<template>
  <div class="custom-background">
    <div class="container-fluid custom-container">
      <h1 class="text-center title-font">
        - MEDICINA ESTETICA VASCULAR -
      </h1>
      <div class="row d-flex justify-content-center">
        <div class="col-5 custom-box me-5" ref="sclerotherapy">
          <div>
            <h2 class="subtitle-font" id="sclerotherapy">ESCLEROTERAPIA</h2>
            <p class="description-font">
              Tratamiento eficaz para venas varicosas y arañas vasculares.
              Mejora la apariencia y alivia los síntomas con este procedimiento
              minimamente invasivo.
            </p>
            <p class="description-font">
              Consiste en inyectar una solución en la vena mediante una aguja.
              La solución de escleroterapia hace que la vena se fibrose. La
              fibrosis obliga a la sangre a circular por venas sanas. Luego, la
              vena colapsada desaparece.
            </p>
            <div class="d-flex justify-content-center">
              <swiper
              :loop="true"
              :autoplay="{
                delay: 2000,
                disableOnInteraction: false,
              }"
                :modules="modules"
                class="mySwiper"
              >
                <swiper-slide><img src="@/assets/images/body/therapy/T1.jpeg" alt="..."></swiper-slide>
                <swiper-slide><img src="@/assets/images/body/therapy/T2.jpeg" alt="..."></swiper-slide>
                <swiper-slide><img src="@/assets/images/body/therapy/T3.jpeg" alt="..."></swiper-slide>
                <swiper-slide><img src="@/assets/images/body/therapy/T4.jpeg" alt="..."></swiper-slide>
              </swiper>
            </div>
          </div>
        </div>
        <div class="col-5 custom-box ms-5">
          <div>
            <h2 class="subtitle-font" id="laser">LASER ARAÑAS VASCULARES</h2>
            <p class="description-font">
              El laser es útil para vasos anómalos están localizados en un nivel
              más superficial de la piel, tienen un calibre mucho menor y, por
              lo tanto, son más difíciles de pinchar.
            </p>
            <p class="description-font">
              La terapia láser para telangiectasias es una solución de
              vanguardia para abordar y eliminar las molestas telangiectasias,
              también conocidas como venas en araña o venas rojas. Este
              procedimiento altamente efectivo ha ganado popularidad gracias a
              sus resultados visibles y a la mejora significativa en la
              apariencia de la piel.
            </p>
            <div class="d-flex justify-content-center">
              <video
                ref="videoRef"
                src="@/assets/images/body/video/laser.mp4"
                class="video-element"
                autoplay
                muted
                @ended="restartVideo"
              >
              </video>
            </div>
          </div>
        </div>

        <div class="col-5 custom-box me-5 mt-5">
          <div>
            <h2 class="subtitle-font" id="venous-doppler">DOPPLER VENOSO</h2>
            <p class="description-font">
              El Doppler Venoso es una avanzada técnica utilizada en nuestras
              modernas instalaciones, este innovador sistema nos permite evaluar
              la circulación sanguínea en tus venas de manera precisa y no
              invasiva.
            </p>
            <p class="description-font">
              La ecografía Doppler es una prueba no invasiva que calcula el
              flujo de la sangre en los vasos sanguíneos haciendo rebotar ondas
              sonoras de alta frecuencia (ecografía) en los glóbulos rojos
              circulantes. En la ecografía común, se utilizan ondas sonoras para
              crear imágenes, pero no se puede mostrar el flujo sanguíneo.
            </p>
            <div class="d-flex justify-content-center">
              <img
                src="@/assets/images/body/doppler.jpeg"
                alt="..."
                class="custom-image"
              />
            </div>
          </div>
        </div>

        <div class="col-5 custom-box ms-5 mt-5">
          <div>
            <h2 class="subtitle-font" id="reflexotherapy">REFLEXOTERAPIA</h2>
            <p class="description-font">
              Con la Reflexoterapia, te sumergirás en un mundo de relajación y
              equilibrio mientras nuestros especialistas altamente capacitados
              trabajan en tus puntos de presión específicos.
            </p>
            <p class="description-font">
              Nuestra Reflexoterapia se basa en la antigua sabiduría de la
              medicina oriental y su enfoque en la conexión entre los puntos de
              presión en los pies y el bienestar general del cuerpo. En nuestra
              clínica, creamos un ambiente tranquilo y acogedor para que puedas
              disfrutar de esta terapia, que tiene como objetivo aliviar el
              estrés, reducir la tensión muscular y mejorar la circulación.
            </p>
            <div class="d-flex justify-content-center">
              <img
                src="@/assets/images/body/reflexotherapy.jpeg"
                alt="..."
                class="custom-image"
              />
            </div>
          </div>
        </div>

        <div class="col-10 custom-box mt-5">
          <div class="row my-5">
            <div class="col-7">
              <h2 class="subtitle-font" id="medic-consult">CONSULTA MEDICA VASCULAR</h2>
              <p class="description-font">
                La consulta vascular está dedicada a la prevención, diagnóstico
                y tratamiento de las enfermedades de las arterias, las venas y
                los vasos linfáticos y en general de todas las
                enfermedades vasculares, así como el segumiento de los
                tratamientos realizados.
              </p>
              <p class="description-font">
                Nos enorgullece ofrecer una atención de vanguardia para abordar
                todas las enfermedades vasculares, asegurando que nuestros
                pacientes reciban la atención de alta calidad que merecen. Además,
                no nos limitamos al tratamiento inicial, sino que también
                proporcionamos un seguimiento meticuloso de los tratamientos
                realizados para garantizar resultados óptimos y la satisfacción de
                nuestros pacientes en su búsqueda de una salud vascular óptima y
                una estética mejorada.
              </p>
            </div>
            <div class="col-5 d-flex align-items-center">
              <div class="d-flex justify-content-center">
                <img
                  src="@/assets/images/body/medic_consult.jpeg"
                  alt="..."
                  class="custom-image"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import 'swiper/css/pagination';
import { EffectCards, Autoplay, Pagination } from "swiper/modules";

const modules = [Autoplay, EffectCards, Pagination];

const videoRef = ref(null);

const playVideo = () => {
  videoRef.value.play();
};

const restartVideo = () => {
  videoRef.value.currentTime = 0;
  videoRef.value.play();
};

onMounted(() => {
  videoRef.value.addEventListener("ended", restartVideo);
  playVideo();
});
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap");
.custom-background {
  background-color: #d1b684;
}
.custom-container {
  padding-top: 120px;
  padding-bottom: 120px;
}
.title-font {
  font-family: "Roboto", sans-serif;
  font-weight: 600;
  font-size: 50px;
  color: #fff;
  margin-bottom: 60px;
}
.subtitle-font {
  font-family: "Roboto", sans-serif;
  font-weight: 600;
  font-size: 40px;
  color: #fff;
}
.description-font {
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  font-size: 20px;
  color: #6e6e6e;
}
.button-font {
  font-family: "Roboto", sans-serif;
  font-weight: 600;
  font-size: 40px;
  color: #2f2f2f;
}
.custom-box {
  box-sizing: border-box;
  padding: 30px;
  border-radius: 50px;
  background: #d1b684;
  box-shadow: 20px 20px 60px #b29b70, -20px -20px 60px #f0d198;
}

.custom-button {
  width: 9em;
  height: 3em;
  border-radius: 30em;
  font-size: 15px;
  font-family: inherit;
  border: none;
  position: relative;
  overflow: hidden;
  z-index: 1;
  box-shadow: 6px 6px 12px #b29b70, -6px -6px 12px #f0d198;
}

.custom-button::before {
  content: "";
  width: 0;
  height: 3em;
  border-radius: 30em;
  position: absolute;
  top: 0;
  left: 0;
  background-image: linear-gradient(to right, #b29b70 0%, #f0d198 100%);
  transition: 0.5s ease;
  display: block;
  z-index: -1;
}

.custom-button:hover::before {
  width: 9em;
}
.custom-image {
  width: 100%;
  border-radius: 25px;
}
.custom-span {
  color: #fff;
}

.video-element{
  width: 100%;
  border-radius: 25px;
}

.swiper {
  width: 100%;
  height: 100%;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;

  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  height: 100%;
  object-fit: cover;
  border-radius: 25px;
}
</style>
