<template>
    <footer>

        <nav>
            <div class="container">
                <div class="link-cont">
                    <div>
                        <ul>
                            <h3>DC COMICS</h3>
                            <li v-for="link, i in dcComicsLinks" :key="i">
                                <a :href="link.url">{{link.text}}</a>
                            </li>
                        </ul>
                        <ul>
                            <h3>SHOP</h3>
                            <li v-for="link, i in shopLinks" :key="i">
                                <a :href="link.url">{{link.text}}</a>
                            </li>
                        </ul>
                    </div>
                    <ul>
                        <h3>DC</h3>
                        <li v-for="link, i in dcLinks" :key="i">
                            <a :href="link.url">{{link.text}}</a>
                        </li>
                    </ul>
                    <ul>
                        <h3>SITES</h3>
                        <li v-for="link, i in sitesLinks" :key="i">
                            <a :href="link.url">{{link.text}}</a>
                        </li>
                    </ul>
                </div>
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </nav>

        <div class="bg-container">
            <div class="link-cont">
                <a class="sign-btn" href="">SIGN-UP NOW!</a>
                <div>
                    <a href="">FOLLOW US</a>
                    <ul>
                        <li v-for="link, i in socialLinks" :key="i">
                            <a :href="link.url">
                                <img :src="require(`../assets/img/${link.img}`)" :alt="link.alt">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

export default {
    name: 'Footer',
    data(){
        return{
            dcComicsLinks: [
                {
                    url: '#',
                    text: 'Characters'
                },
                {
                    url: '#',
                    text: 'Comics'
                },
                {
                    url: '#',
                    text: 'Movies'
                },
                {
                    url: '#',
                    text: 'TV'
                },
                {
                    url: '#',
                    text: 'Games'
                },
                {
                    url: '#',
                    text: 'Videos'
                },
                {
                    url: '#',
                    text: 'News'
                },
            ],
            shopLinks: [
                {
                    url: '#',
                    text: 'Shop DC'
                },
                {
                    url: '#',
                    text: 'Shop DC Collectibles'
                },

            ],
            dcLinks: [
                {
                    url: '#',
                    text: 'Terms Of Use'
                },
                {
                    url: '#',
                    text: 'Privacy Policy (New)'
                },
                {
                    url: '#',
                    text: 'Ad Choices'
                },
                {
                    url: '#',
                    text: 'Advertising'
                },
                {
                    url: '#',
                    text: 'Jobs'
                },
                {
                    url: '#',
                    text: 'Subscriptions'
                },
                {
                    url: '#',
                    text: 'Talent Workshop'
                },
                {
                    url: '#',
                    text: 'CPSC Certificates'
                },
                {
                    url: '#',
                    text: 'Ratings'
                },
                {
                    url: '#',
                    text: 'Shop Help'
                },
                {
                    url: '#',
                    text: 'Contact Us'
                },
            ],
            sitesLinks: [
                {
                    url: '#',
                    text: 'DC'
                },
                {
                    url: '#',
                    text: 'MAD Magazine'
                },
                {
                    url: '#',
                    text: 'DC Kids'
                },
                {
                    url: '#',
                    text: 'DC Universe'
                },
                {
                    url: '#',
                    text: 'DC Power Visa'
                },
            ],
            socialLinks: [
                {
                    img: 'footer-facebook.png',
                    url: '#',
                    alt: 'Facebook'
                },
                {
                    img: 'footer-twitter.png',
                    url: '#',
                    alt: 'Twitter'
                },
                {
                    img: 'footer-youtube.png',
                    url: '#',
                    alt: 'YouTube'
                },
                {
                    img: 'footer-pinterest.png',
                    url: '#',
                    alt: 'Pinterest'
                },
                {
                    img: 'footer-periscope.png',
                    url: '#',
                    alt: 'Periscope'
                },
            ]
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    nav {
        background-image: url("../assets/img/footer-bg.jpg");
        // padding: 50px 0;
        color: white;
        .container {
            width: 80%;
            height: 400px;
            overflow: hidden;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            .link-cont {
                padding: 30px 0;
                display: flex;
                > * {
                    margin-right: 20px;
                }
                li {
                    list-style: none;
                        margin: 10px 0;
                        font-size: .8rem;
                    a {
                        color: gray;
                        text-decoration: none;
                        &:hover {
                            color: white;
                        }
                    }
                }
            }
            img {
                height: 150%;
                object-fit: cover;
                transform: translate(0, -20%);
            }
        }
    }

    .bg-container {
        background-color: #303030;
        .link-cont {
            width: 80%;
            margin: 0 auto;
            padding: 50px 0;
            display: flex;
            justify-content: space-between;
            .sign-btn {
                border: 2px solid #0282f9;
                padding: 15px;
                color: white;
                text-decoration: none;
                transition: all .2s ease;
                &:hover {
                    background-color: #0282f9;
                }
            }
            div {
                display: flex;
                align-items: center;
                > a {
                    color: #0282f9;
                    text-decoration: none;
                    font-weight: bold;
                    font-size: 1.3rem;
                    margin-right: 20px;
                }
                li {
                    display: inline-block;
                    margin-right: 10px;
                }
            }
        }
    }
</style>
