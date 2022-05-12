<template>
  <div class="container mt-5">
    <b-list-group>
      <b-list-group-item v-for="item in cart" :key="item.id">
        <button type="button" aria-label="Close" class="close">x</button>
        <div>
          <b-media left-align vertical-align="center">
            <template #aside>
              <b-img :src="item.imgUrl" width="130" :alt="item.title"></b-img>
            </template>
            <h5 class="mt-2 mb-1 text-center">{{ item.title }}</h5>
            <p class="mt-4 mb-0 text-center">
              <b-button class="btn-qty mr-2" variant="outline-primary"
                >-</b-button
              >
              x {{ item.qty }}
              <b-button class="btn-qty ml-2" variant="outline-primary"
                >+</b-button
              >
            </p>
          </b-media>
        </div>
      </b-list-group-item>
    </b-list-group>
  </div>
</template>

<script>
import { mapGetters } from "vuex";

export default {
  computed: {
    ...mapGetters(["cart"]),
  },
};
</script>
