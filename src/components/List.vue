<template>
  <div class="list">
    <br>
    <h3>List of objectives: {{ val }}</h3>
    <p>create components</p>
    <p>learn to use components</p>
    <p>learn from youtube videos</p>
    <p>create a bearable website with vue</p>
    <p>learn aws</p>
  </div>
</template>

<script>
export default {
  name: "List",
  props: {
    val: Number
  }
};
</script>

<style scoped>
p {
  color: #42b983;
  display: inline-block;
  padding: 10px;
}
</style>
