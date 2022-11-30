<template >
    <div >
      <navbar> </navbar>
      <breadcrum></breadcrum>
      <Galley :imageLink="img"></Galley>
      <Slider @changePictures="fromSlider"></Slider>
      <Footer></Footer>
      <Copyright></Copyright>

    </div>
  </template>
  <script>
  import Navbar from '../components/Navbar.vue'
  import Breadcrum from '../components/Breadcrum.vue'
  import Galley from '../components/Galley.vue'
  import Slider from '../components/Slider.vue'
  import Footer from '../components/Footer.vue'
  import Copyright from '../components/Copyright.vue'
 
  
  
  export default {
    name: 'DetailPage',
    components: {
      Navbar,
      Breadcrum,
      Galley,
      Slider,
      Footer,
      Copyright,
      
    },
    data(){
    return{
      img : "chair"
    }
  },
  methods : {
    fromSlider : function(Image) {
      this.img = Image
    }
  }
}
    
  
  </script>
  