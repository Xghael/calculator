<template>
  <div id="app">
    <calculator></calculator>
  </div>
</template>

<script>
import Calculator from "./components/calculator.vue";
export default {
  name: "App",
  components: {
    Calculator,
  },
};
</script>

<style>
body {
  background-color: black;
}
</style>
