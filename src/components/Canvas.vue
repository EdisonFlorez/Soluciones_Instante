<template>
  <div class="canvas">
    <main>

      
      <div id="cartelera-servicios" class="cartelera">
        <div class="container-entries">
          <section>
            Se requiere contador experiencia de 2 años contrato a término
            indefinido.
          </section>
        </div>
        <div class="container-entries">
          <section>
            Se requiere contador experiencia de 2 años contrato a término
            indefinido.
          </section>
        </div>
        <div class="container-entries">
          <section>
            Se requiere contador experiencia de 2 años contrato a término
            indefinido.
          </section>
        </div>
        <div class="container-entries">
          <section>
            Se requiere contador experiencia de 2 años contrato a término
            indefinido.
          </section>
        </div>

        <div class="button-box">
          <button id="offer-services">Ofrece un servicio</button>
          <button id="hire-service">Contratar servicio</button>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Canvas",
};
</script>

<style>

.cartelera {
  position: relative;
  width: 80vw;
  height: 85vh;
  margin: 0 10vw;
  background: #91e5f6;
  padding: 0 100px;
  overflow: auto;
}

button {
  width: 10.5em;
  height: 2em;
  border-radius: 2.4em;
  border: none;
  background: #133c55;
  color: white;
  font-family: "Source Serif Pro", serif;
  font-size: 1.4em;
}
.container-entries {
  height: 200px;
  margin: 20px;
  border: 2px solid #133c55;
  border-radius: 9px;
  background: white;
}
.button-box {
  position: sticky;
  bottom: 0;
  padding: 15px;
  background: #91e5f6;
}
#hire-service {
  visibility: visible;
}
.copyright {
  margin-top: 60px;
  padding: 10px;
  background: #133c55;
  text-align: center;
  color: #91e5f6;
}
</style>
