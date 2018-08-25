<template lang="html">
    <div>
      <Heador />
      <Slide />
      <Novice />
      <Borrow />
      <Money />
      <Product />
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Slide from './hslider.vue'
import Novice from './novice.vue'
import Borrow from './borrow.vue'
import Money from './money.vue'
import Product from './product.vue'
export default {
  components: {
    Heador,
    Slide,
    Novice,
    Borrow,
    Money,
    Product
  }
}
</script>

<style lang="scss" module>
</style>
