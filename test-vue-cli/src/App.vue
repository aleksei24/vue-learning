<template>
  <div id="new App">
    <ToDoList />
  </div>
</template>

<script>
import ToDoList from './components/ToDoList.vue'
export default {
  name: 'new App',
  data(){ // must be a function
    return {
      todo: ['Repair']
    }
  },
  components: {
    ToDoList
  }

  }
</script>

<style>

</style>
