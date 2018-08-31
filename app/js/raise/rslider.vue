<!--  -->
<template>
  <Panel title="金融头条" :class="$style.panel">
    <section :class="$style.content">
      <swiper :options="options">
        <swiper-slide>投资有风险，购买需谨慎<em>></em></swiper-slide>
        <swiper-slide>华住金融平台服务协议<em>></em></swiper-slide>
        <swiper-slide>华住金融隐私政策<em>></em></swiper-slide>
      </swiper>
    </section>
  </Panel>
</template>

<script>
import { swiper, swiperSlide } from 'vue-awesome-swiper'
import Panel from '../core/panel.vue'
export default {
  name: '',

  data () {
    return {
      options: {
        autoplay: true,
        loop: true,
        direction: 'vertical'
      }
    };
  },

  created(){},

  mounted(){},

  watch: {},

  computed: {},

  methods: {},

  components: {
    Panel,
    swiper, 
    swiperSlide
  }
}

</script>
<style lang='scss'>
.swiper-container-vertical{
  height: 72px;
  .swiper-slide{
    font-family: PingFangSC-Medium;
    font-size: 28px;
    color: #333;
    em{
      color: #ddd;
      float: right;
      margin-right: 20px;
    }
  }

}
</style>
<style lang='scss' module>
  @import '../../css/element.scss';
  .panel{
    @include panel;
    >h4{
      display: none;
    }
    margin-top: 120px!important;
    .content{
      height: 72px;
      line-height: 72px;
      overflow: hidden;
      padding: 0 0 0 178px;
      background: url(//static.360buyimg.com/zhongchou/product_m/v2/build/static/images/index/news_title.png) 10px center no-repeat;
      background-size: 20%;
    }
  }
</style>