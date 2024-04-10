<script>
export default {
    name: 'RecentWork',
}
</script>

<template>

    <div>
        <img src="../../../public/img/recent_work_1.jpg">
        <img src="../../../public/img/recent_work_2.jpg">
        <img src="../../../public/img/recent_work_3.jpg">
    </div>

    <h4>VIEW ALL PROJECTS</h4>

</template>

<style scoped>
div{
    width: 1100px;
    margin: 50px auto;
    display: flex;
    justify-content: space-between;

    img{
        aspect-ratio: 1;
        width: 350px;
    }
}

h4{
    text-align: center;
    font-weight: 400;
    color: #333333;
}
</style>