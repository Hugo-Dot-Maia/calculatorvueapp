<template>
  <div id="app">
    <calculator></calculator>
  </div>
</template>

<script>
import Calculator from './components/Calculadora.vue'
export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
body {
  background: #31475e !important;
}
</style>