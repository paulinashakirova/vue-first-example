<template>
  <div>
    <h1>{{message}}</h1>
    <input type="text" v-model='message'/>
    <button type="submit" @click="counter++">Add One</button>
    <button type="submit" @click="counter--">Delete One</button>
    <p>{{counter}}</p>
  </div>
</template>

<script>
export default {
data() {
  return {
    message: 'Barcelona',
    counter: 0
  }
},
methods: {
  
}
}
</script>

<style>

</style>

