<template lang="">
    <section class="flex justify-between flex-wrap-reverse py-24 lg:gap-0 gap-24">
        <div class="lg:w-1/2">
            <h1 data-aos="fade-up" class="font-extrabold text-[3rem] xl:text-[5rem] backdrop-blur-sm mb-6 lg:text-start text-center">About Me</h1>
            <p data-aos="flip-up" class="text-lg">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia dolores provident commodi natus a? Hic, mollitia. Repellat deleniti quae magni aliquam atque, facilis, commodi obcaecati dolore magnam labore ipsam nam temporibus reprehenderit in reiciendis earum sint? Doloribus voluptatum nam facilis eum cupiditate sit, ullam excepturi tempora perferendis repellat, veritatis, voluptas ipsum placeat. Modi accusantium, optio sapiente, nesciunt fugit et fuga qui facere cumque asperiores numquam. Deleniti cum aperiam provident, sunt non animi cupiditate quasi aspernatur iste eaque quaerat suscipit quas minima ipsam enim accusantium accusamus dolor neque! Eius consectetur corporis modi ab, delectus consequuntur culpa eveniet quod. Asperiores, repudiandae? Adipisci.
            </p>
        </div>
        <div class="lg:w-1/2 w-screen">
            <div class="flex justify-center">
                <div class="relative">
                    <img data-aos="fade" data-aos-duration="1000" data-aos-delay="100" class="lg:w-96 w-60" src="../public/images/profile.png" alt="" srcset="">
                    <div data-aos="slide-up" data-aos-delay="`100" data-aos-easing="ease-in-out" class="absolute md:py-5 py-2 bg-white shadow-lg bottom-0 rounded-t-3xl text-center w-full">
                        <p class="text-black md:text-2xl text-lg font-semibold">Alwi Sahrul Al Falah</p>
                        <p class="text-black md:text-lg text-base font-medium">Web Developer</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    import AOS from 'aos';
    import 'aos/dist/aos.css';

    export default {
        mounted() {
            AOS.init();
        },
    }
</script>