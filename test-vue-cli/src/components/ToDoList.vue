<template>
    <ul>
        <!-- left todo is taken from the array below -->
        <!-- right todo is taken from data in App.vue -->
        <!-- todo in {{}} is taken from the first argument in for () -->
        <!-- index in key is taken from the second argument in for () -->
        <li :for="(todo, index) in todo" :key="index">{{todo}}</li>
    </ul>
</template>

<script>
export default {
    props: ['todo'] //taken from an attr of ToDoList in App.vue (before the sign = )
}
</script>