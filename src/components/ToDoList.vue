<template>
    <div>
      <ul>
        <li v-for="task in tasks" :key="task.id">
          {{ task.title }}
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        tasks: [
          { id: 1, title: 'Task 1' },
          { id: 2, title: 'Task 2' },
          { id: 3, title: 'Task 3' },
        ]
      }
    }
  }
  </script>
  
  <style scoped>
  /* CSS-Stile spezifisch für diese Komponente */
  </style>
  