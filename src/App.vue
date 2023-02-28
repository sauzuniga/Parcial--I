
<template>
  <NavCompe/>
  <RouterView />
</template>

<script>
import NavCompe from './components/NavCompe.vue';
  export default {  
    name: "App", 
    components: {  
       NavCompe  
    }
  }
</script>

<style >
 #app {
  color: black;
 }
</style>
