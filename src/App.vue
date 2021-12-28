<template>
  <div class="container">
    <LeftBar />
  </div>
</template>

<script>
import LeftBar from "./components/LeftBar.vue";

export default {
  name: "App",
  components: {
    LeftBar,
  },
};
</script>

<style>
.container {
  display: flex;
  width: 100vw;
  height: 100vh;
}
#app {
  font-family: Roboto sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body {
  margin: 0;
}
</style>
