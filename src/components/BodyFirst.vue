<template>
 <div id="BodyFirst">
   <div id="max">
     <img src="../assets/01.svg" alt="" class="Img">
     <div class="Reletive">
       <div class="Center">
         <div class="left">
           <div class="son">
           <h2>Get started with GitHub Enterprise</h2>
           <p class="p">Take collaboration to the next level with security and administrative features built for teams.</p>
           </div>
         </div>
         <div class="out">
           <div class="in">
             <img src="../assets/02.svg" alt="" class="Img2">
             <h2 class="H2">Enterprise</h2>
             <h3 class="H3">Deploy to your environment or the cloud.</h3>
             <button class="Btn">Start a free trail</button>
           </div>
         </div>
         <div class="out">
           <div class="in">
             <img src="../assets/03.svg" alt="" class="Img2">
             <h2 class="H2">Talk to us</h2>
             <h3 class="H3">Need help?</h3>
             <button class="Btn1 Btn">Contact Salse ></button>
           </div>
         </div>
<!--         <div></div>-->
       </div>
     </div>

   </div>
 </div>
</template>

<script>
export default {
  name: "BodyFirst"
}
</script>

<style scoped>
#max{
  height: 600px;
  text-align: center;
}
.Img{
  width: 450px;
  height: 190px;
  position: absolute;
  top: 650px;
  left: 1000px;
}
.Center{
  width: 1200px;
  height: 320px;
  /*border: 1px grey solid;*/
  border-radius: 5px;
  border:none;
  box-shadow: 0 5px 5px 5px #f5f6f7;
  /*background-color: pink;*/
  position: absolute;
  left: 0;
  right: 0;
  top: 115px;
  margin: auto;
  box-sizing: border-box;
  padding: 50px 0 50px 50px ;
  display: flex;
  justify-content: space-around;
}
.Reletive{
  position: relative;

}
.out{
  width: 350px;
  /*background-color: pink;*/
  padding: 16px;
  font-size: 14px;
  /*margin-left: 20px;*/

}
.left{
  /*padding: 20px;*/
  width: 700px;
  font-size:20px ;
  text-align: left;

}
.son{
  width: 350px;
}
.p{
  margin-top:20px ;
  color: #586069;
}
.H2{
  font-size: 16px;
}
.H3{
  font-size: 12px;
  /*font-weight:3;*/
  margin-top: 10px;
  color: #586069;
}
.Img2{
  width: 50px;
  height: 50px;
  margin-bottom: 10px;
}
.Btn{
  width: 150px;
  height: 50px;
  border: none;
  border-radius: 5px;
  margin-top: 20px;
  background-color:#0077e5 ;
  color: white;
}
/*.Btn:nth-child(1){*/
/*  background-color:#0077e5 ;*/
/*  color: white;*/
/*}*/
.Btn1 {
  background-color: white;
  color:#0077e5 ;
  border: 1px solid #0077e5 ;
}
</style>
