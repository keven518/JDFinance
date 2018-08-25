<!--  -->
<template>
  <Panel title="极速借贷" :class='$style.panel'>
    <section :class="$style.content">
      <router-link :to="{ name: 'home', params: {} }">
        <img src="//img12.360buyimg.com/jrpmobile/jfs/t2842/350/3035567089/14791/5f6ff93d/577cf395N31e76288.png?width=1125&height=252" />
      </router-link>
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
    .content{
      padding-bottom: 40px;
      img{
        display: block;
        width: 100%;
      }
    }
  }
</style>