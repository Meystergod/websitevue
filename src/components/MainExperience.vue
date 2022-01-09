<template>
    <div class="my-exp-header">
        <custom-header title="My experience"/>
    </div>
    <div class="exp-timeline">
        <ul>
            <li>
                <div class="date">
                    <h4>September 2018 — present days</h4>
                </div>
                <div class="company">
                    <h3>Study</h3>
                </div>
                <div class="info">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate nesciunt eum reiciendis necessitatibus cum! Voluptatum molestiae pariatur enim harum sunt, consectetur soluta necessitatibus, est, id reprehenderit ipsam! Quas, dolore totam?</p>
                </div>
            </li>
            <li>
                <div class="date">
                    <h4>September 2020 — August 2021</h4>
                </div>
                <div class="company">
                    <h3>Freelance</h3>
                </div>
                <div class="info">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate nesciunt eum reiciendis necessitatibus cum! Voluptatum molestiae pariatur enim harum sunt, consectetur soluta necessitatibus, est, id reprehenderit ipsam! Quas, dolore totam?</p>
                </div>
            </li>
            <li>
                <div class="date">
                    <h4>September 2021 — present days</h4>
                </div>
                <div class="company">
                    <h3>Hybrik</h3>
                </div>
                <div class="info">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate nesciunt eum reiciendis necessitatibus cum! Voluptatum molestiae pariatur enim harum sunt, consectetur soluta necessitatibus, est, id reprehenderit ipsam! Quas, dolore totam?</p>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
import CustomHeader from './CustomHeader.vue'
export default {
    name: "MainExperience",
    components: {
        CustomHeader
    }
}
</script>

<style scoped>
    .my-exp-header {
        text-align: center;
        padding-bottom: 40px;
    }
    .exp-timeline {
        width: 75%;
        display: flex;
        margin: 50px auto;
        position: relative;
    }
    .exp-timeline::before {
        content: '';
        position: absolute;
        left: 50%;
        width: 2px;
        height: 100%;
        background: #c5c5c5;
    }
    .exp-timeline ul {
        margin: 0;
        padding: 0;
    }
    .exp-timeline ul li {
        list-style: none;
        position: relative;
        width: 50%;
        padding: 20px 40px;
        padding-bottom: 80px;
        box-sizing: border-box;
    }
    .exp-timeline ul li:nth-child(odd)
    {
        float: left;
        text-align: right;
        clear: both;
    }
    .exp-timeline ul li:nth-child(even)
    {
        float: right;
        text-align: left;
        clear: both;
    }
    .exp-timeline ul li:nth-child(odd)::before {
        content: '';
        top: 26px;
        right: -6px;
        position: absolute;
        width: 10px;
        height: 10px;
        background: #abc4ff;
        border-radius: 50%;
        box-shadow: 0 0 0 3px rgba(0, 155, 255, 0.2);
    }
    .exp-timeline ul li:nth-child(even)::before {
        content: '';
        top: 26px;
        left: -4px;
        position: absolute;
        width: 10px;
        height: 10px;
        background: #abc4ff;
        border-radius: 50%;
        box-shadow: 0 0 0 3px rgba(0, 155, 255, 0.2);
    }
    .exp-timeline ul li:nth-child(odd) .date {
        position: absolute;
        padding: 8px 16px;
        background: #abc4ff;
        box-shadow: 0 0 0 3px rgba(0, 155, 255, 0.2);
        color: white;
        border-radius: 20px;
        right: -295px;
    }
    .exp-timeline ul li:nth-child(even) .date {
        position: absolute;
        padding: 8px 16px;
        background: #abc4ff;
        box-shadow: 0 0 0 3px rgba(0, 155, 255, 0.2);
        color: white;
        border-radius: 20px;
        left: -290px;
    }
    .date {
        top: 14px;
    }
    .company {
        padding-bottom: 3%;
    }
</style>