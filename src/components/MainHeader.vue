<template>
    <section class="header-fullscreen">
        <div class="header-body">
            <h class="header-title">Welcome on my page</h>
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
        background-image: url("../assets/header.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        min-height: 100vh;
    }
    .header-body {
        display: flex;
        flex-direction: column;
        justify-content: center;
        color: white;
        margin: 0px auto;
        text-align: center;
        width: 100%;
    }
    .header-title {
        font-size: 60px;
        opacity: 0.5;
    }
</style>