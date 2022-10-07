<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="wrapper">


    <el-space wrap>
      <router-link to="/">Home</router-link>
      <el-divider direction="vertical" />
      <router-link to="/about">About</router-link>
    </el-space>

    <router-view></router-view>

    <div class="footer">
      <HelloWorld msg="this is footer" />
    </div>
  </div>


</template>

<style scoped>
.wrapper {
  width: 1000px;
  margin: 20px auto;
}

.footer {
  background-color: blanchedalmond;
  padding: 20px;
  margin-top: 20px;
}
</style>
