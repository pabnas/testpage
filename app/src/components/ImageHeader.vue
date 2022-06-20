<template>
  <div class="imgBG">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12 col-lg-6">
          <img
            src="@/assets/img/photo2.jpg"
            alt="image"
            class="rounded img-fluid my-3 w-50"
          />
        </div>
        <div class="col justify-content-center">
          <p class="fs-1 mt-3 fw-bold text-white text-shadow">
            Valeria Montoya Real
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ImageHeader",
};
</script>

<style scoped lang="scss">
.imgBG {
  background: linear-gradient(
    90deg,
    rgba(131, 58, 180, 1) 0%,
    rgba(253, 29, 29, 1) 50%,
    rgba(252, 176, 69, 1) 100%
  );
}

.text-shadow {
  text-shadow: 2px 2px 3px black, 0 0 1em black, 0 0 0.2em black;
}
</style>
