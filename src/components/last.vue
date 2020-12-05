<template>
  <div id="last">
    <h2 class="new">Community</h2>
    <h1 class="new1">Welcome home, <br> developers</h1>
    <h1 class="font1">GitHub is home to the world’s largest community of developers and <br /> their projects...</h1>
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
  name: "last",
  data(){
    return{
      A:[
        {
          img:require('../assets/developer-1.jpg'),
          H1:'Russell Keith-Magee',
          P:'Russell Keith-Magee created BeeWare to fill a gap in his own process. Today, BeeWare is the go-to project for supporting Python on every platform.',
          A:'Read more     →',
        },
        {
          img:require('../assets/developer-2.jpg'),
          H1:'Kris Nova',
          P:'Kris Nova quickly developed a passion for open source software. Now she gets to work on open source tooling at her day job, which includes maintaining Kubernetes Operations (kops).',
          A:'Read more    →',
        },
        {
          img:require('../assets/developer-3.jpg'),
          H1: 'Evan You',
          P:'In 2013, Evan You founded Vue, a Javascript framework funded by the community on Patreon. In 2016, Vue reached 2,000,000 downloads.',
          A:'Read more     →',
        },
        {
          img:require('../assets/developer-4.jpg'),
          H1:'Jess Frazelle',
          P:'Jess Frazelle works on Kubernetes full-time. Previously she maintained Docker, a software containerization platform used by thousands of teams.',
          A:'Read more     →',
        },

      ]
    }
  },
  // props:
}
</script>

<style scoped>
#last{
  text-align: center;
  height:700px;
}

.font1{
  font-size: 20px;
  color: #586069;
  margin-bottom: 20px;

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
  width: 250px;
}
.bor{
  position: relative;

  border-bottom: 1px #e1e4e8 solid;
  height: 350px;
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
  /*font-family: Candara;*/
}
.font3{
  font-size: 16px;
  color: #24292e;
  font-weight: 400;
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
.new{
  font-size: 16px;
  color: #586069;
  margin-top: 50px;
}
.new1{
  font-size: 48px;
  color: #24292e;
  margin-bottom: 20px;
}
</style>
