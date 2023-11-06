<template>
    <IndexSection1 />
    <IndexSection2 />
    <IndexSection3 />
    <IndexSection4 />
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