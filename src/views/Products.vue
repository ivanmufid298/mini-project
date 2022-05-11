<template>
  <div>
    <Navbar />
    <h2>Product List</h2>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Products",
  components: {
    Navbar,
  },
};
</script>

<style></style>
