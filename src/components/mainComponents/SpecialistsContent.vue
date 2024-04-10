<script>
export default {
    name: 'SpecialistsContent',
    data() {
        return {
            cards:
                [{ i: 'fa-regular fa-building', title: 'Buildings' },
                { i: 'fa-solid fa-arrows-rotate', title: 'Renovate' },
                { i: 'fa-solid fa-house-chimney', title: 'Construct' },
                { i: 'fa-solid fa-truck', title: 'Exclusive' }]
        };
    }
}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="card" v-for="(card, index) in this.cards" :key="index">
                <div class="circle">
                    <i :class="card.i + ' fa-xl'"></i>
                </div>
                <h3>{{ card.title }}</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, incidunt.</p>
            </div>
        </div>
    </div>

</template>

<style scoped>
.container {
    width: 1544px;
    margin: 133px auto 0;

    .row {
        display: flex;
        justify-content: space-between;

        .card {
            width: 300px;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: #333333;
            
            .circle {
                width: 75px;
                aspect-ratio: 1;
                border-radius: 50%;
                border: 1px solid #333333;
                display: flex;
                justify-content: center;
                align-items: center;

                i{
                    color: #333333;

                }
            }

            h3{
                margin: 20px 0;
                font-size: 24px;
                font-weight: 400;
            }

            p {
                text-align: center;
                font-size: 12px;
                color: #333333;
            }
        }
    }
}
</style>