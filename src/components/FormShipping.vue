<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-light mt-2">
            <div class="d-flex px-5">
            <router-link class="nav-link active" style="text-decoration:none ; color: black;" aria-current="page" to="/Detail">Home</router-link>
            <router-link class="nav-link active" style="text-decoration:none ; color: black;" aria-current="page" to="/Detail">Detail</router-link>
            <router-link class="nav-link active" style="text-decoration:none ; color: black;" aria-current="page" to="/FormShipping">Shipping</router-link>
            <link rel="apple-touch-icon" href="/latihanBs.html">
            </div>
        </nav>
    
        <div class="row justify-content-center my-5">
            <div class="col-4 border border-danger p-5 rounded " style="" id="formShipping">    
                <form id="formSubmit" class="mt-5" >       <!-- ID Form Shipping -->
                  <h1 class=" text-center">Shipping Form</h1>
                    <div class="d-flex">
                        <div class="form-group">
                            <label for="exampleInputEmail1">First Name</label>
                            <input type="first" class="form-control" id="firstName" aria-describedby="emailHelp"
                                placeholder="Enter your first name" required />
                        </div>
                        <div class="form-group mx-3">
                            <label for="exampleInputPassword1">Phone number</label>
                            <input type="phone" class="form-control" id="exampleInputPassword1"
                                placeholder="Enter phone number"  />
                        </div>
                        <div>
    
                        </div>
                    </div>
    
                    <div class="d-flex">
                        <div class="form-group">
                            <label for="exampleInputEmail1">Last name</label>
                            <input type="last" class="form-control" id="lastName" aria-describedby="emailHelp"
                                placeholder="Enter your last name" required />
                        </div>
                        <div class="form-group mx-3">
                            <label for="exampleInputPassword1">City</label>
                            <input type="city" class="form-control" id="exampleInputPassword1" placeholder="Enter city"  />
                        </div>
                        <div>
    
                        </div>
                    </div>
    
                    <div class="d-flex">
                        <div class="form-group">
                            <label for="exampleInputEmail1">Email address</label>
                            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
                                placeholder="Enter Email" />
                        </div>
                        <div class="form-group mx-3">
                            <label for="exampleInputPassword1">Postal Code</label>
                            <input type="postal" class="form-control" id="exampleInputPassword1"
                                placeholder="Enter postal code"  />
                        </div>
                        <div>
                        </div>
                    </div>
    
                    <div class="form-group">
                        <label for="exampleInputEmail1">Address</label>
                        <textarea type="address" class="form-control" id="address" aria-describedby="emailHelp"
                            placeholder="Enter address" required></textarea>
                    </div>
                    <br>
                    <router-link to="/Order">
                    <button type="submit" id="btnShipping" class="btn rounded" style="background-color: pink;">Submit</button>
                    </router-link>
                </form>
            </div>
        </div>
    </div>
   
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>