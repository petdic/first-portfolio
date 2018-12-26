<template>
  <div class="list">
    <br>
    <h3>List of objectives: {{ val }}</h3>
    <span v-if="seen">just some objectives to help the learning process</span>
    <br>
    <p>create components</p>
    <p>learn to use components</p>
    <p>style guide</p>
    <p>interpolations: mustache braces | v-html | v-bind:id="dynamicId"</p>
    <p>directives: v-if="seen"</p>
    <p>arguments: v-on:click="doSomething"</p>
    <p>shorthand: @click="doSomething"</p>
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
  },
  data() {
    return {
      seen: true
    };
  }
};
</script>

<style scoped>
p {
  color: cornflowerblue;
}

.list {
  background: lightgray;
}
</style>
