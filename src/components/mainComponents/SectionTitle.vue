<script>
export default {
    name: 'SectionTitle',
    props: {
        title: String,
    }
}
</script>

<template>
    <h3>{{ title }}</h3>
    <hr>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Necessitatibus quis eligendi ipsum maxime temporibus, cumque voluptas voluptatum quae libero iure.</p>
</template>

<style scoped>
h3 {
    text-align: center;
    font-size: 24px;
    font-weight: 400;
    margin-top: 150px;
    color: #1f1f1f;
}

hr {
    background-color: #FED03D;
    width: 200px;
    margin: 24px auto 36px;
}

p {
    width: 760px;
    text-align: center;
    color: #333333;
    margin: 0 auto;
}
</style>