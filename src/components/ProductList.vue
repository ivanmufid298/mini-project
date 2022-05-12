<template>
  <div class="container">
    <div class="row">
      <b-card
        v-for="item in products"
        :key="item.id"
        :title="item.title"
        :img-src="item.imgUrl"
        :img-alt="item.title"
        img-top
        tag="article"
        style="max-width: 18rem"
        class="ml-1 mb-4"
      >
        <b-card-text> $ {{ item.price }} </b-card-text>

        <b-button href="#" variant="primary">Add to Cart</b-button>
      </b-card>
    </div>
  </div>
</template>

<script>
import products from "../assets/dummy/products.json";
import { mapGetters, mapActions } from "vuex";
export default {
  name: "ProductList",
  data() {
    return {
      products,
    };
  },
  mounted() {
    this.getProducts;
  },
  computed: {
    ...mapGetters(["products"]),
  },
  methods: {
    ...mapActions(["getProducts"]),
  },
};
</script>

<style></style>
