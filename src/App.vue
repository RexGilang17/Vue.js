<template>
  <div id="app" >
    <img alt="Vue logo" src="./assets/r.png" style="width: 250px; ">
    <h1>{{ text1 }}</h1>
    <h2>THE {{ input[0] }}</h2>
    <h2>THE {{ input[1] + " " + input[2]}}</h2>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <button 
      v-on:click="gantiNama()">
      Ganti Nama</button>

    <h2>{{ totalBelanja }}</h2>
    <button v-on:click="gantiQuantity()">Ganti Qty</button>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data: function(){
    return{
      text1 : "WELCOME TO WAKANDA",
      input : ["Black Panther", "White Panther", "Red Panther"],
      quantity : 5
    }
  },
  methods: {
    gantiNama : function(){
      if(this.text1 == "Kodehive"){
        this.text1 = "Adhan"
      }else{
        this.text1 = "Kodehive"
      }
    },
    gantiQuantity : function(){
      this.quantity++
    }
  },
  computed: {
    totalBelanja : function(){
      return this.quantity * 10000
    }
  },

  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>