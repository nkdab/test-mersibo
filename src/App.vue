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
