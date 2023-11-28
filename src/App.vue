<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div>
    <h1>Benvenuto in Vue</h1>
  </div>
  <AppTitle />
  <AppHero />
</template>

<style scoped></style>
