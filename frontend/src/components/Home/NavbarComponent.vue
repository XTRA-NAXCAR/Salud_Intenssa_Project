<template>
  <div v-bind:class="['navbar-container', { 'navbar-fixed': isNavbarFixed }]">
    <div class="container-fluid p-0 pe-3">
      <nav class="navbar navbar-expand-lg arial-font custom-weight">
        <div class="container-fluid p-0">
          <div
            class="ms-2 ms-lg-0 ms-xl-3 mt-0 mt-lg-3 d-lg-flex justify-content-center align-items-center"
          >
            <a href="#">
              <img
                src="@/assets/images/logo/logo.jpeg"
                class="img-fluid d-inline img-responsive img-fluid-sm img-fluid-lg img-nav-responsive"
                alt="..."
              />
            </a>
          </div>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
            style="background-color: #D1B684"
          >
            <i class="bi bi-list" style="font-size: 30px; color: #fff"></i>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <div
              class="d-flex d-md-block ms-md-3 justify-content-evenly align-items-center"
              style="width: 100%"
            >
              <ul
                class="navbar-nav ms-auto mb-2 mb-lg-0 d-lg-flex justify-content-evenly custom-margin"
              >
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    MEDICINA ESTETICA VASCULAR
                  </a>
                  <ul class="dropdown-menu">
                    <li><a class="dropdown-item btn" @click="scrollToService('sclerotherapy')">ESCLEROTERAPIA</a></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('laser')">LASER ARAÑAS VASCULARES</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item" @click="scrollToService('venous-doppler')">DOPPLER VENOSO</a></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('reflexotherapy')">REFLEXOTERAPIA</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('medic-consult')">CONSULTA MEDICA VASCULAR</a></li>
                  </ul>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    MEDICINA ESTETICA FACIAL
                  </a>
                  <ul class="dropdown-menu">
                    <li><a class="dropdown-item btn" @click="scrollToService('facial-laser')">LASER FACIAL</a></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('botulinum-toxin')">TOXINA BOTULINICA</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('hyaluronic-acid')">ACIDO HIALURONICO</a></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('regenerative-medicine')">MEDICINA REGENERATIVA</a></li>
                  </ul>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    MEDICINA DEL DOLOR
                  </a>
                  <ul class="dropdown-menu">
                    <li><a class="dropdown-item btn" @click="scrollToService('neural-therapy')">TERAPIA NEURAL</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item btn" @click="scrollToService('biological-therapy')">TERAPIAS BIOLOGICAS</a></li>
                  </ul>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    COSMETOLOGÍA
                  </a>
                  <ul class="dropdown-menu">
                    <li><a class="dropdown-item btn" @click="scrollToService('hydrodermoabrasion')">HIDRODERMOABRASION</a></li>
                  </ul>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from "vue";

const isNavbarFixed = ref(false);

const handleScroll = () => {
  isNavbarFixed.value = window.pageYOffset > 0;
};

onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

onUnmounted(() => {
  window.removeEventListener("scroll", handleScroll);
});

const navbarProps = {
  isNavbarFixed,
};
</script>

<script>
export default {
  methods: {
    scrollToService(targetId) {
      // Encontrar el elemento objetivo
      const targetElement = document.getElementById(targetId);
      
      if (targetElement) {
        const scrollPosition = targetElement.offsetTop - 100;
        window.scrollTo({ top: scrollPosition, behavior: 'smooth' });
      }
    },
  },
};
</script>

<style>
.navbar-container {
  position: absolute;
  background-color: rgba(255, 255, 255, 0.8);
  top: 0;
  left: 0;
  width: 100%;
  z-index: 999;
  transition: background-color 0.3s ease;
}
.nav-item-start{
  color: #d1b684;
  border-bottom: 2px solid #d1b684;
}
.custom-nav-item {
  color: #333333;
}
.custom-nav-item:hover {
  color: #d1b684;
  border-bottom: 2px solid #d1b684;
}
.navbar-fixed {
  position: fixed;
  background-color: #fff;
}
.img-nav-text {
  height: 40px;
}
.img-nav-responsive {
  height: 50px;
}
.custom-margin{
  margin-right: 200px;
}
.custom-weight{
  font-weight: 300;
}
@media (max-width: 580px) {
  .img-nav-responsive {
    height: 50px;
  }
  .img-nav-text {
    height: 40px;
  }
}

@media (min-width: 581px) and (max-width: 992px) {
  .img-nav-responsive {
    height: 35px;
  }
}
</style>
