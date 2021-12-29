<template>
    <div class="about-me">
        <custom-header title="About me"/>
    </div>
    <div class="avatar">
        <img src="../assets/avatar.jpg">
    </div>
    <div class="information">
        <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
            Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software
            like Aldus PageMaker including versions of Lorem Ipsum.
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
            Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software
            like Aldus PageMaker including versions of Lorem Ipsum.
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
            industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and
            scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
            Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software
            like Aldus PageMaker including versions of Lorem Ipsum.
        </p>
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
        padding-top: 40px;
        padding-bottom: 40px;
    }
    .avatar {
        text-align: center;        
    }
    .information {
        margin: auto;
        padding-top: 40px;
        padding-bottom: 40px;
        width: 75%;
        font-size: 18px;
    }
    img {
        width: 25%;
        height: auto;
        border-radius: 20%;
    }
    p {
        text-align: center;
        font-size: 22px;
    }
</style>