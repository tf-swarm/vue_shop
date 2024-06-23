<template>
 <div class="home">
    <div class="home-body">
      <h4 class="title">欢迎来到电商后台管理系统</h4>
      <p class="des">Powered by Django with ElementUI</p>
    </div>
 </div>
</template>
<style lang="less" scoped>
.home{
  width: 100%;
  height: 100%;
  background: url("../assets/welcome.jpg") no-repeat;
  background-size: 100% 100%;
}
.home-body{
  height: 100%;
  background-color: rgba(0,0,0,.6);
  color: #fff;
  text-align: center;
  padding: 100px;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
.title{
  font-size: 32px;
  font-weight: 700;
  line-height: 60px;
}
.des{
  font-size: 14px;
  margin: 40px 0;
  color: #ffe;
}
</style>
