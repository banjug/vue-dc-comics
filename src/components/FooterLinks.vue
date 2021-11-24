<template>
    <div class="bg-container">
        <div class="link-cont">
            <a href="">SIGN-UP NOW!</a>
            <div>
                <a href="">FOLLOW US</a>
                <ul>
                    <li v-for="link, i in links" :key="i">
                        <a :href="link.url">
                            <img :src="require(`../assets/img/${link.img}`)" :alt="link.alt">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterLinks',
    data(){
        return{
            links: [
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
    .bg-container {
        background-color: #303030;
        .link-cont {
            width: 80%;
            margin: 0 auto;
            padding: 50px 0;
            display: flex;
            justify-content: space-between;
            div {
                display: flex;
                li {
                    display: inline-block;
                }
            }
        }
    }
</style>
