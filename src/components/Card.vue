<template>
    <div class="bg-white p-4 border-radius-20" id="rounded">
        <a href="#" @click.prevent="$emit('changePictures', cardImage)" class="chairs">
            <img class="border-radius-25" id="rounded" 
            :src="require('@/assets/img/' + cardImage + '.png')" alt="chairs">
        </a>
        <p class="font-weight-bold mt-3 my-0">{{ cardTitle }}</p>
        <p>IDR {{ cardPrice }}</p>
    </div>
</template>

<script>
export default {
    name : 'CardComponent',
    props : [
        "cardImage", "cardPrice", "cardTitle"
    ]
}
</script>

<style scoped>
#rounded{
    border-radius: 25px;
<<<<<<< HEAD
    
        
=======
    background-color: aqua;
>>>>>>> 6f757d8c84c36f95e6f890d98257993f30893d51
}


</style>