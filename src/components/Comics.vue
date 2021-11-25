<template>
    <div class="container">
        <span class="series-label">CURRENT SERIES</span>
        <div class="comic-cont">
            <a href="">
                <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
                <span class="comic-title">ACTION COMICS</span>
            </a>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <div class="comic-cont">
            <img class="comic-cover" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <span class="comic-title">ACTION COMICS</span>
        </div>
        <a href="" class="load-btn">LOAD MORE</a>
    </div>
</template>

<script>
export default {
    name: 'Comics',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    .container {
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        padding: 150px 0 75px;
        position: relative;
        .series-label {
            position: absolute;
            top: -30px;
            color: white;
            background-color: #0282f9;
            padding: 20px;
            font-weight: bold;
            font-size: 1.4rem;
        }
        a {
            text-decoration: none;
        }
        .comic-cont {
            width: calc(100% / 6);
            padding: 0 20px;
            margin-bottom: 50px;
            transition: all .1s ease;
            color: white;
            &:hover {
                transform: scale(1.02);
            }
            .comic-cover {
                width: 100%;
                display: block;
                aspect-ratio: 1;
                object-fit: cover;
                object-position: top;
                margin-bottom: 20px;
            }
            .comic-title {
                color: white;
            }
        }
        .load-btn {
            margin: 0 auto;
            color: white;
            font-weight: bold;
            background-color: #0282f9;
            padding: 10px 50px;
            transition: all .1s ease;
            &:hover {
                transform: scale(1.05);
            }
        }
    }

</style>