<template>
    <div class="my-skills-header">
        <custom-header title="My skills"/>
    </div>
    <div class="main-container">
        <!-- <div class="back-arrow">
            <a href="" class="back-arrow-link">
                <img src="../assets/left-arrow.png">
            </a>
        </div> -->
        <custom-skill skill="C/C++" description="Programing on C++" percent="80" class="skill"/>
        <custom-skill skill="Python" description="Programing on Python" percent="70" class="skill"/>
        <custom-skill skill="Vue" description="Programing on Vue" percent="40" class="skill"/>
        <custom-skill skill="JS/TS" description="Programing on JavaScript and TypeScript" percent="50" class="skill"/>
        <!-- <div class="forward-arrow">
            <a href="" class="forward-arrow-link">
                <img src="../assets/right-arrow.png">
            </a>
        </div> -->
    </div>
</template>

<script>
import CustomHeader from './CustomHeader.vue'
import CustomSkill from './CustomSkill.vue'
export default {
    name: "MainSkill",
    components: {
        CustomHeader, CustomSkill
    }
}
</script>

<style scoped>
    .my-skills-header {
        text-align: center;
        padding-bottom: 40px;
    }
    .main-container {
        width: 75%;
        display: flex;
        flex-direction: row;
        margin: auto;
        padding-bottom: 40px;
        align-items: center;
    }
    .skill {
        text-align: center;
        flex: 9;
    }
    img {
        width: 50%;
        height: auto;
    }
    /* .back-arrow {
        text-align: center;
        flex: 1;
    }
    .forward-arrow {
        text-align: center;
        flex: 1;
    } */
</style>