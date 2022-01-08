<template>
    <div class="about-me">
        <custom-header title="About me"/>
    </div>
    <div class="information">
        <div class="information-text">
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
        <div class="information-image">
            <img src="../assets/avatar.jpg" class="avatar">
        </div>
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
    .information {
        display: flex;
        align-items: center;
        margin: auto;
        padding-bottom: 40px;
        width: 75%;
    }
    .information-text {
        width: 80%;
        padding-right: 5%;
    }
    .information-image {
        width: 20%;
    }
    .avatar {
        width: 100%;
        height: 15vw;
        border-radius: 50%;
    }
    p {
        text-align: left;
        font-size: 18px;
        line-height: 130%;
    }
</style>