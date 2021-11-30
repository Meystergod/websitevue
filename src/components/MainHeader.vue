<template>
    <section class="header-fullscreen">
        <div class="header-body">
            <a href="#" class="header-logo">GM</a>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Experience</a></li>
                <li><a href="#">Contact</a></li>
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
        background-image: url("../assets/header.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        min-height: 100vh;
    }

    .header-body {
        display: flex;
        justify-content: space-between;
        font-size: 24px;
        padding: 20px;
    }
    .header-body ul {
        display: flex;
        list-style: none;
    }
    .header-body ul li {
        margin-left: 20px;
    }
    .header-body ul li a {
        text-decoration: none;
        color: white;
        padding: 6px 15px;
        border-radius: 20px;
    }
    .header-body ul li a:hover,
    .header-body ul li a:active {
        background: white;
        color: inherit;
    }

    .header-description {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .header-title {
        font-size: 60px;
        opacity: 0.5;
    }
</style>