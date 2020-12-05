<template>
 <div id="vue1">
      <h6 class="First">{{messa1}}</h6>
      <h1 class="Secend">{{h1}}</h1>
      <p class="Thired">{{p1}}</p>
      <button class="Fourth">{{btn1}}</button>
 </div>
</template>

<script>
export default {
name: "vue1",
  data(){
  return{

  }
  },
  props:['messa1','h1','p1','btn1']

}
</script>

<style scoped>
#vue1{
  text-align: center;
  height: 300px;
  /*background-color: pink;*/
  font-size: 16px;
}
.First{
  font-size: 16px;
  color: #586069;
}
.Secend{
  font-size:48px ;
  padding: 16px 0 8px 0;
}
.Thired{
  font-size:20px ;
  color: #586069  ;
  width: 650px;
  position: absolute;
  right: 0;
  left: 0;
  margin: auto;

}
.Fourth{
  margin-top: 100px;
  padding: 20px 32px;
  border: 1px solid #1074e7;
  /*width: 152px;*/
  /*height: 24px;*/
  box-sizing: content-box;
  background-color: white;
  border-radius: 10px;
  color:#1074e7;
  font-weight: bolder;
  font-size: 16px;
}

</style>
