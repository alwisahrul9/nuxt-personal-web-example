<template>
    <div data-aos="flip-left" data-aos-delay="500" data-aos-easing="ease-in-out" class="border py-8 px-4 bg-white shadow-2xl h-full text-black rounded-md">
        <div class="relative">
            <img class="h-96 w-96 brightness-50" :src="thumbnail" />
            <h2 class="absolute left-4 bottom-4 text-4xl font-extrabold text-white">{{ title }}</h2>
        </div>
        <div class="my-8 flex flex-wrap gap-6">
            <div v-for="item in skill" :key="item.id">
                <div v-html="item"></div>
            </div>
        </div>
        <p class="font-semibold text-gray-600">Start from:</p>
        <span class="text-3xl font-extrabold text-purple-950">{{ price }}</span>
    </div>
</template>

<script>
export default {
    props: ['title', 'price', 'skill', 'thumbnail']
}
</script>