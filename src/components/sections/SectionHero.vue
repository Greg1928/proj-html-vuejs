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
                        <img src="../../assets/img/single-post-img3-400x263.jpg" alt="">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
                        <span>Lorem ipsum dolor sit amet consectetur</span>
                    </div>
                    <div class="col-4">
                        <img src="../../assets/img/fi-roundup-400x263.jpg" alt="">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
                        <span>Lorem ipsum dolor sit amet consectetur</span>
                    </div>
                    <div class="col-4">
                        <img src="../../assets/img/fi-toasts-400x263.jpg" alt="">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
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
        }

        .pick-small{
            width: 8%;
            position: absolute;
            top: 28%;
            left: 50%;
            right: 50%;
            transform: translate(-50%, -50%);
            background-color: #fc7726;
            border-radius: 5px;
            display: flex;
            justify-content: center;

            p{
               align-self: center;
               margin: 7px 0;
            }
        }
    }
        .container{
            .journal-foodie{
                background-color: white;
                text-align: center;
                padding: 0 40px;

                h3{
                    padding: 20px 0;
                }

                span{
                    padding-bottom: 40px;
                }
            }
        }
    }

</style>