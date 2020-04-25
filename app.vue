<template>
    <div id="app">
        <progress-circle></progress-circle>
    </div>
</template>
<script>
import progressCircle from './components/progress-circle.vue'
export default {
    name: 'app',
    components: { progressCircle }
}
</script>
<style lang="less">
    #app {
        font-family: "Avenir", Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>