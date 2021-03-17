<template>
  <div id="app">
    <nav />
    <router-view />
  </div>
</template>
<script>
import nav from "@/components/nav.vue";

export default {
  name: "App",
  component: {
    nav
  }
};
</script>

<style></style>
