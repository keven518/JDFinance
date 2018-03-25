<template lang="html">
    <div>
      <Heador />
      <Slide />
      <Novice />
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Slide from './hslider.vue'
import Novice from './novice.vue'
export default {
  components: {
    Heador,
    Slide,
    Novice
  }
}
</script>

<style lang="scss" module>
</style>
