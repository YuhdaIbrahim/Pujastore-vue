<template>
<div class="home">
  <headerWeb />
  <carouselComponent />
  <carouselWomenComp />
  <galleryInstaComp />
  <logoComp />
  <footerComp />
</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css';
import headerWeb from '@/components/header.vue';
import carouselComponent from '@/components/carouselComponent.vue';
import carouselWomenComp from '@/components/carouselWomenComp.vue';
import galleryInstaComp from '@/components/galleryInstaComp.vue';
import logoComp from '@/components/logoComp.vue';
import footerComp from '@/components/footerComp.vue';

export default {
  name: 'Home',
  components: {
    headerWeb,
    carouselComponent,
    carouselWomenComp,
    galleryInstaComp,
    logoComp,
    footerComp
  }
};
</script>
