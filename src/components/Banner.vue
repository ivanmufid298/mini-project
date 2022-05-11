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
                  <strong>Delicious Food Menu, </strong><br />
                  in Your Gadget
                </h2>
                <p>Segera pilih makanan kesukaan anda</p>
                <button class="btn btn-lg btn-success">
                  <b-icon-arrow-right></b-icon-arrow-right> Pesan
                </button>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <img src="../assets/ilustrasi.png" width="100%" />
          </div>
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="row mt-4">
      <div class="col-md-6">
        <img src="../assets/ilustrasi.png" width="100%" />
      </div>
      <div class="col-md-6">
        <div class="d-flex h-100">
          <div class="justify-content-center align-self-center">
            <h2>
              <strong>Delicious Food Menu, </strong><br />
              in Your Gadget
            </h2>
            <p>Segera pilih makanan kesukaan anda</p>
            <button class="btn btn-lg btn-success">
              <b-icon-arrow-right></b-icon-arrow-right> Pesan
            </button>
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
