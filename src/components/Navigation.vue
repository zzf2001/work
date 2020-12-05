<template>
  <div id="Navigation" :style="note" class="Nav">
    <div class="Navtop">
    <ul class="A">
      <svg height="32" class="octicon octicon-mark-github text-white" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
      <li v-for="item in zzzf" v-bind:key="item" class="B">
        {{item}}
      </li>
    </ul>
    <input type="text" class="Iput" placeholder="Seach GitHub" >
    <button class="Btn1 Btn">sign in</button>
    <button class="Btn2 Btn">sign up</button>
      <div class="Botton">
        <div class="NavLefe">
          <h1 class="font1">Built for developers</h1>
          <h3 class="font2">GitHub is a development platform inspired by the way you work. From <span class="SPAN"><a href="" class="Http">open source</a></span> to <span class="SPAN"><a href="" class="Http">business</a></span>, you can host and review code, manage projects, and build software alongside 50 million developers.</h3>
        </div>
        <div class="NavRight">
          <div class="Repeat" v-for="name in Nav" :key="name">
<!--            <h3>{{name}}</h3>-->
            <label>{{name}}</label>
            <input type="text" class="Iput2">
          </div>
          <p>Make sure it's at least 15 characters OR <span class="SP">at least 8 characters including a number and a lowercase letter.</span><a href="" class="A1">Learn more.</a></p>
          <button class="Iput3">Sign up for GitHub</button>
          <p class="p2">By clicking “Sign up for GitHub”, you agree to our <a href="" class="A1">Terms of Service</a> and <a href="" class="A1">Privacy Statement.</a> We’ll occasionally send you account related emails.</p>
        </div>
      </div>
  </div>
  </div>

</template>

<script>
export default {
name: "Navigation",
data(){
  return{
    zzzf:['Why GitHub?',
      'Team',
      'Enterprise',
      'Explore',
      'Marketplace',
      'Pricing'],
    note:{
      backgroundImage:"url("+require("../assets/nav.svg"),
      backgroundRepeat:"no-repeat",
      backgroundSize:"1650px"
    },
    Nav:['Usename','Email', 'Password'],
    // Img:'./'
  }
}
}
</script>
<style scoped>
#Navigation{
  display: flex;
  flex-direction: row;
  position: relative;
}
.Navtop{
  display: flex;
  flex-direction: row;
}
.A{
  display: flex;
  flex-direction:row;
}
.B{
  margin: 25px 15px;

}
.Nav{
  background-color: #2b3137;
  color: white;
  height: 700px;
}
.Btn{
  height: 35px;
  /*padding: 0 55px;*/
}
.Iput{
  height: 35px;
  background-color:#24292e ;
  border: none;
  padding: 0 5px;
  margin: 20px 15px 0 250px;
  width: 250px;
  color: white;
  background-image: url("../assets/little.svg");
  background-repeat: no-repeat;
  background-position-x: 230px;
  background-position-y: 10px;
}
.Navtop {
  position: absolute;
  right: 0;
  left: 0;
  margin: auto;
  width: 1400px;
}
.octicon{
  color: white;
  fill: white;
  margin: 20px;
}
.Btn{
  margin: 20px 15px;
  background-color: transparent;
  border-style:none ;
  font-size: 16px;
  color: white;
  padding: 5px;

}
.Btn2{
  border:1px white solid;
  border-radius: 5px;

}
.Botton{
  width: 1000px;
  height: 400px;
  display: flex;
  flex-direction:row ;
  position: absolute;
  top: 75px;
  right: 0;
  left: 0;
  margin: auto;
}
.NavLefe{
  /*padding: 80px 0 0 80px;*/
  padding-top: 80px;
  font-size: 16px;
  width: 500px;
}
.NavRight{
  margin-left: 40px;
  width: 480px;
  background-color: white;
  height: 530px;
  border-radius: 10px;
  box-sizing: border-box;
  padding:20px ;
}
.Repeat{
  color: black;
  font-size: 14px;
  padding: 10px 10px;
  width: 400px;
  font-weight: bolder;
}
.font1{
  font-size: 64px;
  /*font-family:;*/
  margin-bottom:30px ;

}
.font2{
  font-size: 19px;
  color: #9c9fa2;
  line-height: 30px;
  /*font-family: 黑体;*/
}
.Http{
  /*text-decoration: #9c9fa2  underline ;*/
  color: white;
}
.SPAN{
  padding-bottom: 2px;
  border-bottom: 1px solid  #9c9fa2;
}
span:hover{
  border-bottom: 1px solid  white;
}
.Iput2{
  width: 400px;
  height: 25px;
  padding:10px ;
  font-size: 16px ;
  border-radius: 5px;
  border: #e1e4e8 1px solid ;
  margin-top: 5px;
}
p{
  color: black;
  margin-left: 10px;
  font-size: 12px;
  line-height: 20px;
}
.SP{
  color:#22863a;
}
.A1{
  /*text-decoration: underline;*/
  color: #0366d6;
}
.A1:hover{
  text-decoration: underline;
}
.Iput3{
  width: 425px;
  height: 70px;
  padding:20px;
  background-color:#2ebc4f;
  margin-left:10px ;
  border-radius: 5px;
  color: white;
  font-size: 16px;
  margin-bottom: 40px;
  margin-top: 20px;
  border: none;
}
.p2{
  color: #6a737d;
}

</style>
