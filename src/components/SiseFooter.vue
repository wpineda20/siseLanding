<template>
  <div>
    <footer class="footer pt-3 pb-3">
      <div class="container">
        <div class="row">
          <div
            class="
              col-12 col-xs-12 col-sm-12
              text-center
              my-auto
              col-md-3
              pt-2
              pb-2
            "
          >
            <a
              class="mya my-auto footer-text"
              href="https://www.cultura.gob.sv"
              target="_blank"
            >
              Ministerio de cultura
            </a>
          </div>
          <div class="col-12 col-xs-12 col-sm-12 text-center my-auto col-md-6">
            <img
              class="color-logo"
              :src="require('../assets/Logo_GOES_horizontal_D.svg')"
              style="width: 350px; margin: auto"
            />
          </div>
          <div
            class="
              col-12 col-xs-12 col-sm-12
              text-center
              my-auto
              col-md-3
              pt-2
              pb-2
            "
          >
            <div class="mya footer-text">Políticas de privacidad</div>
          </div>
        </div>
      </div>
    </footer>
  </div>
  <!-- Footer -->
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>
<style scoped>
footer {
  min-height: 10vh;
  background-color: #e0e5f1;
}
.logo-footer {
  width: 60% !important;
}
.footer-text {
  color: #313945;
  font-weight: 700;
  text-decoration: none;
}
.color-logo {
  filter: invert(46%) sepia(21%) saturate(356%) hue-rotate(185deg)
    brightness(89%) contrast(86%);
}
</style>
