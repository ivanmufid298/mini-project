<template>
  <div>
    <Navbar />
    <ProductList />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import ProductList from "@/components/ProductList.vue";

export default {
  name: "Products",
  components: {
    Navbar,
    ProductList,
  },
};
</script>

<style></style>
