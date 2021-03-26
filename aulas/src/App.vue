<template>
  <div id="app">

  <h1> {{mesage}}  </h1>
  <input type="text" name="" id="name" v-model="username">

  </div>
 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  data: ({
    return: {
      mesage:"teu pai usa calcinha",
      username:""
    }



  })
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: black;
  margin-top: 60px;
}
</style>
