<template>
<!-- id the div -->

<div id="app">
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- 5. -->
  <!-- using the file name that we declared -->
    <MyComponent/>
  
  <!-- crate a component
        export it in export defauld
         then import in the component youre gonna be using it in
         then declare in the component
         then use it 
         
         declare, register, use -->
</div>
  
</template>


<script>
// 3.
import MyComponent from '@/components/MyComponent.vue';

export default {
  name: 'App',
// 4. register your component
  components: {
    // register your component
    MyComponent
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
