<template>
  <div class="custom-background">
    <div class="container custom-container">
      <h1 class="text-center title-font">- SERVICIOS -</h1>
      <div class="row">
        <div class="col-7 custom-card mb-5">
          <h2 class="subtitle-font">Renovación Facial Total</h2>
          <p class="description-font">
            Descubre una gama completa de tratamientos de medicina estética
            facial diseñados para realzar tu belleza natural y rejuvenecer tu
            apariencia. Desde la suavización de arrugas y líneas de expresión
            con Toxina Botulínica hasta la hidratación profunda con Ácido
            Hialurónico, pasando por la regeneración celular con Plasma Rico en
            Plaquetas y la eliminación de manchas con Láser Facial. En nuestra
            clínica, te ofrecemos una experiencia integral de cuidado facial
            para que logres una piel radiante y saludable.
          </p>

          <ul class="items-font">
            <li>MEDICINA ESTÉTICA FACIAL</li>
            <li>CONSULTA MÉDICA ESTÉTICA FACIAL</li>
            <li>TOXINA BOTULÍNICA</li>
            <li>ÁCIDO HIALURÓNICO</li>
            <li>PLASMA RICO EN PLAQUETAS</li>
            <li>LASER FACIAL MANCHAS Y REJUVENECIMIENTO</li>
          </ul>
        </div>
        <div
          class="col-5 d-flex justify-content-center align-items-center mb-5"
        >
          <swiper
            :effect="'cards'"
            :loop="true"
            :autoplay="{
              delay: 3000,
              disableOnInteraction: false,
            }"
            :grabCursor="true"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide
              ><img src="@/assets/images/services/services_1//Services_1.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_1/Services_2.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_1/Services_3.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_1/services_4.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_1/Services_5.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_1/Services_6.jpeg" alt="..."
            /></swiper-slide>
          </swiper>
        </div>

        <div
          class="col-5 d-flex justify-content-center align-items-center my-5"
        >
          <swiper
            :effect="'cards'"
            :loop="true"
            :autoplay="{
              delay: 3000,
              disableOnInteraction: false,
            }"
            :grabCursor="true"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide
              ><img src="@/assets/images/services/services_2/services_1.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_2/services_2.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_2/services_3.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_2/services_4.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_2/services_5.jpeg" alt="..."
            /></swiper-slide>
          </swiper>
        </div>
        <div class="col-7 custom-card my-5">
          <h2 class="subtitle-font">Renovación y Cuidado Integral</h2>
          <p class="description-font">
            Experimenta la excelencia en cuidado y belleza en un solo lugar con
            nuestra gama completa de servicios de cosmetología y tratamientos
            faciales y corporales. Desde la relajante Limpieza Facial Profunda
            hasta la revitalizante Hidrodermoabrasión, pasando por el
            rejuvenecedor Drenaje Linfático Facial y el relajante Masaje
            Corporal, en nuestra clínica te ofrecemos una experiencia integral
            de bienestar y cuidado. Nuestros especialistas están dedicados a
            realzar tu belleza natural y ayudarte a lograr una piel radiante y
            un cuerpo rejuvenecido. Tu bienestar merece lo mejor, y lo
            encontrarás en nuestra clínica de cuidado y belleza de primer nivel.
          </p>

          <ul class="items-font">
            <li>COSMETOLOGÍA</li>
            <li>LIMPIEZA FACIAL PROFUNDA</li>
            <li>HIDRO DERMOABRASIÓN</li>
            <li>DRENAJE LINFÁTICO FACIAL</li>
            <li>MASAJE CORPORAL</li>
          </ul>
        </div>

        <div class="col-7 custom-card mt-5">
          <h2 class="subtitle-font">Salud Integral y Terapias Avanzadas</h2>
          <p class="description-font">
            En nuestra clínica, nos enorgullece ofrecer una amplia gama de
            servicios de medicina general y terapias biológicas para patologías
            crónicas degenerativas, terapia neural, medicina biológica alemana y
            tratamientos para el dolor crónico. Nuestro enfoque integral de la
            salud se basa en la excelencia médica y terapéutica para abordar tus
            necesidades específicas. Ya sea que busques tratamiento para
            afecciones crónicas o un enfoque holístico para mejorar tu calidad
            de vida, nuestro equipo de especialistas está aquí para cuidarte.
            Experimenta una atención médica de vanguardia que te brinda
            soluciones efectivas y un camino hacia una vida más saludable y
            libre de dolor. Tu bienestar es nuestra prioridad número uno.
          </p>

          <ul class="items-font">
            <li>MEDICINA GENERAL</li>
            <li>TERAPIAS BIOLÓGICAS PARA PATOLOGÍAS CRÓNICAS DEGENERATIVAS</li>
            <li>TERAPIA NEURAL</li>
            <li>MEDICINA BIOLÓGICA ALEMANA</li>
            <li>TERAPIAS PARA EL DOLOR CRÓNICO</li>
          </ul>
        </div>
        <div
          class="col-5 d-flex justify-content-center align-items-center mt-5"
        >
          <swiper
            :effect="'cards'"
            :loop="true"
            :autoplay="{
              delay: 3000,
              disableOnInteraction: false,
            }"
            :grabCursor="true"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide
              ><img src="@/assets/images/services/services_3/services_1.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_3/services_2.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_3/services_3.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_3/services_4.jpeg" alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img src="@/assets/images/services/services_3/services_5.jpeg" alt="..."
            /></swiper-slide>
          </swiper>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/effect-cards";
import { EffectCards, Autoplay } from "swiper/modules";

const modules = [Autoplay, EffectCards];
</script>
<style scoped>
.custom-background {
  background-color: #e8e8e8;
}
.custom-container {
  padding-top: 120px;
  padding-bottom: 120px;
}
.title-font {
  font-family: "Roboto", sans-serif;
  font-weight: 600;
  font-size: 50px;
  color: #d1b684;
  margin-bottom: 60px;
}
.subtitle-font {
  font-family: "Roboto", sans-serif;
  font-weight: 600;
  font-size: 40px;
  color: #2f2f2f;
}
.description-font {
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  font-size: 20px;
  color: #6e6e6e;
}
.items-font {
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  font-size: 17px;
  color: #6e6e6e;
}
.custom-card {
  border-radius: 30px;
  box-sizing: border-box;
  padding: 20px;
  background: #e0e0e0;
  box-shadow: 15px 15px 30px #bebebe, -15px -15px 30px #ffffff;
}

.swiper {
  width: 65%;
}

.swiper-slide {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 30px;
  font-size: 22px;
  font-weight: bold;
  color: #fff;
}
.swiper-slide img {
  width: 100%;
}
</style>
