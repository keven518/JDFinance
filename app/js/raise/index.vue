<template lang="html">
    <div>
      <Heador />
      <Slider />
      <Daily />
      <Footer cname='mfooter' />
      <Navbar />
    </div>
</template>

<script>
import Heador from '../public/header'
import Footer from '../public/footer'
import Navbar from '../public/navbar'
import Slider from './rslider'
import Daily from './daily'

export default {
  components: {
    Heador,
    Slider,    
    Daily,
    Footer,
    Navbar
  }
}
</script>

<style lang='scss'>
  .mfooter{
    margin-top: 0!important;
    ul{
      li:first-child{
        display: none;
      }
    }
  }
</style>

