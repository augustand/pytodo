<template>
  <div id="app">
    <img src="./assets/logo.png">
    <TodoList></TodoList>
  </div>
</template>

<script>
  import TodoList from './components/TodoList'

  export default {
    name: 'app',
    components: {
      TodoList
    }
  }
</script>
