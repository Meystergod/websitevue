<template>
    <section class="header-fullscreen">
        <div class="header-body">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Experience</a></li>
                <li><a href="#">Contact me</a></li>
                <li><a href="#">Blog</a></li>
            </ul>
        </div>
        <div class="header-description">
            <h class="header-title">Gleb Malakhov</h>
            <a href="" class="header-skip-link"></a>
        </div>
    </section>
</template>

<script>
export default {
    name: 'MainHeader'
}
</script>

<style scoped>
    .header-fullscreen {
        display: flex;
        flex-direction: column;
        background-image: url("../assets/header_1.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        min-height: 100vh;
    }

    .header-body {
        font-size: 24px;
        padding: 20px;
    }
    .header-body a {
        text-decoration: none;
        color: white;
        padding: 6px 15px;
        border-radius: 20px;
        opacity: 0.5;
    }
    .header-body ul {
        display: flex;
        list-style: none;
        justify-content: space-between;
    }

    .header-description {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .header-title {
        color: white;
        font-size: 60px;
        opacity: 0.5;
    }
</style>