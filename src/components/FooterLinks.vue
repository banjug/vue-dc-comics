<template>
    <div class="bg-container">
        <div class="link-cont">
            <a href="">SIGN-UP NOW!</a>
            <div>
                <a href="">FOLLOW US</a>
                <ul>
                    <li v-for="link, i in links" :key="i">
                        <a href="link.url">
                            <img :src="link.img" :alt="link.alt">
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
                    img: 'assets/img/footer-facebook.png',
                    url: '#',
                    alt: 'Facebook'
                },
                {
                    img: 'assets/img/footer-twitter.png',
                    url: '#',
                    alt: 'Twitter'
                },
                {
                    img: 'assets/img/footer-youtube.png',
                    url: '#',
                    alt: 'YouTube'
                },
                {
                    img: 'assets/img/footer-pinterest.png',
                    url: '#',
                    alt: 'Pinterest'
                },
                {
                    img: 'assets/img/footer-periscope.png',
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
    }
</style>
