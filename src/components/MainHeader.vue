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
        <div class="header-information">
            <div class="header-title-container">
                <h class="header-title">
                    Gleb Malakhov
                </h>
            </div>
            <div class="header-description-container">
                <p class="header-description-1">
                    C/C++ developer over 3 years
                </p>
            </div>
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
        background-image: linear-gradient(rgba(0,0,0,.530),rgba(0,0,0,.500)), url("../assets/header_1.jpg");
        background-attachment: fixed;
        background-size: cover;
        background-repeat: no-repeat;
        min-height: 100vh;
    }

    .header-body {
        font-size: 16px;
        padding: 20px;
    }
    .header-body a {
        text-decoration: none;
        color: white;
        padding: 6px 15px;
        border-radius: 20px;
    }
    .header-body ul {
        display: flex;
        list-style: none;
        justify-content: space-between;
    }

    .header-information {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .header-title {
        color: white;
        font-size: 48px;
    }
    .header-description-container {
        color: white;
        font-size: 20px;
        text-align: center;
    }
</style>