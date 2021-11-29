<template>
    <div class="about-me">
        <custom-header title="About me"/>
    </div>
</template>

<script>
import CustomHeader from './CustomHeader.vue'
export default {
    name: 'MainAbout',
    components: {
        CustomHeader
    }
}
</script>

<style scoped>
    .about-me {
        text-align: center;
    }
</style>