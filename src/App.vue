<template>
  <div id="app">
    <app-document fullName="Васильев Василий Васильевич" />
  </div>
</template>

<script>
import AppDocument from "./components/AppDocument.vue";

export default {
  name: "App",
  components: {
    AppDocument,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: justify;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
