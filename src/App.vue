<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <HomeBanner title="Hello" />
    <OurServices title="Hello" />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import HomeBanner from "./components/HomeBanner.vue";
import OurServices from "./components/OurServices.vue";

export default {
  name: "app",
  components: {
    // HelloWorld,
    HomeBanner,
    OurServices
  }
};
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
