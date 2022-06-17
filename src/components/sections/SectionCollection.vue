<template>
  <section>
    <div class="container">
        <h3>culinary collection</h3>
        <p id="spec">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Qui aut dolor erroripsum dolor sit amet, consectetur adipisicing elit. Qui aut dolor error</p>
        <div class="row">
            <div class="col-3">
                <img src="../../assets/img/drinks-recipes.png" alt="">
                <p class="over">Drinks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/soups-recipes.png" alt="">
                <p class="over">soups</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/baking-recipes.png" alt="">
                <p class="over">bakery</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/dinner-recipes.png" alt="">
                <p class="over">dinner</p>
            </div>
        </div>
        <div class="row">
            <div class="col-3">
                <img src="../../assets/img/healthy-recipes.png" alt="">
                <p class="over">healthy</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/staff-picks.png" alt="">
                <p class="over">staff picks</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/premium-recipes.png" alt="">
                <p class="over">appetisers</p>
            </div>
            <div class="col-3">
                <img src="../../assets/img/quick-easy-recipes.png" alt="">
                <p class="over">quick & easy</p>
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

    #spec{
        max-width: 100%;
        padding: 0 300px;
        margin-bottom: 40px;
        color: var(--secondary-color);
    }
    .over:hover{
        background-color: var(--primary-color);
        color: white;
        font-weight: bold;
    }
    .container{
        h3{
            color: var(--tertiary-color);
            text-align: center;
            text-transform: uppercase;
            font-family: 'Roboto', sans-serif;
            font-size: 20px;
            letter-spacing: 2.5px;
            margin-bottom: 30px;
        } 
        p{
            text-align: center;
            padding: 20px 0;
            color: var(--tertiary-color);

        }
        .row{
            column-gap: 53px;
            margin-bottom: 48px;
            .col-3{
                background-color: white;
                text-align: center;
                width: calc(100% / 4 - 40px);

                p{
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