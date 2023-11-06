<template>
    <section class="mb-72">
        <h1 data-aos="fade-up" class="font-extrabold text-[2rem] xl:text-[5rem] backdrop-blur-sm text-center">Portfolio</h1>
        <div class="grid grid-cols-12">
            <div class="lg:col-start-3 lg:col-span-8 col-span-12">
                <IndexCorousel />
            </div>
        </div>
    </section>
</template>
<script>

import { 
    initAccordions, 
    initCarousels, 
    initCollapses, 
    initDials, 
    initDismisses, 
    initDrawers, 
    initDropdowns, 
    initModals, 
    initPopovers, 
    initTabs, 
    initTooltips } from 'flowbite'

export default {
    mounted() {
        initAccordions();
        initCarousels();
        initCollapses();
        initDials();
        initDismisses();
        initDrawers();
        initDropdowns();
        initModals();
        initPopovers();
        initTabs();
        initTooltips();
    },
}
</script>
<style>
    
</style>