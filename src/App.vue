<template>
  <div id="app">
    <Header />
    <Carousel />
    <Cep />
      <router-view/>
    <Footer />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->

  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Carousel from '@/components/Carousel.vue';
import Cep from '@/components/Cep.vue';

export default {
  components: {
    Header,
    Footer,
    Carousel,
    Cep,
  },
};
</script>

<style>
  *{
    margin: 0;
  }
</style>
