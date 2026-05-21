<template>
  <view>
    <!-- 2.0.19支持autoBack，默认为false -->
    <up-navbar title="个人中心" @rightClick="rightClick" :autoBack="true"> </up-navbar>
  </view>
</template>

<script>
// 定义方法
const rightClick = () => {
  console.log('rightClick')
}

const leftClick = () => {
  console.log('leftClick')
}
</script>

<style>
page {
  background-color: #fefcf8 !important;
  box-sizing: border-box;
}
</style>
