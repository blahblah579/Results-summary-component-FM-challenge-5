<template>
  <v-app class="app">
    <v-main>
      <HomePage />
    </v-main>
  </v-app>
</template>

<script>
import HomePage from "./components/HomePage.vue";

export default {
  name: "App",

  components: {
    HomePage,
  },
};
</script>
<style>
.app {
  background-color: #ffffff;
}
</style>
