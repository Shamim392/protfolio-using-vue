<script setup>
import { ref, computed } from "vue";
import myIntro from "./components/myIntro.vue";
import myHome from "./components/myHome.vue";
import mySkill from "./components/mySkill";
import NotFound from "./components/notFound.vue";
import myHeader from "./components/myHeader.vue";
import myProjects from "./components/myProjects.vue";

const routes = {
  "/": myHome,
  "/about": myIntro,
  "/skill": mySkill,
  "/project": myProjects,
};

const currentPath = ref(window.location.hash);

window.addEventListener("hashchange", () => {
  currentPath.value = window.location.hash;
});

const currentView = computed(() => {
  return routes[currentPath.value.slice(1) || "/"] || NotFound;
});
</script>

<template>
  <myHeader />
  <!-- <a href="#/">Home</a> | <a href="#/about">About</a> |
  <a href="#/non-existent-path">Broken Link</a> -->
  <component :is="currentView" />
</template>
