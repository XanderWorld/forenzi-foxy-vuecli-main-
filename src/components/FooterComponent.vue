<template>
    <footer>
        <FooterTop />
        <FooterBottom />
    </footer>
</template>

<script>
    import FooterTop from './FooterComponents/FooterTop.vue'
    import FooterBottom from './FooterComponents/FooterBottom.vue'
    export default {
        name: 'FooterComponent',
        components: {
            FooterTop,
            FooterBottom
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

</style>
