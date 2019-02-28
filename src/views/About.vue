<template>
  <div class="about">
    <h1>This is a about page</h1>
    <el-date-picker
      v-model="value1"
      type="datetime"
      placeholder="选择日期时间">
    </el-date-picker>
  </div>
</template>
<script>
export default {
  data () {
    return {
      value1: ''
    }
  }
}
</script>
