<template>
<section>
    <div class="hero-pick">
        <h1>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h1>
        <span>March 25, 2019</span>
        <div class="pick-small">
            <p>today's pick</p>
        </div>
    </div>
        <div class="container">
            <div class="journal-foodie">
                <h3>foodie journal</h3>
                <div class="row">
                    <div class="col-4">
                        <div class="box">
                            <div class="img">
                            <img src="../../assets/img/single-post-img3-400x263.jpg" alt="">
                        </div>
                        </div>
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit</h4>
                        <span>Lorem ipsum dolor sit amet consectetur</span>
                    </div>
                    <div class="col-4">
                        <div class="box">
                            <div class="img">
                            <img src="../../assets/img/fi-roundup-400x263.jpg" alt="">
                        </div>
                        </div>
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit</h4>
                        <span>Lorem ipsum dolor sit amet consectetur</span>
                    </div>
                    <div class="col-4">
                        <div class="box">
                            <div class="img">
                            <img src="../../assets/img/fi-toasts-400x263.jpg" alt="">
                        </div>
                        </div>
                        <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit</h4>
                        <span>Lorem ipsum dolor sit amet consectetur</span>
                    </div>
                </div>
            </div>
        </div>
  </section>
</template>

<script>
export default {
    name: 'SectionHero'
}
</script>

<style lang="scss" scoped>
section{
    background-image: url("../../assets/img/single-post-img3.jpg");
    background-position: center;
    background-size: cover;
    height: 700px;
    display: flex;
    flex-direction: column;
    position: relative;
    row-gap: 13.9rem;

    .img{
        position: relative;
    }
    .img::after{
        content: "\f0c1" "Lorem ipsum dolor sit amet consecteturi psum dolor sit amet consectetur";
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
        padding: 0 40px;
        text-align: center;
        align-items: center;
        justify-content: center;

    }
    .box:hover .img::after{
        opacity: 1;
    }

    
    .hero-pick{
        width: 40%;
        margin: 200px auto 0 auto;
        height: 200px;
        background-color: white;
        border-radius: 10px;
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: center;

        h1{
            padding: 30px 30px 15px 30px;
            color: var(--tertiary-color);
            font-family: 'Playfair Display', serif;
        }
        span{
            color: var(--secondary-color);
            margin-bottom: 30px;
        }

        .pick-small{
            width: 9%;
            position: absolute;
            top: 28%;
            left: 50%;
            right: 50%;
            transform: translate(-50%, -50%);
            background-color: var(--primary-color);
            border-radius: 5px;
            display: flex;
            justify-content: center;

            p{
               align-self: center;
               margin: 7px 0;
               color: white;
               text-transform: uppercase;
               font-weight: bold;
            }
        }
    }
        .container{
            .journal-foodie{
                background-color: white;
                text-align: center;
                padding: 0 40px;
                height: 500px;

                img{
                    width: 100%;
                }

                h4{
                    color: var(--tertiary-color);
                    padding: 20px 30px 0 30px;
                    font-family: 'Playfair Display', serif;
                }

                h3{
                    padding: 20px 0;
                    text-transform: uppercase;
                    color: var(--tertiary-color);
                    font-size: 20px;
                    letter-spacing: 2.5px;
                }

                span{
                    padding-bottom: 40px;
                    color: var(--secondary-color);
                    padding-bottom: 40px;
                }
            }
        }
    }

</style>