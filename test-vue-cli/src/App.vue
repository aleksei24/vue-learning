<template>
  <div id="new App">
    <!-- with : an array -->
    <!-- without : a string -->
    <!-- attr todo is taken from data below -->
    <ToDoList :todo="todo"/>
  </div>
</template>

<script>
import ToDoList from './components/ToDoList.vue'
export default { //default is a selected one
  name: 'new App',
  data(){ // must be a function
    return {
      todo: ['Repair']
    }
  },
  components: {
    ToDoList // should be the same name as in import
  }

  }
</script>

<style>

</style>
