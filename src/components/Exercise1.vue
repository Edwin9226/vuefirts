<script setup lang="ts">
const color= 'red';
const title=' Interpolation can also handle conditional logic.';
const isUpperCase=false;
</script>

<template>
    <div>
        <h1>My first component!</h1>
        <span> {{ color.toUpperCase() }}</span>
        <p>{{ isUpperCase ? title.toUpperCase(): title}}</p>
    </div>
    
</template>

<style>
h1 {
    font-family: 'Avenir', Helvetica, Arial,
        sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>

