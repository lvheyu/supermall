<template>
  <div id="tab-bar" class="tab-bar">
  <slot></slot>
  </div>
</template>

<script>
export default {
  name: "TabBar"
}
</script>

<style scoped>
/*定义tab-bar样式*/
#tab-bar {
  display:flex;
  background-color: #f6f6f6;
  /*tabbar移到底部*/
  position: fixed;
  left:0;
  right:0;
  bottom:0;

  /*x水平移动,y垂直移动,高度，rgba(颜色，透明度)*/
  box-shadow: 0 -3px 1px rgba(100,100,100,.1);
}

</style>
