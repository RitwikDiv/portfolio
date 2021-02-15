<template>
  <div id="d-flex flex-row">
    <Navbar />
    <Intro class="mt-3 mb-4" />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
import Intro from "./components/Intro.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Intro,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap");

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  /* font-family: "Inter", sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  border-top-style: solid;
  border-width: 6px;
  border-color: #007bff;
}
</style>
