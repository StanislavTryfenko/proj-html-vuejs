<script>
import AppJumbotron from './mainComponents/AppJumbotron.vue';
import SectionTitle from './mainComponents/SectionTitle.vue';
import SpecialistsContent from './mainComponents/SpecialistsContent.vue';
import AvadaStats from './mainComponents/AvadaStats.vue';
import RecentWorks from './mainComponents/RecentWorks.vue';

export default {
    name: 'AppMain',
    components: {
        AppJumbotron,
        SectionTitle,
        SpecialistsContent,
        AvadaStats,
        RecentWorks,
    },

}
</script>

<template>

    <AppJumbotron />

    <SectionTitle title="Specialists In Modern Constuction" />

    <SpecialistsContent />

    <AvadaStats />

    <SectionTitle title="Explore Recent Work" />

    <RecentWorks />

    <SectionTitle title="Our Core Values" />

    <SectionTitle title="Latest News" />

    <SectionTitle title="Trusted Partners" />

    

</template>

<style scoped></style>