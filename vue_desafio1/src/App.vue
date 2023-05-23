<template>
 <div>
  <Autos/>
  <!-- <Filtro/> -->

 </div>
</template>

<script>
 import Autos from './components/Autos.vue'
//  import Filtro from './components/Filtro.vue'


export default {
  name: 'App',
  components: {
    Autos
    // Filtro
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
