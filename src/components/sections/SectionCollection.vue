<template>
  <section>
    <div class="container">
        <h3>culinary collection</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Qui aut dolor error</p>
        <div class="row">
            <div class="col-3">
                <img src="../../assets/img/drinks-recipes.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/soups-recipes.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/baking-recipes.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/dinner-recipes.png" alt="">
                <p>Drinks</p>
            </div>
        </div>
        <div class="row">
            <div class="col-3">
                <img src="../../assets/img/healthy-recipes.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/staff-picks.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/premium-recipes.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/quick-easy-recipes.png" alt="">
                <p>Drinks</p>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'SectionCollection'
}
</script>

<style lang="scss" scoped> 
section{
    margin-top: 150px;
    .container{
        h3, p{
            text-align: center;
            margin: 20px 0;
        }
        .row{
            column-gap: 53px;
            margin-bottom: 48px;
            .col-3{
                background-color: white;
                text-align: center;
                width: calc(100% / 4 - 40px);

                img{
                    height: 100px;
                    margin-top: 20px;
                }
            }
        }
    }
}
</style>