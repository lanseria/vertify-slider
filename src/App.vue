<template>
  <div>
    <Vertify></Vertify>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Vertify } from "../packages/";
export default defineComponent({
  name: "App",
  components: {
    Vertify,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
