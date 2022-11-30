<template >
    <div >
      <navbar> </navbar>
      <breadcrum></breadcrum>
      <Order></Order>
      <Footer></Footer>
      <Copyright></Copyright>

    </div>
  </template>
  <script>
  import Navbar from '../components/Navbar.vue'
  import Breadcrum from '../components/Breadcrum.vue'
  import Order from '../components/Order.vue'
  import Footer from '../components/Footer.vue'
  import Copyright from '../components/Copyright.vue'
 
  
  
  export default {
    name: 'DetailPage',
    components: {
      Navbar,
      Breadcrum,
      Order,
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
  