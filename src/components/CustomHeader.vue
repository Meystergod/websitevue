<template>
    <h class="header">{{title}}</h>
</template>

<script>
export default {
    name: 'CustomHeader',
    props: {
        title: String
    }
}
</script>

<style scoped>
    .header {
        font-size: 60px;
        opacity: 0.5;
    }
</style>