<template>
  <transition name="slide-in">
    <div v-show="currentSlide === index" class="carousel-item">
      <img :src="slide" />
    </div>
  </transition>
</template>

<script>
export default {
  props: {
    slide: {
      type: String,
      default: '',
    },
    currentSlide: {
      type: Number,
      default: 0,
    },
    index: {
      type: Number,
      default: 0,
    },
  },
}
</script>

<style lang="scss" scoped>
.carousel-item {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

.slide-in-enter-active,
.slide-in-leave-active {
  transition: all 1s ease-in-out;
}
</style>
