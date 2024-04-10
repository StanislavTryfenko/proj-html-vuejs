<script>
import AppJumbotron from './mainComponents/AppJumbotron.vue';
import SectionTitle from './mainComponents/SectionTitle.vue';
import SpecialistsContent from './mainComponents/SpecialistsContent.vue';
import AvadaStats from './mainComponents/AvadaStats.vue';

export default {
    name: 'AppMain',
    components: {
        AppJumbotron,
        SectionTitle,
        SpecialistsContent,
        AvadaStats,
    },

}
</script>

<template>

    <AppJumbotron />

    <SectionTitle title="Specialists In Modern Constuction" />

    <SpecialistsContent />

    <AvadaStats />

    <SectionTitle title="Explore Recent Work" />

    <SectionTitle title="Our Core Values" />

    <SectionTitle title="Latest News" />

    <SectionTitle title="Trusted Partners" />

    

</template>

<style scoped></style>