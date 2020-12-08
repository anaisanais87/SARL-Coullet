<template>
  <div id="app">
    <homePage></homePage>
  </div>
</template>

<script>

import HomePage from "./components/HomePage.vue";

export default {
  name: 'App',
  components: {
    "homePage": HomePage,
  }
}
</script>

<style>
html body {
  margin: 0;
  padding: 0;
}



</style>
