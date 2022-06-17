<template>
  <section>
    <div class="container">
        <h3>culinary collection</h3>
        <p class="spec">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Qui aut dolor erroripsum dolor sit amet, consectetur adipisicing elit. Qui aut dolor error</p>
        <div class="row">
            <div class="col-3">
                <img src="../../assets/img/drinks-recipes.png" alt="">
                <p>Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/soups-recipes.png" alt="">
                <p>soups</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/baking-recipes.png" alt="">
                <p>bakery</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/dinner-recipes.png" alt="">
                <p>dinner</p>
            </div>
        </div>
        <div class="row">
            <div class="col-3">
                <img src="../../assets/img/healthy-recipes.png" alt="">
                <p>healthy</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/staff-picks.png" alt="">
                <p>staff picks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/premium-recipes.png" alt="">
                <p>appetisers</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/quick-easy-recipes.png" alt="">
                <p>quick & easy</p>
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

    .spec{
        max-width: 100%;
        padding: 0 300px;
    }
    .container{
        h3{
            color: var(--tertiary-color);
            text-align: center;
            text-transform: uppercase;
            font-family: 'Roboto', sans-serif;
            font-size: 20px;
            letter-spacing: 2.5px;
        } 
        p{
            text-align: center;
            margin: 20px 0;
            color: var(--secondary-color);

        }
        .row{
            column-gap: 53px;
            margin-bottom: 48px;
            .col-3{
                background-color: white;
                text-align: center;
                width: calc(100% / 4 - 40px);

                p{
                    color: var(--tertiary-color);
                    text-transform: uppercase;
                }

                img{
                    height: 100px;
                    margin-top: 20px;
                }
            }
        }
    }
}
</style>