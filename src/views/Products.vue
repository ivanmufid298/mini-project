<template>
  <div>
    <Navbar />
    <h2>Foods List</h2>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Foods",
  components: {
    Navbar,
  },
};
</script>

<style></style>
