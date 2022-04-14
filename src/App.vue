<template>
  <div id="app">
    <Expense />
  </div>
</template>

<script>
// import Expense
import Expense from './components/Expense.vue'

export default {
  name: 'App',
  components: {
    Expense,
  }
}
</script>

// <style >
/* // @import "~@/assets/scss/vendors/bootstrap-vue/index"; */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
