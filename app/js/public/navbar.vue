<!--  -->
<template>
  <Panel title="导航条" :class="$style.panel">
    <ul :class="$style.content">
      <li>
        <router-link :to="{ name: 'home' }">
          <img src="https://img12.360buyimg.com/jrpmobile/jfs/t17650/174/1729132233/4020/2b09fc25/5ad6aac4N620fbed1.png?width=60&height=60" alt="">
          <p>首页</p>
        </router-link>
      </li>
      <li>
        <router-link :to="{ name: 'money' }">
          <img src="https://img12.360buyimg.com/jrpmobile/jfs/t17650/174/1729132233/4020/2b09fc25/5ad6aac4N620fbed1.png?width=60&height=60" alt="">
          <p>理财</p>
        </router-link>
      </li>
      <li>
        <router-link :to="{ name: 'ious' }">
          <img src="https://img12.360buyimg.com/jrpmobile/jfs/t17650/174/1729132233/4020/2b09fc25/5ad6aac4N620fbed1.png?width=60&height=60" alt="">
          <p>白条</p>
        </router-link>
      </li>
      <li>
        <router-link :to="{ name: 'raise' }">
          <img src="https://img12.360buyimg.com/jrpmobile/jfs/t17650/174/1729132233/4020/2b09fc25/5ad6aac4N620fbed1.png?width=60&height=60" alt="">
          <p>众筹</p>
        </router-link>
      </li>
      <li>
        <router-link :to="{ name: 'home' }">
          <img src="https://img12.360buyimg.com/jrpmobile/jfs/t17650/174/1729132233/4020/2b09fc25/5ad6aac4N620fbed1.png?width=60&height=60" alt="">
          <p>我的</p>
        </router-link>
      </li>
    </ul>
  </Panel>
</template>

<script>
import Panel from '../core/panel.vue'
export default {
  props: [],

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
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    height: 100px;
    margin: 0 !important;
     z-index: 1;
    h4{
      display: none;
    }
    .content{
      @include flex(row);
      justify-content: space-around;
      li{
        text-align: center;
        a{
          text-decoration: none;
        }
        img{
          width: 44px;
          height: 44px;
          display: inline-block;
          margin: 12px auto 6px;
        }
        p{
          font-size: 22px;
          color: #656565;
        }
      }
    }
  }
</style>