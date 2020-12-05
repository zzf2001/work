<template>
  <div id="robot">
    <div class="big">
      <div class="son">
        <div class="left">
          <img :src="dizhi" alt="" class="img">
        </div>
        <div class="right">
          <div class="repeat" v-for="(item,index) in a" :key="index">
            <h3 class="one">{{item.h}}</h3>
            <p class="two">{{item.p}}<span><a href="" class="thire">{{item.a}}</a></span></p>
            <img :src="item.tu" alt="" class="Img">

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "robot",
  data(){
  return {
    dizhi:require('../assets/04.svg'),
    a:[
      {
        h:'Write better code',
        p:'Collaboration makes perfect. The conversations and code reviews that happen in pull requests help your team share the weight of your work and improve the software you build.',
        a:'Learn about code review.',
        tu:require('../assets/number1.svg'),

      },
      {
        h:'Manage your chaos',
        p:'Take a deep breath. On GitHub, project management happens in issues and project boards, right alongside your code. All you have to do is mention a teammate to get them involved.',
        a:'Learn about project management.',
        tu:require('../assets/number2.svg'),

      },
      {
        h:'Find the right tools',
        p:'Browse and buy apps from GitHub Marketplace with your GitHub account. Find the tools you like or discover new favorites—then start using them in minutes.',
        a:' Learn about integrations.',
        tu:require('../assets/number3.svg'),

      },
    ],
    // methods:{
    //   enter(){
    //
    //     let a;
    //     a = document.getElementsByClassName('Img')
    //     a.style.opacity="0"
    //   } ,
    //   leave:function (){
    //     let a;
    //     a = document.getElementsByClassName('Img')
    //     a.style.opacity="1"
    //   }
    // }
  }

  }
}
</script>

<style scoped>
  #robot{
    /*background-size: px;*/
    height: 700px;

    background-repeat: no-repeat;
    /*background-image: url();*/
  }
  .big{
    position: relative;
  }
  .son{
    width: 1248px;
    position: absolute;
    right: 0;
    left: 0;
    margin: auto;
    padding: 0  16px;
    display: flex;
    justify-content: space-around;
  }
  img{
    /*width: 680px;*/
    height: 634px;
  }
  .repeat{
    padding: 24px;
    height: 116px;
    width: 436px;
    /*background-color: pink;*/
    box-shadow: 0 0 5px 5px white;
    border: 1px solid white;
    margin-top:2px ;

  }
  .Img{
    width: 187px;
    height: 189px;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    margin: auto;
    opacity:0;


  }
  .repeat:hover> img{
    opacity:1;
    transition: all 1s;
  }
  .repeat:hover{
    box-shadow: 0 0 5px 5px #f5f6f7;
    opacity:1;
    border-radius: 5px;
    border: 1px solid #ccd4c8;


  }
  .one{
    font-size: 20px;
  }
  .two{
    font-size: 14px;
    width: 395px;
    margin-top: 7px;

  }
  .thire{
    font-size: 14px;
    text-decoration: underline;
    color: #0366d6;
  }

</style>
