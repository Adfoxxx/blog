<template>
    <el-container :style="{height:'100%'}">
  <el-aside width="250px">
      <app-aside/>
      </el-aside>
  <el-main>
   <nuxt/>
      </el-main>
</el-container>
</template>
<script>
import AppAside from '@/components/admin/Aside'
export default {
    components: {AppAside}
}
</script>

<style lang="scss" scoped>
.admin-layout-wrap {
    width: 100%;
    height: 100vh;
}
</style>