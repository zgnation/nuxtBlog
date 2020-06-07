<!--导航 -->
<template>
  <header>
    <div id="myNav">
      <logo></logo>
      <el-menu
        :default-active="activeIndex"
        class="navBar"
        mode="horizontal"
        @select="handleSelect"
      >
        <el-menu-item index="1">
          <nuxt-link to="./">首页</nuxt-link>
        </el-menu-item>
        <el-menu-item index="2">
          <nuxt-link to="./summary">个人总结</nuxt-link>
        </el-menu-item>
        <el-menu-item index="3">
          <nuxt-link to="./share">插件分享</nuxt-link>
        </el-menu-item>
        <el-menu-item index="4">
          <nuxt-link to="./interaction">
            交流讨论</nuxt-link>
        </el-menu-item>
      </el-menu>
    </div>
  </header>
</template>



<script>
import logo from "./logo";

export default {
  name: "myNav",
  components: {
    logo
  },
  data() {
    return {
      activeIndex: "1"
    };
  },
  methods: {
    handleSelect(key, keyPath) {
      this.activeIndex = key;
    }
  }
};
</script>

<style  scoped>
header {
  width: 100%;
  border-bottom: 1px solid #e6e6e6;
}
#myNav {
  width: 1200px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.navBar .el-menu-item{
  padding:0;
}
.navBar .el-menu-item a{
  display: block;
  padding: 0 20px;
}
</style>