<template>
  <div id="app">
    <MyTitle />
    <HeroJumbotron />
  </div>
</template>

<script>
import HeroJumbotron from "./components/HeroJumbotron.vue";
import MyTitle from "./components/MyTitle.vue";
export default {
  name: "App",
  components: {
    MyTitle,
    HeroJumbotron,
  },
};
</script>

<style></style>
