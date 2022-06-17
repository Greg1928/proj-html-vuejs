<template>
  <section>
    <div class="container">
        <h3>Popular Receipes</h3>
        <p class="spec">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, quidem? Ut esse quo sapienteLorem ipsum dolor, sit amet consectetur adipisicing elit. Vero dolorem</p>
        <div class="row">
            <div class="col-6 white">
                <div class="box">
                    <div class="img">
                    <img src="../../assets/img/Yogurt-Nan-800x527.jpg" alt="">
                </div>
                </div>
                <h4>Lorem ipsum dolor sit amet consectetur adipisicing</h4>
                <span>Lorem ipsum dolor sit amet consectetur adipisicing</span>
                <hr>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Vero dolorem similique labore illum odit ex debitis atque. Enim beatae sed eos quod, aliquam omnis reiciendis corrupti, consectetur expedita officiis suscipit! Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque atque iusto praesentium dignissimos dolorum aspernatur alias eaque voluptate excepturi quo saepe, earum suscipit inventore porro quaerat voluptatum perferendis placeat incidunt!</p>
                <a href="#">learn more</a>
            </div>
            <div class="col-6">
                <div class="row">
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/Mixed-fruits-400x263.jpg" alt="">
                        </div>
                    </div>
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/r-rachel-park-366508-unsplash-min-400x263.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/r-michelle-tsang-500721-unsplash-min-400x263.jpg" alt="">
                        </div>
                    </div>
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/quick-summer-drink-460x295.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="">
                        </div>
                    </div>
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/perfect-cosmopolitan-460x295.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/fi2x-6-460x295.jpg" alt="">
                        </div>
                    </div>
                    <div class="col-6 box">
                        <div class="img">
                            <img src="../../assets/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="">
                        </div>
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

    .spec{
        max-width: 100%;
        padding: 0 300px;
    }

    h3{ 
        text-align: center;
        color: var(--tertiary-color);
        text-transform: uppercase;
        font-size: 20px;
        letter-spacing: 2.5px;
        margin-bottom: 30px;
    }
    
    p{
        text-align: center;
        color: var(--secondary-color);
        margin-bottom: 30px;
    }
    img{
        width: 100%;
    }
    .img{
        position: relative;
    }
    .img::after{
        content: "\f0c1" "Lorem ipsum dolor sit amet consectetur";
        font-family: "Playfair Display", serif;
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        z-index: 1;
        background-image: linear-gradient(rgba($color: #BE4834, $alpha: 0.8), rgba($color: #F56F23, $alpha: 1));
        opacity: 0;
        color: white;
        font-weight: bold;
        transition: opacity 0.3s;
        display: flex;
        flex-direction: column;
        padding: 0 20px;
        text-align: center;
        align-items: center;
        justify-content: center;

    }
    
    .box:hover .img::after{
        opacity: 1;
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
            span{
                color: var(--secondary-color);
            }
            hr{
                border-style: none;
                border-top-style: dotted;
                width: 80%;
                margin: auto;
                margin-top: 20px;
                border-color: var(--secondary-color);
            }
            h4{
                margin-top: 40px;
                font-family: 'Playfair Display', serif;
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
                text-transform: uppercase;
                border-radius: 3px;
                font-weight: bold;
            }
        }

        .row{
            margin-bottom: 20px;
        }
    }
}
</style>