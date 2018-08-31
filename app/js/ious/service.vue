<!--  -->
<template>
  <Panel title="更多服务" :class="$style.panel">
    <section :class="$style.content">
      <div :class="$style.item" v-for="item in items" :key="item.img">
        <img :src="item.img" alt="">
        <p>{{item.text}}</p>
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
      items: [{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t6757/309/2669181098/3183/40d08c37/5965c32eNfd2302a5.png?width=90&height=90',
        text: '小白卡'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t6424/260/2675895212/5334/7b957f87/5965c422N5d3905db.png?width=90&height=90',
        text: '白条商城'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t5686/311/6054725983/3080/5050748f/596710dfN79c2d5ae.png?width=90&height=90',
        text: '消费分期'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t21988/248/644694035/5569/16609f2a/5b149b37N7ea270bc.png?width=90&height=90',
        text: '借钱'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t12430/361/1344312222/9697/c59d311b/5a1e90dcN571accd9.png?width=136&height=136',
        text: '白条提额'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t6424/336/2659890302/4060/4bba8090/5965db34N20a6fe02.png?width=90&height=90',
        text: '白条闪付'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t6214/70/2646101465/4242/8d891843/5965dbdcN21d3d2cc.png?width=90&height=90',
        text: '小白会玩'
      },{
        img:'//img12.360buyimg.com/jrpmobile/jfs/t13264/330/2493234123/3373/1894ec99/5a42290aNde550718.png?width=90&height=90',
        text: '钢镚'
      }]
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
      @include flex(row);
      .item{
        width: 160px;
        height: 144px;
        text-align: center;
        margin-bottom: 40px;
        img{
          width: 90px;
          height: 90px;
        }
        p{
          font-size: 26px;
          color: #666;
          margin-top: 12px;
        }
      }
    }
  }
</style>