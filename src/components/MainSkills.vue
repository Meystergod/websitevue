<template>
    <div class="my-skills-header">
        <custom-header title="My skills"/>
    </div>
    <div class="skills">
        <custom-skill title="C++" info="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged."/>
        <custom-skill title="Vue" info="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged."/>
        <custom-skill title="Python" info="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged."/>
        <custom-skill title="OpenCV" info="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged."/>
        <custom-skill title="FFmpeg" info="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged."/>
    </div>
</template>

<script>
import CustomHeader from './CustomHeader.vue'
import CustomSkill from './CustomSkill.vue'
export default {
    name: "MainSkills",
    components: {
        CustomHeader,
        CustomSkill
    }
}
</script>

<style scoped>
    .my-skills-header {
        text-align: center;
        padding-bottom: 40px;
    }
    .skills {
        display: flex;
        flex-direction: column;
        
    }
</style>