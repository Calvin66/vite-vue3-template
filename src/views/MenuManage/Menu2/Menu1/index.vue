<!--
 * @Author: Calvin
 * @Date: 2021-12-07 14:42:24
 * @FilePath: \src\views\MenuManage\Menu2\Menu1\index.vue
 * @Description: 
-->
<template>
  <div class="menu-container">
    <div v-for="i in 200" :key="i">{{ i }}二级菜单__一级菜单</div>
  </div>
</template>

<script>
export default {
  setup() {}
}
</script>

<style lang="scss" scoped>
.menu-container {
  background: #fff;
}
</style>
