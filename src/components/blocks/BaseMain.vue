<template>
    <main>
        <SectionHero/>
        <SectionPopular/>
        <SectionCollection/>
        <SectionFarm/>
        <SectionPost/>
    </main>
</template>

<script>
import SectionHero from '../sections/SectionHero.vue';
import SectionPopular from '../sections/SectionPopular.vue'
import SectionCollection from '../sections/SectionCollection.vue';
import SectionFarm from '../sections/SectionFarm.vue'
import SectionPost from '../sections/SectionPost.vue'

export default {
    name: "BaseMain",
    components: { SectionHero, SectionPopular, SectionCollection, SectionFarm, SectionPost }
}
</script>

<style lang="scss" scoped>
main{
    background-color: #f5f5f1;
}
</style>