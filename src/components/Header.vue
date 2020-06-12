<template>
  <div class="header">
    <router-link  :to="{name:'root'}">
      <img src="../assets/cnodejs_light.svg" alt="">
    </router-link>
<!--    <ul>-->
<!--      <li><a href="/">首页</a></li>-->
<!--      <li><a href="#">新手入门</a></li>-->
<!--      <li><a href="#">API</a></li>-->
<!--      <li><a href="#">关于</a></li>-->
<!--      <li><a href="#">注册</a></li>-->
<!--      <li><a href="#">登录</a></li>-->
<!--    </ul>-->
  </div>
</template>

<script>
  export default {
    name: 'Header'
  }
</script>

<style scoped>
  .header{
    background-color:#5a5555 ;
    height: 50px;
    position: relative;
  }
  img{
    max-width: 120px;
    /*margin-left: 50px;*/
    /*margin-top: 10px;*/
    position:absolute;
    top:0;
    bottom:0;
    left:0;
    right:0;
    margin:auto;
  }
  ul{
    list-style: none;
    float: right;
    margin: 4px;
  }
  li{
    display: inline-block;
    padding: 10px 15px;
  }
  a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
  }
</style>
