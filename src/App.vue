<template>
  <myHeader />
  <myAbout />
  <myIntro />
  <mySkill />
  <myProjects />
  <myFooter />
</template>

<script>
import myHeader from "./components/myHeader";
import myAbout from "./components/myAbout";
import myIntro from "./components/myIntro";
import mySkill from "./components/mySkill";
import myProjects from "./components/myProjects";
import myFooter from "./components/myFooter";

export default {
  name: "App",
  components: {
    myHeader,
    myAbout,
    myIntro,
    mySkill,
    myProjects,
    myFooter,
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
