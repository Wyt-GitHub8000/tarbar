<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="red">
      <img slot="item-icon" src="../assets/img/tabbar/home.svg" alt="" >
      <img slot="item-icon-active" src="../assets/img/tabbar/Hom.svg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item >
    <tab-bar-item path="/category" activeColor="pink">
      <img slot="item-icon" src="../assets/img/tabbar/all-fill.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/All.svg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="green">
      <img slot="item-icon" src="../assets/img/tabbar/icon-test.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/Icon.svg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="deepPink">
      <img slot="item-icon" src="../assets/img/tabbar/RectangleCopy.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/Rectangle.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from './tabbar/TabBar.vue'
  import TabBarItem from './tabbar/TabBarItem.vue'
    export default {
        name: 'MainTabBar',
      components:{
        TabBar,
        TabBarItem
      }
    }
</script>

<style>

</style>
