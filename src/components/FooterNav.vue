<template>
    <nav>
        <div class="container">
            <div class="link-cont">
                <div>
                    <ul>
                        <h3>DC COMICS</h3>
                        <li>Characters</li>
                    </ul>
                    <ul>
                        <h3>DC COMICS</h3>
                        <li>Characters</li>
                    </ul>
                </div>
                <ul>
                    <h3>DC COMICS</h3>
                    <li>Characters</li>
                </ul>
                <ul>
                    <h3>DC COMICS</h3>
                    <li>Characters</li>
                </ul>
            </div>
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </nav>
</template>

<script>
export default {
    name: 'FooterNav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
nav {
    background-image: url(../assets/img/footer-bg.jpg);
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
                margin: 0 20px;
            }
        }
        img {
            height: 150%;
            object-fit: cover;
            transform: translate(0, -20%);
        }
    }
}
</style>
