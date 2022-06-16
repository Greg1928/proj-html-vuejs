<template>
  <section>
    <div class="container">
        <div class="row">
            <div class="col-6">
                <h3>farm to table</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elitLorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe doloribus, dolorum natus,.</p>
            </div>
            <div class="col-6">
                <a href="#">read our blog</a>
            </div>
        </div>
        <div class="row">
            <div class="col-8">
                <img src="@/assets/img/single-post-img3-800x527.jpg" alt="">
                <h4>Lorem, ipsum dolor sit amet consectetur adipisicing elit</h4>
                <span>Lorem, ipsum dolor sit amet</span>
                <hr>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe doloribus, dolorum natus, enim alias obcaecati veritatis fugit earum est atque quia ipsa, voluptatum accusantium cupiditate laboriosam aliquam eligendi neque dicta!</p>
                <a href="#">read more ></a>
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
                        <img src="@/assets/img/singapore-featured-image-400x263.jpg" alt="">
                        <!-- <span>city guide: singapore</span>
                        <a href="#">view all city guides</a> -->
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
    .container{
        .row{
            .col-6{
                padding: 0;
                a{
                    padding: 10px 20px;
                    background-color: var(--primary-color);
                    color: white;
                    border-radius: 4px;
                    text-decoration: none;
                }
                p{
                    margin-top: 30px;
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
                }
                p{
                    padding-right: 20px;
                    line-height: 2;
                }
                a{
                    text-decoration: none;
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
                        }
                    }
                }
            }

     }
        
    

</style>