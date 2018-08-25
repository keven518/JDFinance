<template lang="html">
    <div>
      <Heador />
      <Slide />
      <Ada />
      <Money />
      <Adb />
      <Footer />
      <Navbar />
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Footer from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import Slide from './mslider.vue'
import Ada from './ada.vue'
import Money from './money.vue'
import Adb from './adb.vue'
export default {
  components: {
    Heador,
    Slide,
    Ada,
    Money,
    Adb,
    Footer,
    Navbar
  }
}
</script>
