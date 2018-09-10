<template>
    <div id="app">
        <div>666</div>
        <icon name="info" scale="20"></icon>
    </div>
</template>

<script>
import Icon from './Icon.vue';
    export default {
        name: 'app',
        components: {Icon}
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
