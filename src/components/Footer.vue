<template>
    <footer>
        <FooterNav/>
        <FooterLinks/>
    </footer>
</template>

<script>
import FooterNav from '../components/FooterNav.vue'
import FooterLinks from '../components/FooterLinks.vue'
export default {
    name: 'Footer',
    components: {
        FooterNav,
        FooterLinks
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
