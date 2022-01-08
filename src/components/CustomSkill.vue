<template>
    <div class="skill-container">
        <div class="progress-circle">
            HHH
        </div>
        <div class="skill-name">
            AAA
        </div>
        <div class="skill-description">
            BBB
        </div>
    </div>
</template>

<script>
export default {
    name: "CustomSkill",
    props: {
        skill: String,
        description: String,
        percent: String
    }
}
</script>

<style scoped>
    .skill-container {
        display: flex;
        flex-direction: column;
    }
</style>