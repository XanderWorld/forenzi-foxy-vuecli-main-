<template>
  <header>
    <HeaderTop />
    <HeaderBottom />
  </header>
</template>

<script>
import HeaderTop from './HeaderComponents/HeaderTop.vue'
import HeaderBottom from './HeaderComponents/HeaderBottom.vue'

export default {
  name: 'HeaderComponent',
  components: {
    HeaderTop,
    HeaderBottom,
  },
}
</script>

<style lang="scss" scoped>
</style>
