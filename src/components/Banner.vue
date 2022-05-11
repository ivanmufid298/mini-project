<template>
  <div>
    <!-- Dekstop -->
    <div class="banner">
      <div class="d-none d-md-block">
        <div class="row mt-4">
          <div class="col-md-6">
            <div class="d-flex h-100">
              <div class="justify-content-center align-self-center">
                <h2>
                  <strong>Electro</strong><br />
                  in Your Age
                </h2>
                <p>Find Your Powerfull Device</p>
                <router-link class="btn btn-lg btn-info" to="/products"
                  >Shop Now</router-link
                >
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <img src="../assets/Banner.png" width="100%" />
          </div>
        </div>
      </div>
    </div>

    <!-- Mobile -->

    <div class="row mt-4">
      <div class="row mt-4 d-sm-block d-md-none">
        <div class="col-md-6">
          <img src="../assets/Banner.png" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong> Electro</strong><br />
                in Your Age
              </h2>
              <p>Find Your Powerfull Device</p>
              <router-link class="btn btn-lg btn-info" to="/products"
                >Shop Now</router-link
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style></style>
