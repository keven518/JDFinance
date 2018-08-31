<!--  -->
<template>
  <Panel title="轮播图" :class="$style.panel">
    <section :class="$style.content">
      <Slider :items="items" :cname="$style.slider" />
    </section>
  </Panel>
</template>

<script>
import Panel from '../core/panel.vue'
import Slider from '../core/slider.vue'
export default {
  name: '',

  data () {
    return {
      items: [{
        // href: 'home',
        src: '//img12.360buyimg.com/jrpmobile/jfs/t27787/252/3387618/21105/fcd12476/5b7fe336N9800ddb2.jpg?width=750&height=400'
      },{
        // href: 'home',
        src: '//img12.360buyimg.com/jrpmobile/jfs/t25531/353/865116044/48280/b35e9f58/5b7fe33dN37818fea.jpg?width=750&height=400'
      },{
        // href: 'home',
        src: '//img12.360buyimg.com/jrpmobile/jfs/t27355/256/4580821/29438/e1d12b95/5b7fe347N68800961.jpg?width=750&height=400'
      },{
        // href: 'home',
        src: '//img12.360buyimg.com/jrpmobile/jfs/t24415/75/2429210456/26381/2890a393/5b7fe341Ne848b7e6.jpg?width=750&height=400'
      }]
    };
  },

  created(){},

  mounted(){},

  watch: {},

  computed: {},

  methods: {},

  components: {
    Panel,
    Slider
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
      .slider{
        margin-top: 120px
      }

    }
  }
</style>