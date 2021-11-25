<template>
    <main>
        <Jumbotron/>
        <Comics/>
    </main>
</template>

<script>
import Jumbotron from '../components/Jumbotron.vue'
import Comics from '../components/Comics.vue'
export default {
    name: 'Main',
    components: {
        Jumbotron,
        Comics,
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main {
    background-color: #1c1c1c;
}
</style>
