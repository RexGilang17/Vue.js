<template>
    <div class="container container-fluid px-5 mt-5">
        <div class="row ">
<div class="col-2 d-flex flex-column justify-content-between">
    <img id="view" src="../assets/img/side-1.png" alt="" style="width: 50%;">
    <img id="view" src="../assets/img/side-2.png" alt="" style="width: 50%;">
    <img id="view" src="../assets/img/side-3.png" alt="" style="width: 50%;">
    <img id="view" src="../assets/img/side-2.png" alt="" style="width: 50%;">
    <img id="view" src="../assets/img/side-1.png" alt="" style="width: 50%;">
</div>
<!-- Gamabar Utama -->
<div class="col-6">
    <img :src="require('@/assets/img/' + imageLink + '.png')" alt="kursi" class="img" style="width: 500px; height: auto;" id="rounded"  >
</div>
<!-- End Gambar utama -->

<div class="col-4">
    <H2 id="nameKursi">Chair Thatty</H2>
    <p id="price">IDR.12.000.000</p>
    <router-link to="/FormShipping" >
    <button type="button" id="rounded"  style="background-color: pink;"><b> <img src="../assets/img/cart-icon.png" alt=""> Add To Chart</b></button>
    </router-link>  
    <br> <br>
    <hr>
    <br><br>
    <b>About The Product</b> 
    <p>
     Lorem ipsum dolor sit amet consectetur adipisicing elit.
      Corporis enim accusantium id laborum modi animi voluptate, 
      reprehenderit voluptatum nostrum temporibus.
    </p>
    <p>
      Providing a subtle nod to the past, Jetty alsobr 
      provides a perfect solution for the way we
      work today. A comprehensive product family,
      Jetty features a variety of elegant chair and
      sofas.
    </p>
    
</div> 
</div>
    </div>
</template>
<script>
export default {
    name : 'GalleyComponent',
    props: ['imageLink']
}
</script>
<style scoped>
#rounded{
    border-radius: 50px;
}
#view{
    border-radius: 15px;
}



</style>
