<template>
    <div class="app">
        <main-header/>
        <main-about/>
        <main-skills/>
        <main-experience/>
        <main-contact/>
    </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainAbout from './components/MainAbout.vue'
import MainSkills from './components/MainSkills.vue'
import MainExperience from './components/MainExperience.vue'
import MainContact from './components/MainContact.vue'
export default {
    name: 'App',
    components: {
        MainHeader, MainAbout, MainSkills, MainExperience, MainContact
    }
}
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');
    *,
    *:before,
    *:after {
        padding: 0;
        margin: 0;
        border: 0;
        box-sizing: border-box;
        font-family: 'Roboto';
    }
</style>