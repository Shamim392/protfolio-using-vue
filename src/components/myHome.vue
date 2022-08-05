<template>
  <!-- <myHeader /> -->
  <myAbout />
  <myIntro />
  <mySkill />
  <myProjects />
  <myFooter />
</template>

<script>
// import myHeader from "./myHeader";
import myAbout from "./myAbout";
import myIntro from "./myIntro";
import mySkill from "./mySkill";
import myProjects from "./myProjects";
import myFooter from "./myFooter";

export default {
  name: "myHome",
  components: {
    // myHeader,
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
