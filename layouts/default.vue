<template>
  <v-app class="app">
    <app-header />
    <Nuxt />
  </v-app>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue'
export default {
  name: 'DefaultLayout',
  components: { AppHeader },
  data() {
    return {}
  },
}
</script>
<style scoped>
.app {
  background: url('https://pizza4ps.com/common2017/img/other/bg_body.gif')
    repeat 0 0;
}
</style>
