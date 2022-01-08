<template>
    <div class="my-skills-header">
        <custom-header title="My skills"/>
    </div>
    <div class="main-container">
        <div class="back-arrow">
            s
        </div>
        <custom-skill class="skill"/>
        <custom-skill class="skill"/>
        <custom-skill class="skill"/>
        <div class="forward-arrow">
            s
        </div>
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
    .back-arrow {
        text-align: center;
        flex: 1;
    }
    .forward-arrow {
        text-align: center;
        flex: 1;
    }
</style>