<template>
  <div>
    <h1>{{message}}</h1>
    <input type="text" v-model='message'/>
    <button type="submit" @click="addOne">Add One</button>
    <button type="submit" @click="deleteOne">Delete One</button>
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
  addOne() {
    this.counter++
  },
  deleteOne() {
    this.counter--
  }
}
}
</script>

<style>

</style>

