<template>
    <div class="">
        <Maintopic text="Latest News" />
        <div class="container swiper">
            <div class="card-wrapper">
                <ul class="card-list swiper-wrapper">
                    <li class="card-item swiper-slide">
                        <a href="#" class="card-link">
                            <img src="/Images/img1.png" alt="Card Image" class="card-image">

                            <h2 class="card-title">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
                                nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
                                voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
                                gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit
                                amet, consetetur sadipscing elitr, sed diam nonumy eirmod</h2>

                            <div class="d-flex justify-content-end pt-4">
                                <div type="button card-button" class="pe-5">Read</div>
                                <img src="/Icons/right-icon.svg" alt="">
                            </div>
                        </a>
                    </li>
                    <li class="card-item swiper-slide">
                        <a href="#" class="card-link">
                            <img src="/Images/img2.png" alt="Card Image" class="card-image">

                            <h2 class="card-title">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
                                nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
                                voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
                                gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit
                                amet, consetetur sadipscing elitr, sed diam nonumy eirmod</h2>
                            <div class="d-flex justify-content-end pt-4">
                                <div type="button card-button" class="pe-5">Read</div>
                                <img src="/Icons/right-icon.svg" alt="">
                            </div>
                        </a>
                    </li>
                    <li class="card-item swiper-slide">
                        <a href="#" class="card-link">
                            <img src="/Images/img3.png" alt="Card Image" class="card-image">

                            <h2 class="card-title">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
                                nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
                                voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
                                gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit
                                amet, consetetur sadipscing elitr, sed diam nonumy eirmod</h2>
                            <div class="d-flex justify-content-end pt-4">
                                <div type="button card-button" class="pe-5">Read</div>
                                <img src="/Icons/right-icon.svg" alt="">
                            </div>
                        </a>
                    </li>
                    <li class="card-item swiper-slide">
                        <a href="#" class="card-link">
                            <img src="/Images/img1.png" alt="Card Image" class="card-image">

                            <h2 class="card-title">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
                                nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
                                voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
                                gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit
                                amet, consetetur sadipscing elitr, sed diam nonumy eirmod</h2>
                            <div class="d-flex justify-content-end pt-4">
                                <div type="button card-button" class="pe-5">Read</div>
                                <img src="/Icons/right-icon.svg" alt="">
                            </div>
                        </a>
                    </li>
                    <li class="card-item swiper-slide">
                        <a href="#" class="card-link">
                            <img src="/Images/img2.png" alt="Card Image" class="card-image">

                            <h2 class="card-title">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
                                nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam
                                voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd
                                gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit
                                amet, consetetur sadipscing elitr, sed diam nonumy eirmod</h2>
                            <div class="d-flex justify-content-end pt-4">
                                <div type="button card-button" class="pe-5">Read</div>
                                <img src="/Icons/right-icon.svg" alt="">
                            </div>
                        </a>
                    </li>
                </ul>

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
        new Swiper('.card-wrapper', {
            loop: true,
            spaceBetween: 30,

            pagination: {
                el: '.swiper-pagination',
                clickable: true,
                dynamicBullets: true
            },

            breakpoints: {
                0: {
                    slidesPerView: 1
                },
                768: {
                    slidesPerView: 2
                },
                1024: {
                    slidesPerView: 3
                }
            }
        });



    },
}
</script>

<style></style>