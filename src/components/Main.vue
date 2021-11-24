<template>
    <main>
        <div class="container">content goes here</div>
    </main>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main {
    background-color: black;
    color: white;
    font-weight: bold;
    padding: 100px 0;
    .container {
        width: 80%;
        margin: 0 auto;
    }
}
</style>
