<template>
  <div id="app">
    <h5>Input feild which takes string and reprint it in uppercase</h5>
    <input type="text" v-model="message" />
    <h4>{{ message | uppercase }}</h4>
  </div>
</template>

<script>

export default {
  name: "App",
  data(){
    return{
      message: "aviram"
    }
  }
};
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
