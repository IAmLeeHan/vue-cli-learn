<template>
  <div class="hello">
    <a href="" @click = "clickMsg">{{msg}}</a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',//方便虚拟dom快速找到此组件
  data(){
    return {
      msg:"我爱中国！"
    }
  },
  methods:{
    clickMsg(e){
      e.preventDefault();
      console.log(11111111)
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

a {
  color: red;
}
</style>
