<!--  -->
<template>
  <Panel title="每日签到" :class="$style.panel">
    <section :class="$style.content">
      <img src="//img12.360buyimg.com/jrpmobile/jfs/t26287/10/82496566/21137/c6e0d587/5b83ce0cNa7a89997.png?width=375&height=233" alt="">
      <img src="//img12.360buyimg.com/jrpmobile/jfs/t14215/140/1757206721/24186/81b4e53c/5a56c877Nee6cfc4d.jpg?width=375&height=233" alt="">
      <p>不抢白不抢</p>
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
    Panel,
  }
}

</script>
<style lang='scss' module>
  @import '../../css/element.scss';
  .panel{
    @include panel;
    .content{
      @include flex(row);
      position: relative;
      padding-bottom: 40px;
      img{
        width: 320px;
        height: 200px;
      }
      p{
        position: absolute;
        top: -112px;
        right: 20px;
        font-size: 28px;
        color: #999;
        height: 112px;
        line-height: 112px;
      }
    }
  }
</style>