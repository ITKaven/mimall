<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="/imgs/logo-footer.png" alt="">
      <p>Kaven商城</p>
    </div>             
    <div class="footer-link">
      <a href="https://kaven.blog.csdn.net/" target="_blank">Kaven博客主页</a><span>|</span>
      <a href="https://github.com/ITKaven" target="_blank">Kaven'Github</a><span>|</span>
      <a href="https://kaven.blog.csdn.net/article/details/104233588" target="_blank">Java并发编程</a><span>|</span>
      <a href="https://kaven.blog.csdn.net/article/details/104109975" target="_blank">Java设计模式</a>
    </div>
    <div class="copyright">Copyright ©2019 <span class="domain">kaven.top</span> All Rights Reserved.</div>
  </div>
</template>
<script>
  export default{
    name:'nav-footer'
  }
</script>
<style lang="scss" scoped>
  .footer{
    height:234px;
    border-top:4px solid #FF6600;
    background-color:#333333;
    color:#999999;
    font-size:16px;
    text-align:center;
    .footer-logo{
      margin-top:46px;
      margin-bottom:31px;
      img{
        width:53px;
        height:36px;
        margin-bottom:13px;
      }
    }
    .footer-link{
      a{
        color:#999999;
        display:inline-block;
      }
      span{
        margin:0 10px;
      }
      margin-bottom:13px;
    }
    .copyright{
      .domain{
        color:#FF6600;
      }
    }
  }
</style>