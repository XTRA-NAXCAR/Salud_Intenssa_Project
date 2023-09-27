<template>
  <div class="container-fluid p-2 p-md-3 px-md-5 bg-white">
    <div
      class="container-fluid py-3 d-flex align-items-center justify-content-center"
    >
      <img
        class="img-fluid pt-2"
        src="@/assets/images/logo/logo.jpeg"
        alt="None"
        style="width: 15em"
      />
    </div>
    <div class="row row-cols-2 row-cols-md-4 g-2 g-lg-4">
      <div class="col">
        <div class="card h-100 bg-transparent text-white border-0">
          <div class="card-body">
            <h5 class="card-title mb-4 pb-3 RalewayFont text-black">
              <strong>
                Contacto:
              </strong>
            </h5>
            <p class="card-text text-black"><strong>Teléfono:</strong> +57 302 389 1677</p>
            <p class="card-text text-black">
              <strong>Correo:</strong> info@saludintenssa.com
            </p>
            <p class="card-text text-black">
              <strong>Dirección:</strong> <a href="https://maps.app.goo.gl/aD6YZHAuPXhG8Ba58" target="_blank" class="btn">Edificio Comedal, Oriental Con Caracas Diagonal Clinica Medellín Del Centro, Carrera 46 Número 54 - 14 / Piso 1010</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 bg-transparent text-white border-0">
          <div class="card-body">
            <h5 class="card-title mb-4 pb-3 RalewayFont text-black">Sitio:</h5>
            <div>
              <a class="card-text text-black" href="#" style="text-decoration: none;"><strong>Inicio</strong></a>
            </div>
            <div class="mt-3" @click="$emit('scroll_to_About_Us')" style="cursor: pointer;">
              <a class="card-text text-black" style="text-decoration: none;"><strong>Medicina Estetica Vascular</strong></a>
            </div>
            <div class="mt-3" @click="$emit('scroll_to_products')" style="cursor: pointer;">
              <a class="card-text text-black" style="text-decoration: none;"><strong>Medicina Estetica Facial</strong></a>
            </div>
            <div class="mt-3" @click="$emit('scroll_to_measure')" style="cursor: pointer;">
              <a class="card-text text-black" style="text-decoration: none;"><strong>Medicina Del Dolor</strong></a>
            </div>
            <div class="mt-3" @click="$emit('scroll_to_comparate')" style="cursor: pointer;">
              <a class="card-text text-black" style="text-decoration: none;"><strong>Cosmetología</strong></a>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 bg-transparent text-white border-0">
          <div class="card-body">
            <h5 class="card-title mb-4 pb-3 RalewayFont text-black">Legal:</h5>
            <p class="card-text text-black">Política de privacidad</p>
            <p class="card-text text-black">Términos y condiciones</p>
            <p class="card-text text-black">Cookies</p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100 bg-transparent text-white border-0">
          <div class="card-body">
            <h5 class="card-title mb-4 pb-3 RalewayFont text-black">
              Nuestras Redes:
            </h5>
            <p class="card-text fs-2 text-black">
              <i class="bi bi-instagram pe-3"></i>
              <i class="bi bi-facebook pe-3"></i>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div
    class="container-fluid py-1 d-flex align-items-center justify-content-center fs-5"
    style="background-color: #D1B684"
  >
    <h6 class="text-center RalewayFont">
      <a href="https://www.paginaswebscolombia.com.co/" style="text-decoration: none; color: #000;">
        © 2023 Paginas Webs Colombia | Design by Paginas Webs Colombia Click Aquí
      </a>
    </h6>
  </div>
</template>

<style scoped>
.custom-border-color {
  border-color: #ff8f39;
}
</style>
