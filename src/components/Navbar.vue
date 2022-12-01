<template>
   
        <nav class="navbar navbar-expand-lg navbar-light  " id="nav">
       <div class="container-fluid px-5">
         <a class="navbar-brand" href="#"><img src="../assets/img/logo.png" alt=""></a>
         <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
           <span class="navbar-toggler-icon"></span>
         </button>
         <div class="d-flex justify-content-between" id="navbarText">
           <ul class="navbar-nav ms-auto mb-10 mb-lg-2">
             <li class="nav-item px-3">
               <a class="nav-link active" aria-current="page" href="#">Show collapse</a>
             </li>
             <li class="nav-item px-3">
               <a class="nav-link active" href="#">Catalog</a>
             </li>
             <li class="nav-item px-3">
               <a class="nav-link active" href="#">Delivery</a>
             </li>
             <li class="nav-item px-3">
                 <a class="nav-link active" href="#">Reward</a>
               </li>
             <li class="nav-item px-3">
                <img id="gambarutama"  src="../assets/img/cart-icon.png" alt="#">
               </li>
           </ul>
         </div>
       </div>
     </nav>
  </template>
  
  <script>
  export default {
    name: 'NavbarView',
  }
  </script>
<style scoped>
#nav{
    background-color: #009EFF;
}




</style>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
 
  
 