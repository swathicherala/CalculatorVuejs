<template>
  <div id="app">
    <CalculatorPage/>
  </div>
</template>

<script>
import CalculatorPage from './components/CalculatorPage.vue'

export default {
  name: 'App',
  components: {
    CalculatorPage
  }
}
</script>

<style>
body{
  background: #31475e;
}
</style>
