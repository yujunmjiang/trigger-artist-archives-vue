<template>
  <div>
    <div class="search-bar">
      <input type="text" id="search-input" placeholder="Search" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Search",
  props: ["search"]
}
</script>

<style scoped>
/* ---- input ---- */

input[type="text"] {
  font-family: 'Rajdhani', sans-serif;
  font-weight: 500;
  font-size: 20px;
  width: 600px;
}
</style>