<template>
    <section class="link-strip">
        <ul>
            <li v-for="link, i in links" :key="i">
                <a href="">
                    <img src="link.img" alt="  ">
                    {{link.text}}
                </a>
            </li>
        </ul>
    </section>
</template>

<script>
export default {
    name: 'LinkStrip',
    data(){
        return{
            links:[
                {
                    img: '../assets/img/buy-comics-digital-comics.png',
                    text: 'DIGITAL COMICS',
                },
                {
                    img: '../assets/img/buy-comics-merchandise.png',
                    text: 'DC MERCHANDISE',
                },
                {
                    img: '../assets/img/buy-comics-subscriptions.png',
                    text: 'SUBSCRIPTION',
                },
                {
                    img: '../assets/img/buy-comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR',
                },
                {
                    img: '../assets/img/buy-comics-power-visa.png',
                    text: 'DC POWER VISA',
                },
            ]
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .link-strip {
        background-color: blue;
        padding: 50px 0;
        ul {
            width: 80%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            li {
                display: inline-block;
                a {
                    display: flex;
                    align-items: center;
                    color: white;
                    text-decoration: none;
                    img {
                        height: 80px;
                        margin-right: 20px;
                    }
                }
            }
        }
    }
</style>