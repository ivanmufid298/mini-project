<template>
  <div>
    <Navbar />
    <Cart />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Cart from "@/components/Cart.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Cart,
    Footer,
  },
};
</script>

<style></style>
