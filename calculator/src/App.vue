<template>
  <div id="app">
    <h1>Calculator</h1>
   <Calculator/>
  </div>
</template>

<script>
import Calculator from './main/Calculator.vue'

export default {
  components: {Calculator}
}
</script>

<style>
@font-face {
  font-family: 'RobotoMono', monospace;
  src: url("./fonts/RobotoMono-Thin.ttf");
}
</style>