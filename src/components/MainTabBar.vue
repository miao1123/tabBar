<template>
  <tab-bar>
      <tab-bar-item path="/home" activeColor="#d63823">
        <template #item-icon><img src="../assets/img/home.svg" alt=""></template>
        <template #item-icon-active><img src="../assets/img/home-active.svg" alt=""></template>
        <template #item-text><div>首页</div></template>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="#d63823">
        <template #item-icon><img src="../assets/img/category.svg" alt=""></template>
        <template #item-icon-active><img src="../assets/img/category-active.svg" alt=""></template>
        <template #item-text><div>分类</div></template>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="#d63823">
        <template #item-icon><img src="../assets/img/shoppingcar.svg" alt=""></template>
        <template #item-icon-active><img src="../assets/img/shoppingcar-active.svg" alt=""></template>
        <template #item-text><div>购物车</div></template>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="#d63823">
        <template #item-icon><img src="../assets/img/usercenter.svg" alt=""></template>
        <template #item-icon-active><img src="../assets/img/usercenter-active.svg" alt=""></template>
        <template #item-text><div>我的</div></template>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from './tabbar/TabBar'
import TabBarItem from './tabbar/TabBarItem'
export default {
  name: 'MainTabBar',
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style>

</style>