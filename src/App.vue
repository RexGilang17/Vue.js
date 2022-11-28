<template lang="">
  <div id="app">
    <navbar> </navbar>
    <breadcrum></breadcrum>
    <Galley></Galley>
    <Slider></Slider>
    <Footer></Footer>
    <Copyright></Copyright>
    <card></card>
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue'
import Breadcrum from './components/Breadcrum.vue'
import Galley from './components/Galley.vue'
import Slider from './components/Slider.vue'
import Footer from './components/Footer.vue'
import Copyright from './components/Copyright.vue'
import Card from './components/Card.vue'


export default {
  name: 'App',
  components: {
    Navbar,
    Breadcrum,
    Galley,
    Slider,
    Footer,
    Copyright,
    Card,

    
  }
  
}
</script>
