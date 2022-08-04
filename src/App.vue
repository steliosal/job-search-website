<template>
  <MainNav class="text-center text-2xl bg-slate-900 text-white" />
  <h1 class="mt-8 text-6xl text-center">Hello Vue</h1>
</template>

<script>
import MainNav from "@/components/MainNav.vue";

export default {
  name: "App",
  components: {
    MainNav,
  },
};
</script>
