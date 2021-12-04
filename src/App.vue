<template>
  <div id="app">
    <div class="text-center">
      <img width="100" alt="Vue logo" src="./assets/logo.png">
    </div>
    <formQuestion />
  </div>
</template>

<script>
import formQuestion from './components/formQuestion.vue'

export default {
  name: 'App',
  components: {
    formQuestion
  }
}
</script>

<style>
.text-center{
  text-align: center;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
