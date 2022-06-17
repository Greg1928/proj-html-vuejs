<template>
  <section>
     <div class="container">
        <div class="row">
            <div class="col-8">
                <div class="row">
                    <div class="col-6">
                        <img src="@/assets/img/fi-roundup-600x395.jpg" alt="">
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis</h4>
                        <p>Lorem ipsum dolor sit amet consectetur</p>
                    </div>
                    <div class="col-6">
                        <img src="@/assets/img/fi-korean-food-600x395.jpg" alt="">
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis</h4>
                        <p>Lorem ipsum dolor sit amet consectetur</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6">
                        <img src="@/assets/img/fi-toasts-600x395.jpg" alt="">
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis</h4>
                        <p>Lorem ipsum dolor sit amet consectetur</p>
                    </div>
                    <div class="col-6">
                        <img src="@/assets/img//fi-street-food-600x395.jpg" alt="">
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis</h4>
                        <p>Lorem ipsum dolor sit amet consectetur</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6">
                        <img src="@/assets/img/fi-organic-breakfast-600x395.jpg" alt="">
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis</h4>
                        <p>Lorem ipsum dolor sit amet consectetur</p>
                    </div>
                    <div class="col-6">
                        <img src="@/assets/img/fi-water-side-rest-600x395.jpg" alt="">
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis</h4>
                        <p>Lorem ipsum dolor sit amet consectetur</p>
                    </div>
                </div>
                <div class="col-12">
                    <a href="#">Load more post</a>
                </div>
            </div>
            <div class="col-4">
                <input type="text" placeholder="search...">
                <p style="color:var(--primary-color)">Follow Us</p>
                <div class="icons">
                    <div class="padd"><i class="fa-brands fa-facebook-f"></i></div>
                    <div class="padd"> <i class="fa-brands fa-instagram"></i></div>
                    <div class="padd"><i class="fa-brands fa-twitter"></i></div>
                    <div class="padd"><i class="fa-brands fa-youtube"></i></div>
                    <div class="padd"><i class="fa-brands fa-pinterest-p"></i></div>
                </div>
                <div class="row">
                    <div class="col-6 popular white">
                        <span class="lineH">Popular</span>
                    </div>
                    <div class="col-6 popular">
                        <span class="lineH">Recent</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col-2">
                        <img src="@/assets/img/single-post-img3-66x66.jpg" alt="">
                    </div>
                    <div class="col-10">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
                        <span>march 25th, 2019</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col-2">
                        <img src="@/assets/img/singapore-featured-image-66x66.jpg" alt="">
                    </div>
                    <div class="col-10">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
                        <span>march 25th, 2019</span>
                    </div>
                </div>
                <div class="row">
                    <div class="col-2">
                        <img src="@/assets/img/slide1-bg-66x66.jpg" alt="">
                    </div>
                    <div class="col-10">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
                        <span>march 25th, 2019</span>
                    </div>
                </div>
                <div class="row">
                    <div class="content">
                        <div class="row">
                            <div class="col-10">
                                <h5>Tweets <small> by </small></h5>
                                <a href="#"> @Theme_Fusion</a>
                            </div>
                            <div class="col-2 align-self-end">
                                <i class="fa-solid fa-circle-info"></i>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-2">
                                <img src="@/assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="">
                            </div>
                            <div class="col-10">
                                <div class="div d-flex justify-content-between">
                                    <h6>ThemeFusion</h6>
                                    <i class="fa-brands fa-twitter"></i>
                                </div>
                                <div class="div"><span>@Theme_Fusion</span></div>
                                <p id="margin-p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum saepe quos veritatis quaerat hic dignissimos id quam recusandae vero, deserunt labore sapiente eius molestias nulla in? Dicta quas facilis quia.</p>
                                <img src="@/assets/img/En2TRxLW4AEiWUN.jpeg" alt="">
                                <div class="row">
                                    <div class="col-6">
                                        <i class="fa-regular fa-heart"></i>
                                        <i class="fa-solid fa-arrow-right-from-bracket"></i>
                                    </div>
                                    <div class="col-6 right">
                                        <span>21h</span>
                                    </div>
                                </div>
                            </div>
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
    name: 'SectionPost'
}
</script>

<style lang="scss" scoped>
section{

    h4{
        color: var(--tertiary-color);
        margin-top: 14px;
        padding: 0 30px;
        font-family: 'Playfair Display', serif;
    }
    .popular{
        text-align: center;
        border: 1px solid #edede7;
        height: 50px;
        margin-top: 40px;
        color: var(--tertiary-color);
        cursor: pointer;
    }
    .lineH{
        line-height: 50px;
        color: var(--tertiary-color);
    }
    #margin-p{
        margin-bottom: 40px;
    }
    .white{
        background-color: white;
    }
    .icons{
        display: flex;
        justify-content: space-around;
        width: 40%;
        cursor: pointer;
    }
    .padd{
        width: 30px;
        height: 30px;
        text-align: center;
        background-color: #edede7;
        border-radius: 5px;
        display: flex;
            justify-content: center;

        svg{
            align-self: center;
            color: var(--secondary-color);
        }
    }
    input{
        border-radius: 5px;
        width: 100%;
        border-color: #edede7;
        height: 60px;
        margin-bottom: 30px;
        color: #edede7;
    }
    .col-12{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 50px;
        background-color: #edede7;

        a{
            text-decoration: none;
            text-transform: uppercase;
            color: var(--tertiary-color);
        }
    }
    .container{
        .row{
            .col-8{
                width: calc(66% - 30px);
                .row{
                    column-gap: 40px;
                    .col-6{
                        background-color: white;
                        margin-bottom: 30px;
                        width: calc(50% - 20px);
                        padding: 0;
                        text-align: center;
                        p{
                            color: var(--secondary-color);
                        }
                        img{
                            width: 100%;
                        }
                    }
                    }
                }
            }
            .col-4{
                flex-direction: column;
                margin-left: 38px;

                .row{
                    margin-bottom: 20px;
                     
                    .col-2{
                        align-self: center;
                    img{
                        border-radius: 100%;
                        margin-top: 10px;
                        margin-left: 15px;
                    }
                }
                .col-10{
                    p{
                        margin: 0;
                        line-height: 1.5;
                        color: var(--tertiary-color);
                    }
                    span{
                        color: var(--secondary-color);
                    }
                }
                .content{
                    background-color: white;
                    border-radius: 7px;
                    .row{
                        .col-2{
                            align-self: flex-start;
                        }
                        svg{
                            padding-right: 30px;
                            color: var(--quaternary-color);
                        }
                        .right{
                                text-align: right;
                            }
                    }
                    }
                    h5{
                        display: inline-block;
                    }
                    h6{
                       margin: 0; 
                    }
                    img{
                        width: 100%;
                        // margin-top: 30px;
                        border-radius: 5px;
                    }
                    .col-10{
                        margin-top: 20px;
                    }
                    .col-2{
                        text-align: right;
                    }
                }
                }
            }
        }
    


</style>