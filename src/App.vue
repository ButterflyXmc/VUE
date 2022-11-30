<template>
<!-- id the div -->
<!-- can ony use app as an ID because vue only allows this ID -->
<div id="app">
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- 5. -->
  <!-- (3) using the file name that we declared -->
    <MyComponent/>
    
</div>
  
</template>

 <!-- DECLARE, REGISTER, USE -->

<script>
// 3. (1) Declaring the component
import MyComponent from '@/components/MyComponent.vue';

export default {
  name: 'App',
// 4. (2) Register your component
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
