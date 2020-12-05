<template>
<div id="Repeat">
  <div class="Reletive">
    <div class="ab">
      <h1 class="font1">More than 2.9 million businesses and organizations use GitHub</h1>
      <ul class="one">
        <li v-for="(item,index) in top " :key="index" class="son">
          <img :src="item.img" alt="" class="IMG">
        </li>
      </ul>
      <ul class="one">
        <li v-for="(item,index) in bottom " :key="index" class="son">
          <img :src="item.img" alt="" class="IMG">
        </li>
      </ul>
    </div>

  </div>

</div>
</template>

<script>
export default {
name: "Repeat",
  data(){
  return{
    top:[
      {img: require('../assets/logo-01.png')},
      {img: require('../assets/logo-02.png')},
      {img: require('../assets/logo-03.png')},
      {img: require('../assets/logo-04.png')},
      {img: require('../assets/logo-05.png')},
      {img: require('../assets/logo-06.png')}
    ],
    bottom:[
    {img: require('../assets/logo-07.png')},
    {img: require('../assets/logo-08.png')},
    {img: require('../assets/logo-09.png')},
    {img: require('../assets/logo-10.png')},
    {img: require('../assets/logo-11.png')},
    {img: require('../assets/logo-12.png')},
    ],

  }
  }
}
</script>

<style scoped>
#Repeat{
  text-align: center;
  height: 300px;

}
.font1{
  font-size: 20px;
  color:  #9c9fa2;
  margin-bottom: 20px;
}
.IMG{
  /*width: 50px;*/
  /*height: 50px;*/
  filter: grayscale(100%);
  height: 25px;
  margin: 16px;
}
.one{
  display: flex;
  justify-content: space-around;
  /*text-align: center;*/
}

.ab{
  width: 980px;
  position: absolute;
  right: 0;
  left: 0;
  margin: auto;

}
.Reletive{
  position: relative;
}
.son{

}

</style>
