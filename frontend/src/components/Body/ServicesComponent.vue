<template>
  <div class="custom-background">
    <div class="container custom-container">
      <h1 class="text-center title-font">
        - MEDICINA ESTETICA FACIAL -
      </h1>
      <div class="row">
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
              ><img
                src="@/assets/images/services/Facial_Laser/1.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Facial_Laser/2.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Facial_Laser/3.jpeg"
                alt="..."
            /></swiper-slide>
          </swiper>
        </div>
        <div class="col-7 custom-card my-5">
          <h2 class="subtitle-font">LASER FACIAL</h2>
          <p class="description-font">
            El revolucionario tratamiento con rayo láser que ofrecemos en la
            Clínica Salud Intenssa proporciona una serie de ventajas notables
            para aquellos que buscan rejuvenecer su piel de manera efectiva y
            poco invasiva. Este procedimiento altamente avanzado no solo se
            enfoca en la capa externa de la piel, la epidermis, sino que también
            se adentra en las capas más profundas, alcanzando la dermis. Lo más
            sorprendente es que todo esto se logra sin necesidad de cirugía, lo
            que lo convierte en una opción muy atractiva para quienes desean
            mejorar su apariencia sin los inconvenientes de procedimientos
            invasivos.
          </p>
          <p class="description-font">
            El proceso de tratamiento con rayo láser es delicado y seguro.
            Durante la sesión, el láser trabaja de manera gradual y controlada,
            estimulando la producción natural de colágeno en la piel a lo largo
            del tiempo. Esta revitalización interna de la piel tiene como
            resultado un incremento en el tono y la textura de la piel,
            dejándola más suave, firme y juvenil.
          </p>
        </div>

        <div class="col-7 custom-card my-5">
          <h2 class="subtitle-font">TOXINA BOTULINICA</h2>
          <p class="description-font">
            La toxina botulínica, conocida por su nombre comercial Botox, es un
            tratamiento altamente efectivo que ofrece una serie de ventajas
            notables en el ámbito de la estética facial. Este procedimiento
            actúa con precisión y temporabilidad al reducir la contracción de
            los músculos faciales, lo que da como resultado una piel
            visiblemente más tersa y tonificada. Además de corregir las arrugas
            existentes, la toxina botulínica también desempeña un papel
            fundamental en la prevención de su progresión, lo que la convierte
            en una opción preventiva atractiva para mantener una apariencia
            juvenil a lo largo del tiempo.
          </p>
          <p class="description-font">
            Los beneficios de la toxina botulínica son múltiples:
          </p>
          <ul class="items-font">
            <li>
              Reducción de arrugas:
              <p>
                Las inyecciones de Botox suavizan arrugas y líneas de expresión,
                especialmente en áreas como la frente, entrecejo y patas de
                gallo.
              </p>
            </li>
            <li>
              Efecto temporal:
              <p>
                El tratamiento es reversible y sus efectos son temporales,
                brindando flexibilidad para adaptarse a los cambios en la
                apariencia deseada.
              </p>
            </li>
            <li>
              Aspecto natural:
              <p>
                El Botox permite mantener una apariencia fresca y natural sin
                una apariencia artificial o congelada.
              </p>
            </li>
            <li>
              Procedimiento no invasivo:
              <p>
                No requiere cirugía ni tiempo de recuperación, lo que permite a
                los pacientes retomar sus actividades normales de inmediato.
              </p>
            </li>
            <li>
              Prevención de arrugas futuras:
              <p>
                Al debilitar y paralizar ciertos músculos faciales, la toxina
                botulínica bloquea la formación de nuevas arrugas y líneas de
                expresión.
              </p>
            </li>
            <li>
              Mejora la autoestima:
              <p>
                Los resultados visibles después del tratamiento pueden aumentar
                la confianza y la autoestima.
              </p>
            </li>
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
              ><img
                src="@/assets/images/services/Botulinum_toxin/1.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Botulinum_toxin/2.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Botulinum_toxin/3.jpeg"
                alt="..."
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
              ><img
                src="@/assets/images/services/Hyaluronic_acid/1.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Hyaluronic_acid/2.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Hyaluronic_acid/3.jpeg"
                alt="..."
            /></swiper-slide>
          </swiper>
        </div>
        <div class="col-7 custom-card my-5">
          <h2 class="subtitle-font">ACIDO HIALURONICO</h2>
          <p class="description-font">
            El ácido hialurónico, un aliado esencial en el mundo de la belleza y
            la estética, ofrece una serie de beneficios extraordinarios para la
            piel. Este compuesto se destaca por su capacidad para proporcionar
            una hidratación profunda, una mejora notable en la apariencia y
            textura de la piel y la corrección de arrugas y líneas de expresión.
            Uno de sus mayores atributos radica en su capacidad para restablecer
            tanto la densidad como el volumen de nuestro rostro, contribuyendo a
            una apariencia más juvenil y revitalizada.
          </p>
          <p class="description-font">
            Las ventajas del ácido hialurónico son abundantes:
          </p>
          <ul class="items-font">
            <li>
              Hidratación profunda:
              <p>
                El ácido hialurónico tiene una extraordinaria capacidad para
                retener la humedad, lo que resulta en una piel visiblemente más
                suave, flexible y radiante.
              </p>
            </li>
            <li>
              Relleno de arrugas:
              <p>
                Este compuesto rellena eficazmente las arrugas y las líneas de
                expresión, proporcionando una apariencia más lisa y juvenil.
              </p>
            </li>
            <li>
              Estimulación del colágeno:
              <p>
                Además de sus propiedades de relleno, el ácido hialurónico
                estimula la producción de colágeno en la piel, lo que contribuye
                a una estructura dérmica más firme y tonificada.
              </p>
            </li>
            <li>
              Resultados naturales:
              <p>
                Los resultados son notorios pero sutiles, lo que permite
                mantener una apariencia natural sin exageraciones.
              </p>
            </li>
            <li>
              Comodidad y seguridad:
              <p>
                Los procedimientos de ácido hialurónico son mínimamente
                invasivos y conllevan un tiempo de recuperación breve, lo que
                los hace ideales para personas con agendas ocupadas.
              </p>
            </li>
          </ul>
        </div>

        <div class="col-7 custom-card mt-5">
          <h2 class="subtitle-font">MEDICINA REGENERATIVA</h2>
          <p class="description-font">
            La medicina regenerativa se despliega como un vasto horizonte de
            disciplinas científicas, que abarcan desde la sofisticada ingeniería
            de tejidos hasta la intrincada investigación sobre la capacidad de
            autorregeneración inherente a nuestro propio cuerpo. En este
            fascinante panorama, observamos cómo el organismo despliega sus
            propios sistemas, a veces colaborando con material biológico
            externo, para desencadenar procesos de recreación celular y
            restauración de tejidos y órganos.
          </p>
          <p class="description-font">
            Esta extraordinaria rama de la medicina busca ofrecer una serie de ventajas notables:
          </p>
          <ul class="items-font">
            <li>Potenciación de la regeneración:<p>La medicina regenerativa impulsa la capacidad natural del cuerpo para sanar y repararse a sí mismo, lo que puede acelerar la recuperación de lesiones y enfermedades.</p></li>
            <li>Tratamientos personalizados:<p>La diversidad de enfoques en medicina regenerativa permite adaptar los tratamientos a las necesidades específicas de cada paciente, garantizando una atención más precisa.</p></li>
            <li>Mínima invasión:<p>Muchos de los procedimientos regenerativos son mínimamente invasivos, lo que reduce el riesgo y el tiempo de recuperación para los pacientes.</p></li>
            <li>Reducción de efectos secundarios:<p>Al utilizar materiales biológicos autólogos (propios del paciente), se minimiza el riesgo de reacciones adversas.</p></li>
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
              ><img
                src="@/assets/images/services/Regenerative_Medicine/1.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Regenerative_Medicine/2.jpeg"
                alt="..."
            /></swiper-slide>
            <swiper-slide
              ><img
                src="@/assets/images/services/Regenerative_Medicine/3.jpeg"
                alt="..."
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
  width: 75%;
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
