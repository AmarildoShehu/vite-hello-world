<script>
import AppTitle from './components/AppTitle.Vue'

export default {
  name: 'MyApp',
  data: () => ({
    name: 'Ciao',
  }),
  components: {
    AppTitle: AppTitle
  },
}
</script>

<template>
  <header>
    <AppTitle />
  </header>

  <main>

    <div class="jumbotron"></div>
  </main>

  <footer>

  </footer>
</template>

<style></style>