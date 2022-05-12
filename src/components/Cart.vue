<template>
  <div class="container mt-5">
    <b-list-group>
      <b-list-group-item>
        <button type="button" aria-label="Close" class="close">x</button>
        <div>
          <b-media left-align vertical-align="center">
            <template #aside>
              <b-img
                blank
                blank-color="#ccc"
                width="130"
                alt="placeholder"
              ></b-img>
            </template>
            <h5 class="mt-2 mb-1 text-center">Media object</h5>
            <p class="mt-4 mb-0 text-center">
              <b-button class="btn-qty mr-2" variant="outline-primary"
                >-</b-button
              >
              x 1
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
