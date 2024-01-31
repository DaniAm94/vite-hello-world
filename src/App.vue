<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  name: 'MyApp',
  data: () => ({

  }),
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="container">
    <AppTitle />
    <AppHero />
  </div>
</template>

<style>
.container {
  max-width: 1080px;
  margin: auto;
  text-align: center;
}
</style>