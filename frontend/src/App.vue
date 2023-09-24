<script setup>
import NavbarComponent from '@/components/Home/NavbarComponent.vue';
import PictureMainComponent from '@/components/Home/PictureMainComponent.vue';
import MainTextComponent from '@/components/Body/MainTextComponent.vue';
import IntermediatePictureComponent from '@/components/Body/IntermediatePictureComponent.vue';
import TreatmentsComponent from '@/components/Body/TreatmentsComponent.vue';
import ServicesComponent from '@/components/Body/ServicesComponent.vue';
import PainMedicine from './components/Body/PainMedicine.vue';
import FooterComponent from '@/components/Footer/FooterComponent.vue';
import WhatsAppFloatComponent from '@/components/Social_Networks/WhatsAppFloatComponent.vue';
import FloatingSocialNetwork from './components/Social_Networks/FloatingSocialNetwork.vue';
</script>

<template>
<NavbarComponent></NavbarComponent>
<PictureMainComponent></PictureMainComponent>
<MainTextComponent></MainTextComponent>
<IntermediatePictureComponent></IntermediatePictureComponent>
<TreatmentsComponent></TreatmentsComponent>
<ServicesComponent></ServicesComponent>
<PainMedicine></PainMedicine>
<FooterComponent></FooterComponent>
<WhatsAppFloatComponent></WhatsAppFloatComponent>
<FloatingSocialNetwork></FloatingSocialNetwork>
</template>

<style>
.arial-font{
  font-family: Arial, sans-serif;
}

body {
  overflow-x: hidden;
}
::-webkit-scrollbar {
  width: 10px; 
}

::-webkit-scrollbar-track {
  background-color: #fff; 
}

::-webkit-scrollbar-thumb {
  background-color: #d1b684; 
  border-radius: 5px; 
}

::-webkit-scrollbar-thumb:hover {
  background-color: #d1b684; 
}
</style>
