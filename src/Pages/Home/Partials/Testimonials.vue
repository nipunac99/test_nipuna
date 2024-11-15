<template>
    <div class="container">
        <Maintopic text="Testimonials" />
        <div class="testimonials-main">
            <div class="testimonial mySwiper">
                <div class="testi-content swiper-wrapper">
                    <div class="slide swiper-slide">

                        <img src="/Icons/quote-right-Icon.svg" alt="" class="quote-icon-top">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam,
                            saepe provident dolorem a quaerat quo error facere nihil deleniti
                            eligendi ipsum adipisci, fugit, architecto amet asperiores
                            doloremque deserunt eum nemo.
                        </p>
                        <!-- <i class="bx bxs-quote-alt-left quote-icon"></i> -->
                        <img src="/Icons/quote-left-Icon.png" alt="" class="quote-icon-bottom">
                        <div class="details">
                            <span class="name">- Lorem ipsum dolor </span>
                            <span class="job">Labore et dolore</span>
                        </div>
                    </div>
                    <div class="slide swiper-slide">

                        <img src="/Icons/quote-right-Icon.svg" alt="" class="quote-icon-top">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam,
                            saepe provident dolorem a quaerat quo error facere nihil deleniti
                            eligendi ipsum adipisci, fugit, architecto amet asperiores
                            doloremque deserunt eum nemo.
                        </p>
                        <!-- <i class="bx bxs-quote-alt-left quote-icon"></i> -->
                        <img src="/Icons/quote-left-Icon.png" alt="" class="quote-icon-bottom">
                        <div class="details">
                            <span class="name">- Lorem ipsum dolor </span>
                            <span class="job">Labore et dolore</span>
                        </div>
                    </div>
                    <div class="slide swiper-slide">

                        <img src="/Icons/quote-right-Icon.svg" alt="" class="quote-icon-top">
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam,
                            saepe provident dolorem a quaerat quo error facere nihil deleniti
                            eligendi ipsum adipisci, fugit, architecto amet asperiores
                            doloremque deserunt eum nemo.
                        </p>
                        <!-- <i class="bx bxs-quote-alt-left quote-icon"></i> -->
                        <img src="/Icons/quote-left-Icon.png" alt="" class="quote-icon-bottom">
                        <div class="details">
                            <span class="name">- Lorem ipsum dolor </span>
                            <span class="job">Labore et dolore</span>
                        </div>
                    </div>
                   
                    
                </div>
                <div class="swiper-button-next nav-btn"></div>
                <div class="swiper-button-prev nav-btn"></div>
                <div class="swiper-pagination"></div>
            </div>
        </div>
    </div>

</template>

<script>
import Maintopic from '@/components/Maintopic.vue';
export default {
    components: {

        Maintopic
    },

    mounted() {
        var swiper = new Swiper(".mySwiper", {
         
            navigation: {
                nextEl: ".swiper-button-next",
                prevEl: ".swiper-button-prev",
            },
        });
    }

}
</script>

<style></style>