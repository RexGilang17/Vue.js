<template >
    <nav class="navbar navbar-expand-lg  " id="nav">
        <div class="d-flex px-5">
        <router-link class="nav-link active" style="text-decoration:none ; color: black;" aria-current="page" to="/Detail">Home</router-link>
        <router-link class="nav-link active" style="text-decoration:none ; color: black;" aria-current="page" to="/Detail">Detail</router-link>
        <link rel="apple-touch-icon" href="/latihanBs.html">
        </div>
    </nav>
</template>
<script>
export default {
    name: 'BreadcrumView',
}
</script>

<style scoped>
    #nav{
        background-color: #EEF1FF;
    }


</style>

