<template>
  <a class="logoWrapper" href="/">
      <div class="logo">
        <h1>个人博客</h1>
      </div>
      <!-- <div class="header_txt">
          <span>个人前端总结——每天进步一点点</span>
      </div> -->
  </a>
</template>
<style>
  .logoWrapper{
      display: flex;
      align-items: flex-end;
      justify-content: center;
      text-decoration: none;
  }
   .logo{
    width:54px;
    height: 54px;
    background: url('../assets/images/logo.png') no-repeat center center;
    background-size: 100% 100%;
  }
   .logo h1{
    display: none;
  }
  .header_txt{
      color: #999;
      font-size: 13px;
  }
</style>

<script>
export default {
  name: "logo",
}
</script>
