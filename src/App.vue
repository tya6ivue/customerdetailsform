<template>
  <div id="app">
    <AssignmentSec />
  </div>
</template>

<script>
import AssignmentSec from "./components/assignmentSec.vue";

export default {
  name: "App",
  components: {
    AssignmentSec,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
