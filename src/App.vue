<template>
  <SiseHeader />
  <main>
    <SiseModules />
  </main>
  <SiseFooter />
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
</template>

<script>
import SiseHeader from "./components/SiseHeader.vue";
import SiseModules from "./components/SiseModules.vue";
import SiseFooter from "./components/SiseFooter.vue";

export default {
  name: "App",
  components: {
    SiseHeader,
    SiseModules,
    SiseFooter,
  },
};
</script>

<style>
#app {
  font-family: "Nunito", sans-serif;
}
html,
body {
  background-color: #fff;
  scroll-behavior: smooth;
}

main {
  min-height: 80vh;
  background-color: #fff;
}

header,
main,
footer {
  flex-shrink: 0;
}
</style>
