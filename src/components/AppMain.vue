<script>
import AppJumbotron from './mainComponents/AppJumbotron.vue'
import SectionTitle from './mainComponents/SectionTitle.vue';   

export default {
  name: 'AppMain',
  components: {
    AppJumbotron,
    SectionTitle,
  },
  
}
</script>

<template>

    <AppJumbotron />

    <SectionTitle title="Specialists In Modern Constuction"/>

    <SectionTitle title="Explore Recent Work"/>

    <SectionTitle title="Our Core Values"/>

    <SectionTitle title="Latest News"/>

    <SectionTitle title="Trusted Partners"/>


</template>

<style scoped>

</style>