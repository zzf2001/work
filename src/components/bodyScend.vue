<template>
  <div id="bodyScend">
    <div class="reletive">
      <div class="top">
        <div class="left">
          <div>
            <h3  class="font1">Code security</h3>
            <p class="font2">Prevent problems before they happen. Protected branches, signed commits, and required status checks protect your work and help you maintain a high standard for your code.</p>
          </div>
          <div>
            <h3  class="font1">Access controlled</h3>
            <p class="font2">Encourage teams to work together while limiting access to those who need it with granular permissions and authentication through SAML/SSO and LDAP.</p>
        </div>
        </div>
        <div class="right">
          <img :src="picture" alt="" class="img">
        </div>
      </div>
      <div class="button">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64" class="mr-4" width="64px"><path d="M27 13h-9a1 1 0 0 0 0 2h9a1 1 0 0 0 0-2zm15-1a1 1 0 0 0-1 1v2a1 1 0 0 0 2 0v-2a1 1 0 0 0-1-1zm4 0a1 1 0 0 0-1 1v2a1 1 0 0 0 2 0v-2a1 1 0 0 0-1-1zM27 28h-9a1 1 0 0 0 0 2h9a1 1 0 0 0 0-2zm15 3a1 1 0 0 0 1-1v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 1 1zm4 0a1 1 0 0 0 1-1v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 1 1z" fill="#23292f"></path><path d="M50 44h-1a13 13 0 0 0-4.68-9H48a3 3 0 0 0 3-3v-6a3 3 0 0 0-3-3h-5v-3h5a3 3 0 0 0 3-3v-6a3 3 0 0 0-3-3H16a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h5v3h-5a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h11.72a13 13 0 0 0-3.79 5.21A7 7 0 0 0 13.28 44 6 6 0 0 0 14 56h36a6 6 0 0 0 0-12zM15 17v-6a1 1 0 0 1 1-1h32a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H16a1 1 0 0 1-1-1zm8 3h18v3H23zm-7 13a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h32a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-7a12.9 12.9 0 0 0-10 0H16zm34 21H14a4 4 0 1 1 .09-8 1 1 0 0 0 1-.83 5 5 0 0 1 8.6-2.55 1 1 0 0 0 1.7-.42A11 11 0 0 1 47 45a1 1 0 0 0 1 1h2a4 4 0 0 1 0 8z" fill="#23292f"></path></svg>
        <div class="size">
          <h1 class="font3">Hosted where you need it</h1>
          <p class="font4">Securely and reliably host your work on GitHub using GitHub Enterprise Cloud. Or deploy GitHub Enterprise Server in your own data centers or in a private cloud using Amazon Web Services, Azure, or Google Cloud Platform.</p>
          <p><a href="" class="A">Compare plans →</a></p>
          <p><a href="" class="A">Contact Sales for more information →</a></p>
        </div>


      </div>
  </div>
  </div>
</template>

<script>
 export default {
name: "bodyScend",
  data(){
  return{
    picture:require('../assets/business.png'),

  }
  }
}
</script>

<style scoped>
#bodyScend{
  height: 800px;
}
.top{
  display: flex;
  justify-content: space-around;
  width: 1000px;
  position: absolute;
  right: 0;
  left: 0;
  margin: auto;
}
.reletive{
  position: relative;
}
.img{
  width: 458px;
  height: 239px;
  margin-top: 40px;
}
.left{
  width: 410px;
  padding: 40px;
}
.right{
  padding-left:10px ;
}
.font1{
  font-size: 20px;
  color: #24292e;
  /*margin-top: 20px;*/
  font-weight: 400;
}
.font2{
  font-size: 12px;
  color: #586069;
  margin-top: 10px;
  margin-bottom: 20px;
}
.button{
  padding: 36px 24px 24px;
  width: 520px;
  height: 165px;
  position: absolute;
  right: 0;
  left: 0;
  top: 350px;
  margin:auto;
  border: 1px solid #e1e4e8;
  border-radius: 5px;
  display: flex;
  /*flex-direction:row ;*/
}
.mr-4{
  width: 64px;
  height: 64px;
}
.size{
  width: 425px;
  padding: 0 15px;
}
.font3{
  font-size: 16px;
  color: #24292e;
  font-weight: 400;
  margin: 0 15px 15px;
}
.font4{
  font-size: 12px;
  color: #586069;
  margin: 0 15px 15px;

}
.A{
  margin: 0 15px 15px;
  font-size: 14px;
  color: #0366d6;
}

</style>
