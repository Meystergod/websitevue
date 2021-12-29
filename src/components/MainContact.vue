<template>
    <div class="contact-header">
        <custom-header title="Contact me"/>
    </div>
    <div class="icons">
        <a href="https://vk.com/id142476579" class="link-icon-vk">
            <img src="../assets/vk.png" class="icon-vk">
        </a>
        <a href="#" class="link-icon-tg">
            <img src="../assets/telegram.png" class="icon-tg">
        </a>
        <a href="#" class="link-icon-gmail">
            <img src="../assets/gmail.png" class="icon-gmail">
        </a>
        <a href="#" class="link-icon-linkedin">
            <img src="../assets/linkedin.png" class="icon-linkedin">
        </a>
    </div>
</template>

<script>
import CustomHeader from './CustomHeader.vue'
export default {
    name: "MainContact",
    components: {
        CustomHeader
    }
}
</script>

<style scoped>
    .contact-header {
        text-align: center;
        padding-top: 40px;
        padding-bottom: 40px;
    }
    .icons {
        width: 75vw;
        display: flex;
        justify-content: center;
        margin: auto;
    }
    img {
        width: 50%;
    }
    a {
        text-align: center;
    }
</style>