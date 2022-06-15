<template>
  <section>
    <div class="container">
        <h3>Popular Receipes</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, quidem? Ut esse quo sapiente</p>
        <div class="row">
            <div class="col-6 white">
                <img src="../../assets/img/Yogurt-Nan-800x527.jpg" alt="">
                <h4>Lorem ipsum dolor sit amet consectetur adipisicing</h4>
                <span>Lorem ipsum dolor sit amet consectetur adipisicing</span>
                <hr>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vero dolorem similique labore illum odit ex debitis atque. Enim beatae sed eos quod, aliquam omnis reiciendis corrupti, consectetur expedita officiis suscipit! Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque atque iusto praesentium dignissimos dolorum aspernatur alias eaque voluptate excepturi quo saepe, earum suscipit inventore porro quaerat voluptatum perferendis placeat incidunt!</p>
                <a href="#">learn more</a>
            </div>
            <div class="col-6">
                <div class="row">
                    <div class="col-6">
                        <img src="../../assets/img/Mixed-fruits-400x263.jpg" alt="">
                    </div>
                    <div class="col-6">
                        <img src="../../assets/img/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="">
                    </div>
                </div>
                                <div class="row">
                    <div class="col-6">
                        <img src="../../assets/img/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="">
                    </div>
                    <div class="col-6">
                        <img src="../../assets/img/quick-summer-drink-460x295.jpg" alt="">
                    </div>
                </div>
                                <div class="row">
                    <div class="col-6">
                        <img src="../../assets/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="">
                    </div>
                    <div class="col-6">
                        <img src="../../assets/img/perfect-cosmopolitan-460x295.jpg" alt="">
                    </div>
                </div>
                                <div class="row">
                    <div class="col-6">
                        <img src="../../assets/img/fi2x-6-460x295.jpg" alt="">
                    </div>
                    <div class="col-6">
                        <img src="../../assets/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'SectionPopular'
}
</script>

<style lang="scss" scoped>
section{
    margin-top: 500px;

    h3, p{
        text-align: center;
    }
    img{
        width: 100%;
    }
    .container{
        .white{
            background-color: white;
        }
        .row{
             h4, p, span, a{
            margin-left: 20px;
            margin-top: 20px;

            }
            .col-6{
                padding: 0;
                width: calc(50% - 20px);
                margin: 0 10px;
            }
            h4{
                margin-top: 40px;
            }
            p{
                line-height: 2;
                margin-bottom: 30px;
                text-align: left;
                padding-right: 20px;
            }
            a{
                padding: 10px 20px;
                background-color: var(--primary-color);
                text-decoration: none;
                color: white;
            }
        }

        .row{
            margin-bottom: 20px;
        }
    }
}
</style>