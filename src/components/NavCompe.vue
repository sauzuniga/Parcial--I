<template>    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">        
      <div class="container justify-content-evenly">          
        <router-link to="/" class="nav-link" aria-current="page" >Home</router-link>          
        <router-link to="/about" class="nav-link" >API</router-link>        
      </div>    
    </nav>

  </template>
  
  <script>
    export default {
      name : "NavCompe"
    }
  </script>
  
  <style >
.nav-link {
    color: white;
}

.nav-link :hover {
    background-color: rgba(0, 255, 255, 0.355);
    color: white;
}

    .a {
        color: white;
    }
  </style>
  