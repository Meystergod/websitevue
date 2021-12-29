<template>
    <div class="exp-item">
        <p class="text-company">{{company}}</p>
        <p class="text-date">{{date}}</p>
        <div class="text-info">{{info}}</div>
    </div>
</template>

<script>
export default {
    name: "CustomExperience",
    props: {
        company: String,
        date: String,
        info: String
    }
}
</script>

<style scoped>
    .text-company {
        font-size: 40px;
    }
    .text-date {
        font-size: 30px;
    }
    .text-info {
        font-size: 22px;
    }

</style>