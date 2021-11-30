<template>
    <div class="app">
        <main-header/>
        <main-about/>
    </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainAbout from './components/MainAbout.vue'
export default {
    name: 'App',
    components: {
        MainHeader, MainAbout
    }
}
</script>

<style>
    *,
    *:before,
    *:after {
        padding: 0;
        margin: 0;
        border: 0;
        box-sizing: border-box;
    }
</style>