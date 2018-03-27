<template>
  <div>
  {{val}}
   <!-- 根组件路由占位, 将来通过url来控制页面的展示 -->
   <router-view></router-view>
  </div>
  
</template>


<script>
  export default{
       // 这是es6中对象定义函数方法的语法
       //组件内一个函数返回一个对象的形式
       data(){
           return {
               val:"vue项目脚手架环境测试"
           }
       } 
  }
</script> 

<style scoped>

</style>





