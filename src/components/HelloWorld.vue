<template>
  <div class="hello">
    <el-popover
      ref="popover4"
      placement="right"
      width="400"
      trigger="click">
      <el-table>
        <el-table-column width="150" property="date" label="日期"></el-table-column>
        <el-table-column width="100" property="name" label="姓名"></el-table-column>
        <el-table-column width="300" property="address" label="地址"></el-table-column>
      </el-table>
    </el-popover>
    <el-button v-popover:popover4>click 激活</el-button>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  mounted: {
  },
  methods: {
  },
  data () {
    return {
      value2: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
