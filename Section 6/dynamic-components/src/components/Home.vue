<template>
  <h1>Home Page</h1>
</template>

<script>
  export default {
    name: "HomeComponent",
    unmounted() {
      console.log("Home component unmounted");
    },
    activated() {
      console.log("Home component activated");
    },
    deactivated() {
      console.log("Home component deactivated");
    },
  };
</script>

<style></style>
