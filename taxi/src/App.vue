<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavComponent from './components/navComponent.vue'
import LinhaComponet from './components/linhaComponet.vue';
import SectionHome from './components/sectionHome.vue';
import SectionTour from './components/sectionTour.vue';
import sectionCidade from './components/sectionCidade.vue';
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/navigation';

// Import required modules
import { Navigation } from 'swiper/modules';

// Declare the modules to be used
const modules = [Navigation];

</script>

<template>
  <NavComponent />
  <LinhaComponet />
  <SectionHome />
  <LinhaComponet />
  <sectionCidade />
  <LinhaComponet />
  <SectionTour />
  <RouterView />
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
</style>
