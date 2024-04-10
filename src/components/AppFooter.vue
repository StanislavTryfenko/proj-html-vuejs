<script>
import FooterJumbotron from './footerComponents/FooterJumbotron.vue'
import FooterMain from './footerComponents/FooterMain.vue'
import FooterFooter from './footerComponents/FooterFooter.vue'

export default {
    name:'AppFooter',
    components: {
        FooterJumbotron,
        FooterMain,
        FooterFooter,
    }
}
</script>

<template>
    
    <FooterJumbotron />
    <FooterMain />
    <FooterFooter />


</template>

<script scoped>

</script>