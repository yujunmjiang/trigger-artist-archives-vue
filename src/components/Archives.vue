<template>
  <div>
    <div v-bind:key="archive.id" v-for="archive in archives">
      <p>{{archive.name}}</p>
      <p>{{archive.title}}</p>
      <p>{{archive.intro}}</p>
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