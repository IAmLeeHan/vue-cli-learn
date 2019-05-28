<template>
  <div class="app">
    <a href="">hello world!!!</a>
    <HelloWorld></HelloWorld>
  </div>
</template>

<style lang = "scss">

</style>

<script>
  // 引入hello world组件
  import HelloWorld from "@/components/HelloWorld"//@符号指的是当前src路径
  export default {
    components:{//注册子组件
      HelloWorld
    }
  }
</script>