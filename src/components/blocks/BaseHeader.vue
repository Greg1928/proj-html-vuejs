<template>
    <header>
        <div class="container">
            <div class="header-top">
                <div class="row">
                    <div class="col-6">
                        <span>Download App  <small>iOS</small></span>
                        <span>Advertise with us</span>
                    </div>
                    <div class="col-6">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-youtube"></i>
                    </div>
                </div>
            </div>
            <div class="header-logo">
                <img src="../../assets/img/avada-food-logo.png" alt="">
            </div>
            <div class="header-nav">
                <nav>
                    <ul>
                        <li v-for="(link, i) in links" :key="i"><a :href="link.url">{{link.text}}</a></li>
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'BaseHeader',
    data() {
        return {
            index: 0,
            links: [
                {
                    text: "Home",
                    url: "#",
                    current: false,
                },
                {
                    text: "Recipes",
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
header{
    font-family: 'Roboto', sans-serif;
    .container{
        small{
            padding: 3px 5px;
            background-color: var(--primary-color);
            border-radius: 3px;
            color: white;
        }
        .header-top{
            margin-bottom: 20px;
            .row{
                .col-6:first-child{
                    span{
                        margin-right: 2rem;
                        color: var(--secondary-color);
                    }
                }
                .col-6:nth-last-child(1){
                    text-align: right;

                        svg{
                            margin-left: 1.5rem;
                            color: var(--secondary-color);
                        }
                    }
                }
            }

        .header-logo{
            text-align: center;
        }
        .header-nav{
            ul{
                display: flex;
                list-style: none;
                gap: 6rem;
                justify-content: center;
                margin-top: 30px;

                li{
                    a{
                        text-decoration: none;
                        color: var(--tertiary-color);
                    }
                    a:hover{
                        color: var(--primary-color);
                    }
                }
            }
        }
        }
    }
</style>