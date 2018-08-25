<!--  -->
<template>
  <Panel title="理财专享" :class="$style.panel">
    <section :class="$style.content">
      <img src="//img12.360buyimg.com/jrpmobile/jfs/t20746/93/1719082958/12040/306a2296/5b31b40dNeefe4c3c.png?width=750&height=200" alt="">
    </section>
  </Panel>
</template>

<script>
import Panel from '../core/panel.vue'
export default {
  name: '',

  data () {
    return {
    };
  },

  created(){},

  mounted(){},

  watch: {},

  computed: {},

  methods: {},

  components: {
    Panel
  }
}

</script>
<style lang='scss' module>
  @import '../../css/element.scss';
  .panel{
    @include panel;
    h4{
      display: none;
    }
    .content{
      img{
        width: 100%;
        display: block;
      }
    }
  }
</style>