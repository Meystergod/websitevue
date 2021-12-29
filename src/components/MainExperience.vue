<template>
    <div class="my-exp-header">
        <custom-header title="My experience"/>
    </div>
    <div class="exp-items">
        <custom-experience company="Hybrik" date="00.00.0000" info="Information about my experience in the Hybrik"/>
        <custom-experience company="Hybrik" date="00.00.0000" info="Information about my experience in the Hybrik"/>
        <custom-experience company="Hybrik" date="00.00.0000" info="Information about my experience in the Hybrik"/>
    </div>
</template>

<script>
import CustomExperience from './CustomExperience.vue'
import CustomHeader from './CustomHeader.vue'
export default {
    name: "MainExperience",
    components: {
        CustomHeader, CustomExperience
    }
}
</script>

<style scoped>
    .my-exp-header {
        text-align: center;
        padding-bottom: 40px;
    }
    .exp-items {
        width: 75vw;
        margin: auto;
        border-left: 3px solid #7bcdfb;
        padding-left: 20px;
    }
</style>