<template>
  <div class="container-fluid mt-3">
    

    <Formulario/>
     <!--  
      <Navbar />
      <router-view></router-view>
 -->
  
  </div>
</template>

<script>



import Formulario from './components/Formulario.vue'

/* import Navbar from './components/Navbar.vue' */

export default {
  name: 'App',
  components: {
   Formulario,
   /*  Navbar */
  }
}
</script>

<style>
  h1 {
   
  }
  .jumbotron{
   
  }

</style>
