<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  name: 'MyApp',
  data: () => ({
  }),
  components: {
    AppTitle,
    AppHero
  },
}
</script>

<template>
  <header>
    <AppTitle />
  </header>

  <main>
    <AppHero />
  </main>

  <footer>

  </footer>
</template>

<style></style>