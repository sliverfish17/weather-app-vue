<template>
  <div class="left">
    <search-bar />
  </div>
</template>

<script>
import SearchBar from "./SearchBar.vue";

export default {
  components: { SearchBar },
  name: "LeftBar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.left {
  padding: 50px;
  display: flex;
  flex-direction: column;
  width: 25%;
  background: #202020;
  color: white;
}
</style>
