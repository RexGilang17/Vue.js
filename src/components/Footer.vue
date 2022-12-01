<template lang="">
    <footer>
    <div class="footerTitle text-center " id="nav">

        <div class="container container-fluid px-5 py-5">
            <a class="navbar-brand" href="#">
                <img src="../assets/img/logo.png" alt="">
            </a>
            <div class="text-center">
            <img  src="/Asset/logo.png" alt="">
            </div>
            <div class="row py-5 justify-content" >
                <div class="col-3">
                    <b >Overview</b>
                    <p ><a href="/BotsTrap/shippingForm.html" style="text-decoration: none; color :black; ">Shipping </a> </p>
                    <p>Refund</p>
                    <p>Promotion</p>
                </div>
                <div class="col-3">
                    <b>Company</b>
                    <p>About</p>
                    <p>Career</p>
                    <p>Contact Us</p>
                </div>
                <div class="col-3">
                    <b>Explore</b>
                    <p>Term & Conds</p>
                    <p>Privacy Policy</p>
                    <p>For Developer</p>
                    
                </div>
                <div class="col-3">
                    <b>Special Letter</b>
                        <form class="d-flex" id="btnSubmit">
                          <input class="form-control" id="inputNama"  type="email"  placeholder="Masukan Email" required>
                          <button class="btn btn-outline-danger"  style="background-color:pink ;" type="submit" ><img src="../assets/img/tele-icon.png" alt=""></button>
                        </form>              
                </div>
              </div>
    </div>
</div>
</footer>
</template>
<script>
export default {
    name:'FooterView',
}
</script>
<style scoped>
    #nav{
        background-color: #AAC4FF;
    }
</style>