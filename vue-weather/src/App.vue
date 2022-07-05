<template>
  <div id="app">
   <main> 
     <div class="search-box"> 
       <input type="text" name="" id="" class="search-bar" placeholder="Search...">
     </div>
   </main> 
  </div>
</template>

<script>


export default {
  name: 'App',
  data () {
    return {
      api_key: "83e2cc575564a750eaa16ed9e62a97f1"
    }
  }
 
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main {
  min-height: 100vh;
}

</style>
