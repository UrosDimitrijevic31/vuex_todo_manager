<template>
  <div id="app">
    <div class="container">
      <Addtodo />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos.vue'
import Addtodo from './components/Addtodo.vue'

export default {
  name: 'App',
  components: {
    Todos,
    Addtodo
  }
}
</script>

<style>
  body {
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    line-height: 1.6;
    background: #e8f7f0;
  }

  .container {
    max-width: 1100px;
    margin: auto;
    /* overflow use for scroling */
    overflow: auto; 
    padding: 0 2rem;
  }
</style>