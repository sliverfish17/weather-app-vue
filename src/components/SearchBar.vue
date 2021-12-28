<template>
  <div class="search">
    <input
      class="search__input"
      type="text"
      placeholder="search for places.."
    />
    <button class="search__button"></button>
  </div>
</template>

<script>
export default {
  name: "SearchBar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.search {
  color: white;
  width: 100%;
  height: 44px;
  display: flex;
  gap: 16px;
}
.search__input {
  display: flex;
  background: #303030;
  border: none;
  border-radius: 50px;
  padding: 11px 0 11px 17px;
  width: 72%;
}
::placeholder {
  color: white;
}
.search__button {
  width: 44px;
  height: auto;
  border-radius: 25px;
  background: #303030;
  border: none;
  cursor: pointer;
  display: flex;
}
</style>
