<template>
    <section class="link-strip">
        <ul>
            <li>
                <a href="">
                    <img src="..\assets\img\buy-comics-digital-comics.png" alt="  ">
                    DIGITAL COMICS
                </a>
            </li>
            <li>
                <a href="">
                    <img src="..\assets\img\buy-comics-digital-comics.png" alt="  ">
                    DIGITAL COMICS
                </a>
            </li>
            <li>
                <a href="">
                    <img src="..\assets\img\buy-comics-digital-comics.png" alt="  ">
                    DIGITAL COMICS
                </a>
            </li>
            <li>
                <a href="">
                    <img src="..\assets\img\buy-comics-digital-comics.png" alt="  ">
                    DIGITAL COMICS
                </a>
            </li>
            <li>
                <a href="">
                    <img src="..\assets\img\buy-comics-digital-comics.png" alt="  ">
                    DIGITAL COMICS
                </a>
            </li>
        </ul>
    </section>
</template>

<script>
export default {
    name: 'LinkStrip',
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