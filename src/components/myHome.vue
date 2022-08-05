<template>
  <myAbout />
  <myIntro />
  <mySkill />
  <myProjects />
</template>

<script>
import myAbout from "./myAbout";
import myIntro from "./myIntro";
import mySkill from "./mySkill";
import myProjects from "./myProjects";

export default {
  name: "myHome",
  components: {
    myAbout,
    myIntro,
    mySkill,
    myProjects,
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
