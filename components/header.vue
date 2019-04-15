<template>
  <header>
    {{ msg }}
  </header>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      msg: '公共头部内容'
    }
  }
}
</script>

<style scoped>
header {
  display: block;
  height: 50px;
  line-height: 50px;
  text-align: center;
  background: #ccc;
}
</style>
