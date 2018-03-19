<template>
  <div class="layout">
    <el-container>
      <el-header>
        <HeaderContent></HeaderContent>
      </el-header>
      <el-container>
        <el-aside width="200px">
          <AsideContent class="sidebar-container"></AsideContent>
        </el-aside>
        <el-main>
          <MainContent class="main-container"></MainContent>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import AsideContent from './Layout/AsideContent'
import MainContent from './Layout/MainContent'
import HeaderContent from './Layout/HeaderContent'

export default {
  name: 'Layout',
  components: {
    AsideContent,
    MainContent,
    HeaderContent
  },
  methods: {
  },
  data () {
    return {
    }
  }
}
</script>

<style scoped>

</style>
