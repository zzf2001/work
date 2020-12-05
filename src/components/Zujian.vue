<template>
<div id="Zujian">
  <h1 class="font1">See how the world's leading companies use GitHub Enterprise.</h1>
  <div>
    <div class="reletive">
      <div class="abs">
        <div class="repeat" v-for="(item,index) in A" :key="index">
          <div class="bor">
          <img :src="item.img" alt="" class="img">
            <div class="jiantou">↗</div>
            <h3 class="font3">{{item.H1}}</h3>
          <p class="font2">{{item.P}}</p>
          </div>
          <h3><a href="" class="A">{{item.A}}</a></h3>
        </div>
      </div>
    </div>
  </div>

</div>
</template>

<script>
export default {
name: "Zujian",
  data(){
  return{
    A:[
      {
      img:require('../assets/See-1.jpg'),
      H1:'MGM Resorts International',
      P:'Hospitality',
      A:'Read more     →',
    },
      {
        img:require('../assets/See-2.jpg'),
        H1:'Nationwide',
        P:'Insurance',
        A:'Read more    →',
      },
      {
        img:require('../assets/See-3.jpg'),
        H1:'SAP',
        P:'Business Software',
        A:'Read more     →',
      },
      {
        img:require('../assets/See-4.jpg'),
        H1:'Spotify',
        P:'Technology / Streaming',
        A:'Read more     →',
      },

    ]
  }
  },
  // props:
}
</script>

<style scoped>
  #Zujian{
    text-align: center;
    height: 500px;
  }

  .font1{
    font-size: 14px;
    color: #586069;
    margin-bottom: 10px;

  }

  .reletive{
    position: relative;
  }
  .abs{
    width: 1250px;
    display: flex;
    justify-content: space-around;
    position: absolute;
    right: 0;
    top: 0;
    left: 0;
    margin: auto;
  }
.repeat{
  padding: 16px;
  border:1px solid #f9f9f9;
  text-align: left;
  box-shadow: 0 0 5px 5px #f9f9f9;
  border-radius: 10px;
}
.bor{
  position: relative;

  border-bottom: 1px #e1e4e8 solid;
  height: 285px;
}
.img{
  width: 250px;
  height: 200px;
  border:1px solid white;
  border-radius: 10px;
  margin-bottom:16px ;
}
.font2{
  font-size: 12px;
  color: #586069;
  margin-top: 5px;
}
.font3{
  font-size: 16px;
  color: #24292e;
}
.A{
  font-size: 14px;
  color: #3b96eb;
}
.jiantou{
  background-color: #0366d6;
  position: absolute;
  right: 10px;
  top:10px;
  height: 40px;
  width: 40px;
  padding:  10px 10px  15px 15px;
  font-size:35px ;
  color: white;
  border-radius: 5px;
  border:1px #0366d6 solid ;
  opacity:0;
}
.repeat:hover> div{
  opacity:1;
  transition: all 1s;
}
</style>
