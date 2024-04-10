<script>
export default {
    name: 'AvadaStats',
    data() {
        return {
            cards:
                [{ i: 'fa-solid fa-suitcase', number: '3534', string: 'PLANNING APPLICATIONS' },
                { i: 'fa-regular fa-building', number: '896', string: 'COMPLETED PROJECTS' },
                { i: 'fa-solid fa-users', number: '172', string: 'TRAINED PROFESSIONALS' },
                { i: 'fa-solid fa-globe', number: '19', string: 'INTERNATIONAL OFFICES' }]
        };
    }
}
</script>

<template>

    <div class="container">
        <div class="custom-shape-divider-top-1712745500">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120"
                preserveAspectRatio="none">
                <path d="M0,0V7.23C0,65.52,268.63,112.77,600,112.77S1200,65.52,1200,7.23V0Z" class="shape-fill"></path>
            </svg>
        </div>

        <div class="row">
            <div class="card" v-for="(card, index) in cards" :key="index">
                <i :class="card.i + ' fa-3x'"></i>
                <div class="number">{{ card.number }}</div>
                <div class="string">{{ card.string }}</div>
            </div>
        </div>

        <div class="custom-shape-divider-bottom-1712745446">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120"
                preserveAspectRatio="none">
                <path d="M0,0V7.23C0,65.52,268.63,112.77,600,112.77S1200,65.52,1200,7.23V0Z" class="shape-fill"></path>
            </svg>
        </div>
    </div>
</template>

<style scoped>
.container {
    height: 580px;
    background-color: blueviolet;
    position: relative;
    display: flex;
    align-items: center;

    .row {
        width: 1664px;
        display: flex;
        justify-content: space-evenly;

        .card {
            text-align: center;

            i {
                color: #FED03D;
            }

            .number {
                color: #FED03D;
                font-size: 4em;
            }

            .string {
                color: #ffffff;
            }
        }
    }
}



.custom-shape-divider-top-1712745500 {
    position: absolute;
    top: -1px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.custom-shape-divider-top-1712745500 svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 80px;
}

.custom-shape-divider-top-1712745500 .shape-fill {
    fill: #F5F5F5;
}

.custom-shape-divider-bottom-1712745446 {
    position: absolute;
    bottom: -1px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    transform: rotate(180deg);
}

.custom-shape-divider-bottom-1712745446 svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 80px;
}

.custom-shape-divider-bottom-1712745446 .shape-fill {
    fill: #F5F5F5;
}
</style>