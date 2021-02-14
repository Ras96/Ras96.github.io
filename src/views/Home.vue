<template>
  <div class="home">
    <h1>Ras's Portfolio</h1>
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>

<style>
  img {
    width: 200px;
  }
</style>
