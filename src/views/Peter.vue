<template>
  <div class="peter">
    <h1>Peter's home page</h1>
    <List val="5"/>
  </div>
</template>

<script>
// @ is an alias to /src
import List from "@/components/List.vue";

export default {
  name: "peter",
  components: {
    List
  }
};
</script>
