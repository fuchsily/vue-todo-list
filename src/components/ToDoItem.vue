<template>
    <div>
      {{ task.title }}
      <button @click="deleteTask(task.id)">Delete</button>
    </div>
  </template>
  
  <script>
  export default {
    props: ['task'],
    methods: {
      deleteTask(id) {
        // Hier kannst du die Löschlogik implementieren
      }
    }
  }
  </script>
  