<template >
    <div >
      <navbar> </navbar>
      <Form></Form>
      <Footer></Footer>
      <Copyright></Copyright>

    </div>
  </template>
  <script>
  import Navbar from '../components/Navbar.vue'

  import Form from '../components/FormShipping.vue'
  import Footer from '../components/Footer.vue'
  import Copyright from '../components/Copyright.vue'
 
  
  
  export default {
    name: 'DetailPage',
    components: {
      Navbar,
      
      Form,
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
  