<template>
  <div class="sell-main">
    <ul class="mp-listitem-con">
      <li class="mp-listentrance-item item-left"><span class="iconfont">&#xe611;</span>长春</li>
      <li class="mp-listentrance-item"><span class="iconfont">&#xe629;</span>玩水季</li>
    </ul>
    <ul class="mp-activity-con">
      <li class="mp-activity-item item-left"
          style="background:url(http://img1.qunarzz.com/piao/fusion/1806/29/30427c0e0658b502.png) center center no-repeat;background-size:auto 100%;"></li>
      <li class="mp-activity-item"
          style="background:url(http://img1.qunarzz.com/piao/fusion/1809/b7/00000ce26b312902.png) center center no-repeat;background-size:auto 100%;"></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeSell'
}
</script>

<style lang="stylus" scoped>
  .sell-main
    background-color: #3333330a
    .mp-listitem-con
      display: flex
      width: 100%
      background-color: #fff
      .mp-listentrance-item
        overflow: hidden
        flex: 1
        width: 0
        height: .94rem
        line-height: .94rem
        text-align: center
        border: solid #eee
        border-width: .02rem 0
      .item-left
        border-right: .02rem solid #eee
    .mp-activity-con
      margin-top .2rem
      display: flex
      width: 100%
      background-color: #fff
      .mp-activity-item
        flex: 1
        height: 1.36rem
        line-height 1.36rem
        text-align: center
        border: solid #eee
        border-width: .02rem 0
      .item-left
        border-right: .02rem solid #eee
</style>
