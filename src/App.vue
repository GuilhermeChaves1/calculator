<template>
    <div id="app">
        <h1>Calculadora</h1>
        <Calculator />
    </div>
</template>

<script>
import Calculator from './main/Calculator.vue';
export default {
    components: { Calculator },};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@100&display=swap");

* {
    font-family: "Roboto Mono", monospace;
}

body {
    margin: 0;
}
#app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
    background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>
