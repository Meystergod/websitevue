<template>
    <div class="skill-container">
        <div class="progress-circle">
            <div class="outer-contour">
                <div class="inner-contour">
                    <div class="percent-number">{{percent}}<span>%</span></div>
                </div>
            </div>
            <svg xmlns="http://www.w3.org/2000/svg" version="1.1" width="160px" height="160px">
                <defs>
                    <linearGradient id="GradientColor">
                        <stop offset="0%" stop-color="#e91e63" />
                        <stop offset="100%" stop-color="#673ab7" />
                    </linearGradient>
                </defs>
                <circle cx="80" cy="80" r="70" stroke-linecap="round" :style="style"/>
            </svg>
        </div>
        <div class="skill-name">
            {{skill}}
        </div>
        <div class="skill-description">
            {{description}}
        </div>
    </div>
</template>

<script>
export default {
    name: "CustomSkill",
    props: {
        skill: String,
        description: String,
        percent: String
    },
    computed: {
        style () {
            return 'stroke-dashoffset: ' + 'calc(440 - (440 * ' + this.percent + ') / 100)'
        }
    }
}
</script>

<style scoped>
    .skill-container {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .outer-contour {
        width: 160px;
        height: 160px;
        border-radius: 50%;
        box-shadow: 6px 6px 10px -1px rgba(251, 176, 255, 0.7),
                    -6px -6px 10px -1px rgba(255, 255, 255, 0.7);
        padding: 20px;
    }
    .inner-contour {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 120px;
        height: 120px;
        border-radius: 50%;
        box-shadow: inset 4px 4px 6px -1px rgba(251, 176, 255, 0.7),
                    inset -4px -4px 6px -1px rgba(255, 255, 255, 0.7),
                    -0.5px -0.5px 0px rgba(255, 255, 255, 1),
                    0.5px 0.5px 0px rgba(255, 255, 255, 0.15),
                    0px 12px 10px -10px rgba(0, 0, 0, 0.05);
    }
    .progress-circle {
        position: relative;
        padding-bottom: 3%;
    }
    .percent-number {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    circle {
        fill: none;
        stroke: url(#GradientColor);
        stroke-width: 20px;
        stroke-dasharray: 440;
    }
    svg {
        position: absolute;
        top: 0;
        left: 0;
    }
</style>