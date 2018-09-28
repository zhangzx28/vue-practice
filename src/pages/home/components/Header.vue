<template>
  <div class="header">
    <div class="header-left">left</div>
    <div class="header-input">输入城市/景点/游玩主题 </div>
    <div class="header-right">right</div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
  .header
    display: flex
    line-height: .86rem
    background: #00bcd4
    color: #fff
    .header-left
      width: 0.64rem
      float: left
    .header-input
      flex: 1
      margin-top: .12rem
      margin-left: .2rem
      line-height: .64rem
      height: .64rem
      border-radius: 0.1rem
      background: #fff
      color: #ccc
    .header-right
      width: 1.24rem
      float: right
      text-align: center

</style>
