<template>
  <section>
    <div class="container">
        <div class="row">
            <div class="col-6">
                <h3>farm to table</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elitLorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe doloribus, dolorum natus,.</p>
            </div>
            <div class="col-6">
                <a href="#">read our blog <i class="fa-solid fa-book-open-reader"></i></a>
            </div>
        </div>
        <div class="row">
            <div class="col-8">
                <img src="@/assets/img/single-post-img3-800x527.jpg" alt="">
                <h4>Lorem, ipsum dolor sit amet consectetur adipisicing elit</h4>
                <span>Lorem, ipsum dolor sit amet</span>
                <hr>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe doloribus, dolorum natus, enim alias obcaecati veritatis fugit earum est atque quia ipsa, voluptatum accusantium cupiditate laboriosam aliquam eligendi neque dicta!</p>
                <a href="#">Read More ></a>
                <div class="comments">
                    <i class="fa-regular fa-comments"></i>
                    0
                </div>
            </div>
            <div class="col-4">
                <div class="row">
                    <div class="col-12">
                        <img src="@/assets/img/ad-bg.jpg" alt="">
                        <span>View our latest recipes</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col-12">
                        <div class="image">
                            <img src="@/assets/img/singapore-featured-image-400x263.jpg" alt="">
                        </div>
                        <div class="txt"><small>City Guide: Singapore</small></div>
                        <div class="btn">
                            <i class="fa-solid fa-earth-europe"></i>
                            <a href="#">view all city guides</a>
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
    name: 'SectionFarm'
}
</script>

<style lang="scss" scoped>
section{
    margin-top: 150px;
    height: 1150px;

    h4{
        font-family: 'Playfair Display', serif;
    }
    .container{
        .row{
            .col-6{
                padding: 0;

                h3{
                    text-transform: uppercase;
                    color: var(--tertiary-color);
                    font-size: 20px;
                    letter-spacing: 2.5px;
                }
                a{
                    padding: 10px 20px;
                    background-color: var(--primary-color);
                    color: white;
                    border-radius: 4px;
                    text-decoration: none;
                    text-transform: uppercase;
                    font-weight: bold;
                }
                p{
                    margin-top: 30px;
                    color: var(--secondary-color);
                }
            }
            .col-6:nth-child(2){
                align-self: center;
                text-align: right;
            }
        }
        }
        .row{
            margin-top: 70px;

            .col-8{
                background-color: white;
                padding: 0;
                width: calc(66% - 30px);
                margin-right: 38px;
                height: 900px;

                h4, span, p, a{
                    margin-left: 20px;
                }
                h4{
                    margin-top: 40px;
                    color: var(--tertiary-color);
                }
                p{
                    padding-right: 20px;
                    line-height: 2;
                    color: var(--secondary-color);
                }
                a, span{
                    text-decoration: none;
                    color: var(--secondary-color);
                }
                .comments{
                    text-align: right;
                    margin-right: 20px;
                    display: inline-block;
                    margin-left: 80%;
                }
            }
            img{
                width: 100%;
            }
                .col-4{
                    padding: 0;
                    .row{
                        margin: 0;
                        .col-12{
                            
                            overflow: hidden;
                            margin-bottom: 50px;
                            position: relative;
                            text-align: center;


                            span{
                                position: absolute;
                                top: 55%;
                                left: 50%;
                                transform: translate(-50%, -50%);
                                font-size: 30px;
                                text-transform: uppercase;
                            }

                            .btn{
                                width: 100%;
                                background-color: var(--primary-color);
                            }

                            a{
                                text-decoration: none;
                                color: white;
                                font-weight: bold;
                            }
                            svg{
                                color: white;
                                padding-right: 10px;
                            }
                        }
                        .image{
                            position: relative;
                        }

                        .txt{
                            position: absolute;
                            bottom: 80px;
                            background-color: rgba($color: #000000, $alpha: 0.7);
                            color: white;
                            height: 40px;

                            small{
                                padding: 0 40px;
                                font-weight: bold;
                                line-height: 40px;
                                font-size: 18px;
                                letter-spacing: 2px;
                            }
                        }
                    }
                }
            }

     }
        
    

</style>