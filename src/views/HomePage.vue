<template>
    <div>
      <h1>Todo List</h1>
      <TodoList />
    </div>
  </template>
  
  <script>
  import TodoList from '@/components/ToDoList.vue';
  
  export default {
    components: {
      TodoList
    }
  }
  </script>
  