<template>
  <myHeader />
  <myAbout />
  <myIntro />
</template>

<script>
import myHeader from "./components/myHeader.vue";
import myAbout from "./components/myAbout.vue";
import myIntro from "./components/myIntro";

export default {
  name: "App",
  components: {
    myHeader,
    myAbout,
    myIntro,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
