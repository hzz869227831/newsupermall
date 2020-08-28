<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="red">
      <img slot="item-icon" src="../../assets/img/tabbar/home.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/home_active.png" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="red">
      <img slot="item-icon" src="../../assets/img/tabbar/classify.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/classify_active.png" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="red">
      <img slot="item-icon" src="../../assets/img/tabbar/shop.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/shop_active.png" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="red">
      <img slot="item-icon" src="../../assets/img/tabbar/me.png" alt="">
      <img slot="item-icon-active" src="../../assets/img/tabbar/me_active.png" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import tabBar from "../../components/tabbar/tabBar";
  import TabBarItem from "../../components/tabbar/tabBarItem";
  export default {
  name: "MainTabBar",
    components: {
      TabBarItem,
      tabBar
    }
  }
</script>

<style scoped>

</style>