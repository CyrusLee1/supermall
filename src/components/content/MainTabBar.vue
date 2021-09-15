<template>
  <tar-bar>
    <tar-bar-item path="/home" :active-style="{color: 'red'}">
      <img slot="item-icon" src="~@/assets/img/tabbar/home.svg" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/home-active.svg" alt="">
      <div slot="item-text">首页</div>
    </tar-bar-item>
    <tar-bar-item path="/category" :active-style="{color: 'red'}">
      <img slot="item-icon" src="~@/assets/img/tabbar/fenlei.svg" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/fenlei-active.svg" alt="">
      <div slot="item-text">分类</div>
    </tar-bar-item>
    <tar-bar-item path="/cart" :active-style="{color: 'red'}">
      <img slot="item-icon" src="~@/assets/img/tabbar/gouwu.svg" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/gouwu-active.svg" alt="">
      <div slot="item-text">购物车</div>
    </tar-bar-item>
    <tar-bar-item path="/profile" :active-style="{color: 'red'}">
      <img slot="item-icon" src="~@/assets/img/tabbar/profile.svg" alt="">
      <img slot="item-icon-active" src="~@/assets/img/tabbar/profile-active.svg" alt="">
      <div slot="item-text">我的</div>
    </tar-bar-item>
  </tar-bar>
</template>

<script>
import TarBar from "@/components/common/tabbar/TarBar";
import TabBarItem from "@/components/common/tabbar/TabBarItem";
export default {
  name: 'MainTabBar',
  components: {
    TarBar,
    TarBarItem
  }
}
</script>

<style scoped>

</style>
