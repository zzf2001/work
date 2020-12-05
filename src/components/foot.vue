<template>
<div id="foot">
  <div class="max">
    <div class="top">
        <p class="H">Get started for free — join the millions of developers already using GitHub to share their code, work together, and build amazing things.</p>
      <div>
        <div class="NavRight">
          <div class="Repeat" v-for="name in Nav" :key="name">
            <label>{{name}}</label>
            <input type="text" class="Iput2">
          </div>
          <button class="Iput3">Sign up for GitHub</button>
      </div>
        <p class="H2">By clicking “Sign up for GitHub”, you agree to our <a href="" class="topa">terms of service</a> and <a href="" class="topa">privacy statement.</a> We’ll occasionally send you account related emails.</p>

      </div>
    </div>
    <div class="mid">
      <div class="reletive">
        <div class="abs">
          <div class="midleft">
            <svg height="30" class="octicon octicon-logo-github" viewBox="0 0 45 16" version="1.1" width="84" aria-hidden="true"><path fill-rule="evenodd" d="M18.53 12.03h-.02c.009 0 .015.01.024.011h.006l-.01-.01zm.004.011c-.093.001-.327.05-.574.05-.78 0-1.05-.36-1.05-.83V8.13h1.59c.09 0 .16-.08.16-.19v-1.7c0-.09-.08-.17-.16-.17h-1.59V3.96c0-.08-.05-.13-.14-.13h-2.16c-.09 0-.14.05-.14.13v2.17s-1.09.27-1.16.28c-.08.02-.13.09-.13.17v1.36c0 .11.08.19.17.19h1.11v3.28c0 2.44 1.7 2.69 2.86 2.69.53 0 1.17-.17 1.27-.22.06-.02.09-.09.09-.16v-1.5a.177.177 0 00-.146-.18zM42.23 9.84c0-1.81-.73-2.05-1.5-1.97-.6.04-1.08.34-1.08.34v3.52s.49.34 1.22.36c1.03.03 1.36-.34 1.36-2.25zm2.43-.16c0 3.43-1.11 4.41-3.05 4.41-1.64 0-2.52-.83-2.52-.83s-.04.46-.09.52c-.03.06-.08.08-.14.08h-1.48c-.1 0-.19-.08-.19-.17l.02-11.11c0-.09.08-.17.17-.17h2.13c.09 0 .17.08.17.17v3.77s.82-.53 2.02-.53l-.01-.02c1.2 0 2.97.45 2.97 3.88zm-8.72-3.61h-2.1c-.11 0-.17.08-.17.19v5.44s-.55.39-1.3.39-.97-.34-.97-1.09V6.25c0-.09-.08-.17-.17-.17h-2.14c-.09 0-.17.08-.17.17v5.11c0 2.2 1.23 2.75 2.92 2.75 1.39 0 2.52-.77 2.52-.77s.05.39.08.45c.02.05.09.09.16.09h1.34c.11 0 .17-.08.17-.17l.02-7.47c0-.09-.08-.17-.19-.17zm-23.7-.01h-2.13c-.09 0-.17.09-.17.2v7.34c0 .2.13.27.3.27h1.92c.2 0 .25-.09.25-.27V6.23c0-.09-.08-.17-.17-.17zm-1.05-3.38c-.77 0-1.38.61-1.38 1.38 0 .77.61 1.38 1.38 1.38.75 0 1.36-.61 1.36-1.38 0-.77-.61-1.38-1.36-1.38zm16.49-.25h-2.11c-.09 0-.17.08-.17.17v4.09h-3.31V2.6c0-.09-.08-.17-.17-.17h-2.13c-.09 0-.17.08-.17.17v11.11c0 .09.09.17.17.17h2.13c.09 0 .17-.08.17-.17V8.96h3.31l-.02 4.75c0 .09.08.17.17.17h2.13c.09 0 .17-.08.17-.17V2.6c0-.09-.08-.17-.17-.17zM8.81 7.35v5.74c0 .04-.01.11-.06.13 0 0-1.25.89-3.31.89-2.49 0-5.44-.78-5.44-5.92S2.58 1.99 5.1 2c2.18 0 3.06.49 3.2.58.04.05.06.09.06.14L7.94 4.5c0 .09-.09.2-.2.17-.36-.11-.9-.33-2.17-.33-1.47 0-3.05.42-3.05 3.73s1.5 3.7 2.58 3.7c.92 0 1.25-.11 1.25-.11v-2.3H4.88c-.11 0-.19-.08-.19-.17V7.35c0-.09.08-.17.19-.17h3.74c.11 0 .19.08.19.17z"></path></svg>
          </div>
          <div>
            <ul>
              <h2 class="midh2">Product</h2>
              <li class="midli"><a href="">Features</a></li>
              <li class="midli"><a href="">Security</a></li>
              <li class="midli"><a href="">Team</a></li>
              <li class="midli"><a href="">Enterprise</a></li>
              <li class="midli"><a href="">Customer stories</a></li>
              <li class="midli"><a href="">The ReadME Project</a></li>
              <li class="midli"><a href="">Pricing</a></li>
              <li class="midli"><a href="">Resources</a></li>
              <li class="midli"><a href="">Roadmap</a></li>
            </ul>
          </div>
          <div>
            <ul>
              <h2 class="midh2">Platform</h2>
              <li class="midli"><a href="">Developer API</a></li>
              <li class="midli"><a href="">Partners</a></li>
              <li class="midli"><a href="">Atom</a></li>
              <li class="midli"><a href="">Electron</a></li>
              <li class="midli"><a href="">GitHub Desktop</a></li>
            </ul>
          </div>
          <div>
            <ul>
              <h2 class="midh2">Support</h2>
              <li class="midli"><a href="">Help</a></li>
              <li class="midli"><a href="">Community Forum</a></li>
              <li class="midli"><a href="">Professional Services</a></li>
              <li class="midli"><a href="">Learning Lab</a></li>
              <li class="midli"><a href="">Status</a></li>
              <li class="midli"><a href="">Contact GitHub</a></li>
            </ul>
          </div>
          <div>
            <ul>
              <h2 class="midh2">Company</h2>
              <li class="midli"><a href="">About</a></li>
              <li class="midli"><a href="">Blog</a></li>
              <li class="midli"><a href="">Careers</a></li>
              <li class="midli"><a href="">Press</a></li>
              <li class="midli"><a href="">Social Impact</a></li>
              <li class="midli"><a href="">Shop</a></li>
            </ul>
          </div>

        </div>
      </div>






















    </div>
    <div class="buttom">
      <div class="absbut">
        <div class="reletive">
          <ul >
            <li>© 2020 GitHub, Inc</li>
            <a href="" class="btna">Terms</a>
            <a href="" class="btna">Privacy</a>
            <a href="" class="btna">Site Map</a>
            <a href="" class="btna">What is Git?</a>
          </ul>
          <div class="footright">
            <span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 273.5 222.3" class="d-block" height="18"><path d="M273.5 26.3a109.77 109.77 0 0 1-32.2 8.8 56.07 56.07 0 0 0 24.7-31 113.39 113.39 0 0 1-35.7 13.6 56.1 56.1 0 0 0-97 38.4 54 54 0 0 0 1.5 12.8A159.68 159.68 0 0 1 19.1 10.3a56.12 56.12 0 0 0 17.4 74.9 56.06 56.06 0 0 1-25.4-7v.7a56.11 56.11 0 0 0 45 55 55.65 55.65 0 0 1-14.8 2 62.39 62.39 0 0 1-10.6-1 56.24 56.24 0 0 0 52.4 39 112.87 112.87 0 0 1-69.7 24 119 119 0 0 1-13.4-.8 158.83 158.83 0 0 0 86 25.2c103.2 0 159.6-85.5 159.6-159.6 0-2.4-.1-4.9-.2-7.3a114.25 114.25 0 0 0 28.1-29.1" fill="currentColor"></path></svg></span>

            <span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15.3 15.4" class="d-block" height="18"><path d="M14.5 0H.8a.88.88 0 0 0-.8.9v13.6a.88.88 0 0 0 .8.9h7.3v-6h-2V7.1h2V5.4a2.87 2.87 0 0 1 2.5-3.1h.5a10.87 10.87 0 0 1 1.8.1v2.1h-1.3c-1 0-1.1.5-1.1 1.1v1.5h2.3l-.3 2.3h-2v5.9h3.9a.88.88 0 0 0 .9-.8V.8a.86.86 0 0 0-.8-.8z" fill="currentColor"></path></svg></span>
          <span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19.17 13.6" class="d-block" height="16"><path d="M18.77 2.13A2.4 2.4 0 0 0 17.09.42C15.59 0 9.58 0 9.58 0a57.55 57.55 0 0 0-7.5.4A2.49 2.49 0 0 0 .39 2.13 26.27 26.27 0 0 0 0 6.8a26.15 26.15 0 0 0 .39 4.67 2.43 2.43 0 0 0 1.69 1.71c1.52.42 7.5.42 7.5.42a57.69 57.69 0 0 0 7.51-.4 2.4 2.4 0 0 0 1.68-1.71 25.63 25.63 0 0 0 .4-4.67 24 24 0 0 0-.4-4.69zM7.67 9.71V3.89l5 2.91z" fill="currentColor"></path></svg></span>
          <span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19 18" class="d-block" height="18"><path d="M3.94 2A2 2 0 1 1 2 0a2 2 0 0 1 1.94 2zM4 5.48H0V18h4zm6.32 0H6.34V18h3.94v-6.57c0-3.66 4.77-4 4.77 0V18H19v-7.93c0-6.17-7.06-5.94-8.72-2.91z" fill="currentColor"></path></svg></span>
          <span><svg height="20" class="octicon octicon-mark-github d-block" alt="" viewBox="0 0 16 16" version="1.1" width="20" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg></span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
name: "foot"
,
  data(){
  return{
    Nav:['Usename','Email', 'Password'],
  }
  }
}
</script>

<style scoped>
 .top{
   background-color: #2b3137;
   color: white;
   height: 600px;
   text-align: center;
 }
 .Repeat{
   text-align: left;
   color: white;
   font-size: 14px;
   padding: 10px 10px;
   width: 400px;
   /*font-weight: bolder;*/
 }
 /*.font1{*/
 /*  font-size: 64px;*/
 /*  !*font-family:;*!*/
 /*  margin-bottom:30px ;*/

 /*}*/
 /*.font2{*/
 /*  font-size: 19px;*/
 /*  color: #9c9fa2;*/
 /*  line-height: 30px;*/
 /*  !*font-family: 黑体;*!*/
 /*}*/
 .Iput2{
   width: 240px;
   height: 25px;
   padding:10px ;
   font-size: 16px ;
   border-radius: 5px;
   border: #e1e4e8 1px solid ;
   background-color: #e8f0fe;
   margin-top: 5px;
 }
 .H{
   width: 980px;
   color: white;
   position: absolute;
   right: 0;
   left: 0;
   top: 100px;
   margin: auto;


  font-size: 32px;
 }
 .max{
   position: relative;
 }
 .NavRight{
   display: flex;
   width: 1248px;
   align-content: space-around;
   position: absolute;
   top: 300px;
   right: 0;
   left: 0;
   margin: auto;
 }
 .Iput3{
   width: 425px;
   height: 50px;
   padding:10px 20px;
   background-color:#2ebc4f;
   margin-left:10px ;
   border-radius: 5px;
   color: white;
   font-size: 16px;
   margin-bottom: 40px;
   margin-top: 20px;
   border: none;
 }
 .H2{
   font-size: 12px;
   color: #6a737d;
   position: absolute;
   top: 450px;
   right: 0;
   left: 0;
   margin: auto;

 }
 .topa{
   color: white;
   /*position: absolute;*/

 }
 .topa:hover{
   text-decoration: underline;
 }
 .mid{
   height: 400px;
   padding-top:80px ;
 }
 .abs{
   position: absolute;
   right: 0;
   left: 0;
   margin: auto;
   width: 1200px;
   display: flex;
   justify-content: space-around;
   padding: 0 16px ;
 }
 .midleft{
   width: 400px;
 }

 .midh2{
   font-size: 14px;
   font-weight: 400;
   margin-bottom: 16px;
   color:  #586069;
 }
 .midli{
   font-size: 14px;
   margin-bottom: 16px;

 }
.midli>a{
  color: #586069;
}
 .midli>a:hover {
  text-decoration: underline;
   color:#0069d4 ;
 }

 .buttom{
   /*height: 68px;*/
   background-color: #fafbfc;
   position: relative;
   padding: 24px 16px 36px;

 }
 .absbut{
   position: absolute;
   width: 1280px;
   right: 0;
   left: 0;
   margin: auto;
   /*padding: 24px 16px;*/
   /*background-color: pink;*/
 }
 .reletive{
   position: relative;
 }
 .reletive>ul{
   display: flex;
   flex-direction: row;
 }
 .reletive>ul>li{
   margin-right:10px ;
   font-size: 12px;
   color: #586069;
 }
 .reletive>ul>a{
   color: #586069;
   font-size: 12px;
   margin-left:10px ;

 }
 .reletive>ul>a:hover{
 text-decoration: underline;
   color: #0069d4;

 }
 .d-block{
   fill:#586069 ;
   color: #586069;
   filter: grayscale(100%);
 }
 .footright{
   position: absolute;
   top: 0;
   right: 0;
 }
 .footright>span{
   /*filter: grayscale(100%);*/
   margin-left: 20px;
 }
</style>
