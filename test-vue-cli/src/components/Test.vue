<template>
    <div class="test">
        <h1>{{message}}</h1>
        <p>
            Some text should be put here,
            but later
        </p>
    </div>
</template>

<script>
export default {
    name: 'Test',
    props: {
        message: String
    }
}
</script>

<style scoped>
    .test{
        max-width: 300px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    h1{
        color: skyblue;
        font-size: 24px;
        letter-spacing: 5px;
    }
    p{
        color: chocolate;
        font-size: 18px;
    }
</style>