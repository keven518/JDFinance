<!--  -->
<template>
  <Panel title="神劵满" :class="$style.panel">
    <section :class="$style.content">
      <img src="//img12.360buyimg.com/jrpmobile/jfs/t23782/175/2345554410/39410/2ff0ffb9/5b7cb9c4N7815ba88.jpg?width=750&height=200" alt="">
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