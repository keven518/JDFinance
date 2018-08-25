<template lang="html">
    <div>
      <Heador />
      <Slide />
      <Novice />
      <Borrow />
      <Money />
      <Product />
      <Life />
      <Footer />
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Footer from '../public/footer.vue'
import Slide from './hslider.vue'
import Novice from './novice.vue'
import Borrow from './borrow.vue'
import Money from './money.vue'
import Product from './product.vue'
import Life from './life.vue'
export default {
  components: {
    Heador,
    Slide,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    Footer
  }
}
</script>

<style lang="scss" module>
</style>
