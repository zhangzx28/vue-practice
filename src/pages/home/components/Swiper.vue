<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide v-for="item in swiperList" :key="item.id">
        <img class="swiper-img"
             :src="item.imgUrl">
      </swiper-slide>

      <!-- Optional controls -->
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: {
          el: '.swiper-pagination'
        },
        loop: true,
        autoplay: {
          delay: 2000
        }
      },
      swiperList: [{
        id: '00001',
        imgUrl: 'http://img1.qunarzz.com/piao/fusion/1809/86/deb33800de224c02.jpg_750x200_74fb795e.jpg'
      }, {
        id: '00002',
        imgUrl: 'http://img1.qunarzz.com/piao/fusion/1809/91/63a7f117b30cd202.jpg_750x200_6c2dcbc9.jpg'
      }]
    }
  }
}
</script>

<style lang="stylus" scoped>
  .wrapper >>> .swiper-pagination-bullet-active
    background: #fff !important
  .wrapper
    width: 100%
    height: 0
    overflow: hidden
    padding-bottom: 26.67%
    background: #eee
    .swiper-img
      width: 100%
</style>
