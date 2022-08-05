<script setup>
import { ref, computed } from "vue";
import myIntro from "./components/myIntro.vue";
import myHome from "./components/myHome.vue";
import mySkill from "./components/mySkill";
import NotFound from "./components/notFound.vue";
import myHeader from "./components/myHeader.vue";
import myProjects from "./components/myProjects.vue";
import myFooter from "./components/myFooter.vue";

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
  <component :is="currentView" />
  <myFooter />
</template>
