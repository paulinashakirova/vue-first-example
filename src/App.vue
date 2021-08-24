<template>
  <div id='app'>
    <!-- 3. Use the component in the template -->
    <HelloWorld />
  </div>

</template>

<script>
//1. import the component
import HelloWorld from './components/HelloWorld';
export default {
  //2. Declare (register) the component
  components: {
    HelloWorld
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