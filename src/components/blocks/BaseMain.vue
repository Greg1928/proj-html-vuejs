<template>
    <main>
        <SectionHero/>
        <SectionPopular/>
        <SectionCollection/>
        <SectionFarm/>
        <SectionPost/>
        <SectionEbook/>
        <SectionPhotos/>
    </main>
</template>

<script>
import SectionHero from '../sections/SectionHero.vue';
import SectionPopular from '../sections/SectionPopular.vue'
import SectionCollection from '../sections/SectionCollection.vue';
import SectionFarm from '../sections/SectionFarm.vue'
import SectionPost from '../sections/SectionPost.vue'
import SectionEbook from '@/components/sections/SectionEbook.vue'
import SectionPhotos from '../sections/SectionPhotos.vue'

export default {
    name: "BaseMain",
    components: { SectionHero, SectionPopular, SectionCollection, SectionFarm, SectionPost, SectionEbook, SectionPhotos }
}
</script>

<style lang="scss" scoped>
main{
    background-color: #f6f7f1;
    font-family: 'Roboto', sans-serif;
}
</style>