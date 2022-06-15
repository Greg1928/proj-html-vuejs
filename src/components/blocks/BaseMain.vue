<template>
    <main>
        <SectionHero/>
        <SectionPopular/>
    </main>
</template>

<script>
import SectionHero from '../sections/SectionHero.vue';
import SectionPopular from '../sections/SectionPopular.vue'

export default {
    name: "BaseMain",
    components: { SectionHero, SectionPopular }
}
</script>

<style lang="scss" scoped>
main{
    background-color: #f5f5f1;
}
</style>