<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <header>
    <AppTitle></AppTitle>
  </header>
  <main>
    <AppHero></AppHero>
  </main>
</template>

<style>
header {
  height: 80px;
  background-color: aqua;
}
</style>
