<template>
  <div class="">
    <HomePage />
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
body {
  background-image: linear-gradient(to right, rgba(248, 211, 211, 0), rgb(240, 226, 226));
  height: 100vh;
}
</style>

