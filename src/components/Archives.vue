<template>
  <div>
    <!-- <div class="search-bar">
      <input type="text" id="search-input" placeholder="Search" />
    </div> -->

    <div v-bind:key="archive.id" v-for="archive in archives">
      <h3>{{archive.name}}</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "Archives",
  props: ["archives"]
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