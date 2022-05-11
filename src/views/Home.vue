<template>
  <div class="home">
    <Navbar />
    <div class="container">
      <Banner />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Banner from "@/components/Banner.vue";
export default {
  name: "Home",
  components: {
    Navbar,
    Banner,
  },
};
</script>
