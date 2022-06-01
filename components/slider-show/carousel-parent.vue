<template>
  <div class="carousel">
    <div class="carousel-inner">
      <carouse-item
        v-for="(slide, index) in slides"
        :key="`item-${index}`"
        :slide="slide"
        :current-slide="currentSlide"
        :index="index"
      />
    </div>
  </div>
</template>

<script>
import CarouseItem from '@/components/slider-show/carousel-item'
export default {
  components: { CarouseItem },
  props: {
    slides: {
      type: Array,
      default: () => [],
    },
  },

  data() {
    return {
      currentSlide: 0,
      slideInterval: null,
    }
  },

  mounted() {
    this.slideInterval = setInterval(() => {
      const index =
        this.currentSlide < this.slides.length - 1 ? this.currentSlide + 1 : 0
      this.setCurrentSlide(index)
    }, 3000)
  },

  beforeUnmount() {
    clearInterval(this.slideInterval)
  },

  methods: {
    setCurrentSlide(index) {
      this.currentSlide = index
    },
  },
}
</script>

<style lang="scss" scoped>
.carousel {
  display: flex;
  justify-content: center;

  > .carousel-inner {
    position: relative;
    width: 100%;
    height: 400px;
    overflow: hidden;
  }
}
</style>
