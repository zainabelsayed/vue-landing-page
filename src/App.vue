<template>
<div>
  <Navbar/>
  <HeroSection/>
  <Values/>
  <Features/>
  <Footer/>
</div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import HeroSection from './components/HeroSection.vue'
import Values from './components/Values.vue'
import Features from './components/Features.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components:{
    Navbar,
    HeroSection,
    Values,
    Features,
    Footer
  }
}
</script>

<style>
#app{
  direction: rtl;
  font-family: 'Cairo', sans-serif;
}

</style>
