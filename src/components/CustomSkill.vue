<template>
    <div class="skill">
        <div class="logo">{{title}}</div>
        <div class="info">{{info}}</div>
    </div>
</template>

<script>
export default {
    name: 'CustomSkill',
    props: {
        title: String,
        info: String
    }
}
</script>

<style scoped>
    .skill {
        display: flex;
        flex-direction: row;
        margin: auto;
        width: 75vw;
        margin-bottom: 30px;
    }
    .logo {
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 50%;
        border: 7px solid #7bdcfb;
        width: 10%;
        font-size: 25px;
        height: 7vw;
        opacity: 0.5;
    }
    .info {
        display: flex;
        align-items: center;
        justify-content: center;
        margin-left: 5%;
        width: 90%;
        font-size: 18px;
        line-height: 130%;
    }
</style>