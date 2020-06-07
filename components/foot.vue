<!--   底部 -->
<template>
  <div class="footCont">
    <div class="fc_main">
        <ul class="linkBox">
         <li><a href="javascript:" target="_blank">关于江湖</a></li>
         <li><a href="javascript:" target="_blank">用户协议</a></li>
         <li><a href="javascript:" target="_blank">免责条款</a></li>
         <li><a href="javascript:" target="_blank">市场合作</a></li>
         <li><a href="javascript:" target="_blank">投诉反馈</a></li>
       </ul>
       <p class="lm_bottom">©投资江湖 All Rights Reserved 版权所有 皖ICP备05021383号</p>
       <p class="lm_bottom">免责声明：投资江湖仅提供投资者教育服务，所有嘉宾的建议仅代表其个人观点，仅供参考！</p>
    </div>
  </div>
</template>
<style scoped>
.footCont{
    background: #181c1f;
    padding: 20px 0;
    width: 100%;
}
.fc_main{
  width: 1200px;
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0 auto;
}
.linkBox{
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 10px;
}
.linkBox li:not(:last-child){
  margin-right: 15px;
  color: #fff;
}
.linkBox li a{
  color: #999;
}
.linkBox li a:hover{
    color: #ffb346;
}
.lm_bottom{
  text-align: center;
  color: #999;
  margin-bottom: 10px;
}

</style>