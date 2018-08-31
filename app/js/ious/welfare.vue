<!--  -->
<template>
  <Panel title="白条福利" :class="$style.panel">
    <section :class="$style.content">
      <div :class="$style.item">
        <img src="//img12.360buyimg.com/jrpmobile/jfs/t19825/175/2716312753/5076/dfe2d74f/5b7cc241N65ff1885.png?width=90&height=90" alt="">
        <div>
          <h4>阅读理财</h4>
          <p>预期年化收益率4.50%</p>
        </div>
        <em>去赚钱 ></em>
      </div>
      <div :class="$style.item">
        <img src="//img12.360buyimg.com/jrpmobile/jfs/t24682/140/813231673/5159/f8133cd6/5b7cc24fNb15a2746.png?width=90&height=90" alt="">
        <div>
          <h4>阅读理财</h4>
          <p>预期年化收益率4.50%</p>
        </div>
        <em>去赚钱 ></em>
      </div>
      <div :class="$style.item">
        <img src="https://img12.360buyimg.com/jrpmobile/jfs/t25789/23/702574804/4169/de69ccb0/5b7cc25bN4bcd4087.png?width=90&height=90" alt="">
        <div>
          <h4>阅读理财</h4>
          <p>预期年化收益率4.50%</p>
        </div>
        <em>去赚钱 ></em>
      </div>
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
    >h4{
      border-bottom: 1px #ddd solid;
    }
    .content{
      @include flex;
      .item{
        @include flex(row);
        align-items: center;
        height: 140px;
        &::after{
          content: '';
          box-sizing: border-box;
          height: 0;
          width: 100%;
          border-bottom: 1px solid #ddd;
          margin-left: 150px;
        }
        &:last-child:after{
          border-bottom: none;
        }
        >img{
          width: 88px;
          height: 88px;
          display: inline-block;
          margin: 0 32px;
        }
        >div{
          font-size: 32px;
          color: #333;
          line-height: 1.8;
          width: 344px;
          p{
            color: #ff3232;
            font-size: 24px;
            line-height: 1.1;
            white-space: normal;
            text-overflow: ellipsis;
            overflow: hidden;
          }
        }
        >em{
          color: #ff801a;
          font-size: 28px;
        }
      }
    }
  }
</style>