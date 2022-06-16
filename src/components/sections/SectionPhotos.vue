<template>
  <section>
    <div class="row">
        <div class="col-3">
            <img src="@/assets/img/Yogurt-Nan-800x527.jpg" alt="">
        </div>
        <div class="col-3">
            <img src="@/assets/img/Mixed-fruits-800x527.jpg" alt="">
        </div>
        <div class="col-3">
            <img src="@/assets/img/r-rachel-park-366508-unsplash-min-800x527.jpg" alt="">
        </div>
        <div class="col-3">
            <img src="@/assets/img/r-michelle-tsang-500721-unsplash-min-800x527.jpg" alt="">
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'SectionPhotos'
}
</script>

<style lang="scss" scoped>
section{
    img{
        width: 100%;
    }
    .col-3{
        padding: 0;
    }
}
</style>