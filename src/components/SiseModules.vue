<template>
  <div class="container">
    <div class="cards-section pt-4 pb-4">
      <div class="cards-section-logo">
        <img
          :src="require('../assets/cultura_logo.jpg')"
          class="text-center"
          width="300"
          height="150"
        />
      </div>
      <div class="cards-section-title">
        <h4 class="text-center fw-bold mb-0">
          Módulos del Sistema Informático de Seguimiento y Evaluación
        </h4>
      </div>
      <div class="cards-section-body">
        <a
          href="https://sise-cuscatlan.cultura.gob.sv/"
          class="text-decoration-none"
        >
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/fact_check.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Plan Cuscatlán</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/handshake.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Plan de Desarrollo Social</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/paid.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Programa de Inversión</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/security.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Plan Control Territorial</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/book.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Agenda Digital</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/lan.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Estratégico</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/engineering.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Operativo</p>
            </div>
          </div>
        </a>
        <a href="" class="text-decoration-none">
          <div class="card-requests shadow">
            <div class="card-icon p-2">
              <img class="icon-w" :src="require('../assets/line_axis.svg')" />
            </div>
            <div class="card-title text-center p-2">
              <p class="mb-0">Ejes Transversales</p>
            </div>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cards-section-title {
  text-transform: capitalize;
  padding: 20px;
  color: #363d4d;
}

.cards-section-body {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  column-gap: 20px;
  row-gap: 20px;
  padding: 20px;
}

.cards-section-logo {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 250px;
  margin: auto;
}
.card-requests {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 4px 4px 12px 1px rgb(210 210 210 / 91%);
  flex: 1 1 auto;
  padding: 1rem 1rem;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  transition: 0.5s;
}
.card-requests:hover {
  cursor: pointer;
  transform: translateY(-10px);
}
.icon-w {
  width: 60px !important;
  filter: invert(23%) sepia(99%) saturate(916%) hue-rotate(198deg)
    brightness(99%) contrast(91%);
}
.card-title {
  color: #363d4d;
  font-weight: bold;
  text-transform: capitalize;
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .cards-section-body {
    display: grid;
    grid-template-columns: 1fr;
    column-gap: 20px;
    row-gap: 20px;
    padding: 20px;
  }
}
</style>