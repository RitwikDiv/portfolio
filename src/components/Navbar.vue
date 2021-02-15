<template>
  <div
    class="container d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3 bg-white box-shadow"
  >
    <h4 class="my-0 mr-md-auto font-weight-bold">{{ name }}</h4>
    <nav class="my-4 my-md-4 mr-md-5">
      <a class="p-2 text-muted" href="#work"> <strong>Work</strong></a>
      <a class="p-2 text-muted" href="#projects"><strong>Projects</strong></a>
      <a class="p-2 text-muted" href="#skills"><strong>Skills</strong></a>
      <!-- <a class="p-2 text-muted" href="#"><strong>Random</strong></a> -->
    </nav>
    <a class="btn btn-outline-primary btn-sm" href="mailto:ritwik.edu@gmail.com"
      ><strong>Let's talk!</strong></a
    >
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      name: "Ritwik Divakaruni",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
