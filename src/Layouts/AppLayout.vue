<template>

    <Navbar />

    <slot />

    <Footer/>

</template>

<script>
import Footer from './Footer.vue';
import Navbar from './Navbar.vue';






export default {
    name: "AppLayout",
    components: {
        Navbar,
        Footer

    }

}
</script>

<style></style>