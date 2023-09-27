<script lang="ts" setup>
</script>

<template>
      <el-container class="layout">
      <el-header class="header" style="display: flex; align-items: center;">
        <div class="logo">
          <img src="https://pixto.whatalife.top/api/v1/pix/9f/9f335a806f1fc84d263400307534a375.jpg" alt="logo" style="width: 40px;">
        </div>
        <span style="color: white;padding: 15px; font-size: 25px; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">toyile</span>
      </el-header>
      <el-container>
        <el-aside class="aside" width="150px">Aside</el-aside>
        <el-main class="main">Main</el-main>
      </el-container>
      <el-footer class="footer">
        <div style="display: flex; justify-content: center; padding: 15px;">
          <span style="color: aliceblue;">Welcom to Toyile!!</span>
        </div>
      </el-footer>
    </el-container>
</template>

<style scoped>
.layout{
    height: 100%;
    width: 100%;
}
.aside{
    height: 80vh;
    background-color: #FF6969;
}
.header{
    height: 10vh;
    background-color: #C70039;
}
.main{
  background-color: #FFF5E0;
}

.footer{
  background-color: #141E46;
  height: 10vh;
}
</style>