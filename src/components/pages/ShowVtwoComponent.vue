<template>
    <div class="home">
        <div class="container">
            <div class="row">
                <ShowBox2 />
                <h4 class="fw-bold py-2">Elenco formati disponibili</h4>
                <TableComponent />
            </div>
        </div>
        <ClassicRight />
        <div class="container">
            <div class="row">
                <BannerNewsComponent />
            </div>
        </div>

    </div>
</template>

<script>
    import ShowBox2 from '../MainComponents/ShowBox2.vue'
    import TableComponent from '../MainComponents/TableComponent.vue'
    import BannerNewsComponent from '../MainComponents/BannerNewsComponent.vue'
    import ClassicRight from '../MainComponents/ClassicRight.vue'

    export default {
        name: 'UnOnda',
        components: {
            ShowBox2,
            TableComponent,
            BannerNewsComponent,
            ClassicRight,
        }
    }
</script>

<style lang='scss' scoped>




</style>
