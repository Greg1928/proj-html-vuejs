<template>
    <main>
        <SectionHero/>
        <SectionPopular/>
        <SectionCollection/>
    </main>
</template>

<script>
import SectionHero from '../sections/SectionHero.vue';
import SectionPopular from '../sections/SectionPopular.vue'
import SectionCollection from '../sections/SectionCollection.vue';

export default {
    name: "BaseMain",
    components: { SectionHero, SectionPopular, SectionCollection }
}
</script>

<style lang="scss" scoped>
main{
    background-color: #f5f5f1;
}
</style>