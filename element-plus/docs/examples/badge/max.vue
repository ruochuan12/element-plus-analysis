<template>
  <el-badge :value="200" :max="99" class="item">
    <el-button size="small">comments</el-button>
  </el-badge>
  <el-badge :value="100" :max="10" class="item">
    <el-button size="small">replies</el-button>
  </el-badge>
</template>

<style scoped>
.item {
  margin-top: 10px;
  margin-right: 40px;
}
</style>
