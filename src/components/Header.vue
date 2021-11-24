<template>
    <header>
        <a href="">
            <img src="../assets/img/dc-logo.png" alt="DC Logo">
        </a>
        <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li class="active"><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
        </ul>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    margin: 0 auto;
    img {
        padding: 20px 0;
    }
    li {
        display: inline-block;
        margin: 0 15px;
        padding: 60px 0;
        a {
            text-decoration: none;
            color: black;
        }
        &.active {
            a {
                color: blue;
            }
            border-bottom: 5px solid blue;
        }
        &:hover {
            a {
                color: blue;
            }
            border-bottom: 5px solid blue;
        }
    }
}

</style>