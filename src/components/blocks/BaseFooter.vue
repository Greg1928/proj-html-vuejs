<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-3">
                    <img src="@/assets/img/avada-food-logo-mob-2x.png" alt="">
                    <div class="icons">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-youtube"></i>
                    </div>
                </div>
                <div class="col-3">
                    <ul>
                        <li v-for="(link, i) in links" :key="i"><a :href="link.url">{{link.text}}</a></li>
                    </ul>
                </div>
                <div class="col-3">
                    <h4>Contact</h4>
                    <ul>
                        <li><i id="spec-margin" class="fa-solid fa-location-dot"></i>Lorem ipsum dolor sit, amet consectetur adipisicing elit</li>
                        <li><i id="spec-margin" class="fa-solid fa-phone-flip"></i>83485287</li>
                        <li><i id="spec-margin" class="fa-solid fa-envelope"></i>@dhjioqdhi</li>
                    </ul>
                </div>
                <div class="col-3">
                    <h4>Get our app:</h4>
                    <ul>
                        <li><img src="@/assets/img/download-android.png" alt=""></li>
                        <li><img src="@/assets/img/download-app-store.png" alt=""></li>
                    </ul>
                    
                </div>
            </div>
        </div>
        <div class="footer-bottom">
                <i class="fa-solid fa-chevron-up left"></i>
                <small>@copyright Lorem ipsum dolor sit amet, consectetur adipisicing elit.</small>
            </div>
    </footer>
</template>

<script>
export default {
    name: 'BaseFooter',
    data() {
        return {
            index: 0,
            links: [
                {
                    text: "Receipes",
                    url: "#",
                    current: false,
                },
                {
                    text: "Places",
                    url: "#",
                    current: false,
                },
                {
                    text: "Blog",
                    url: "#",
                    current: false,
                },
                {
                    text: "About",
                    url: "#",
                    current: false,
                },
                {
                    text: "Contact",
                    url: "#",
                    current: false,
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
footer{
    margin-top: 70px;
    font-family: 'Roboto', sans-serif;

    #spec-margin{
        margin: 0 20px 0 0;
    }

    img{
        width: 60%;
    }

    svg{
        margin: 40px 20px 0 0;
        color: var(--secondary-color);
    }

    h4{
        color: var(--primary-color);
        margin-bottom: 30px;
    }
    ul{
        list-style: none;
        padding: 0; 

        li{
            margin-bottom: 20px;
            color: var(--secondary-color);

            a{
                color: var(--tertiary-color);
                text-decoration: none;
            }
        }
    }
    .footer-bottom{
        position: relative;
        text-align: center;
        margin: 60px 0 30px 0;
    }
    .left{
        position: absolute;
        left: 70px;
        bottom: 0;
        padding: 20px;
        border-radius: 100%;
        color: white;
        background-color: gray;
        margin: 0;
    }
    small{
        color: var(--secondary-color);
    }
}
</style>