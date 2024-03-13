<template>
  <div id ="app">
    <Todo-List></Todo-List>
  </div>
</template>

<script>
import TodoList from './components/TodoList.vue'

export default {
  name: 'App',
  components: {
    TodoList
  }
}
</script>


