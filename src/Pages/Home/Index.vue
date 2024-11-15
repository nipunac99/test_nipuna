<template>
    <AppLayout>
        <HeroSectionVue />
        <AboutUsVue />
        <LatestNews />
        <TestimonialsVue />
        <ContactUsVue />



    </AppLayout>

</template>

<script>
import AppLayout from '@/Layouts/Applayout.vue';
import HeroSectionVue from './Partials/HeroSection.vue';
import AboutUsVue from './Partials/AboutUs.vue';
import LatestNews from './Partials/LatestNews.vue';
import TestimonialsVue from './Partials/Testimonials.vue';
import ContactUsVue from './Partials/ContactUs.vue';




export default {
    components: {
        AppLayout,
        HeroSectionVue,
        AboutUsVue,
        LatestNews,
        TestimonialsVue,
        ContactUsVue,



    }

}
</script>

<style></style>