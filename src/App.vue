<script>
// 1. import del miop componente custom
import AppHeader from './components/AppHeader.vue'
import AppVideo from './components/AppVideo.vue'

export default {
  name: 'App',
  // 2. registrazione
  components: {
    AppHeader,
    AppVideo,
  },
  data() {
    return {}
  }
}

</script>

<template>
  <div>
    <AppVideo />
    <!-- 3. Utilizzo del component -->
    <AppHeader />
    <AppHeader />
    <AppHeader />
    <AppHeader />
  </div>
</template>

<style scoped>

</style>
