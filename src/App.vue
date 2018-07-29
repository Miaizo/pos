<template>
  <div id="app">
      <left-nav></left-nav>
      <div class="main">
          <router-view></router-view>
      </div>   
  </div>
</template>

<script>
import leftNav from "@/components/common/leftNav";
export default {
  name: "App",
  components: {
    leftNav
  }
};
</script>

<style>
.main {
  float: left;
  width: 95%;
  background-color: #ccc;
  height: 100%;
  overflow: hidden;
}
</style>
