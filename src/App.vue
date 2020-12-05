<template>
  <div id="app">
    <Navigation></Navigation>
    <BodyFirst></BodyFirst>
    <Repeat></Repeat>

    <vue1 :messa1="messa1" :h1="h1" :p1="p1" :btn1="btn1"></vue1>
    <div style="height: 100px"></div>
    <robot></robot>
    <Zujian></Zujian>
<!--    <vue2></vue2>-->
    <vue1 :messa1="messa2" :h1="h2" :p1="p2" :btn1="btn2"></vue1>
    <bodyScend></bodyScend>
    <vue1 :messa1="messa3" :h1="h3" :p1="p3" :btn1="btn3"></vue1>
    <last></last>
    <foot></foot>
  </div>
</template>

<script>

import Navigation from "@/components/Navigation";
import BodyFirst from "@/components/BodyFirst";
import Repeat from "@/components/Repeat";
import Zujian from "@/components/Zujian";
import vue1 from "@/components/vue1";
import robot from "@/components/robot";
// import vue2 from "@/components/vue2";
import bodyScend from "@/components/bodyScend";
import foot from "@/components/foot";
import last from "@/components/last";
export default {
  name: 'App',
  data(){
    return {
          messa1: 'GitHub for teams',
          h1: 'A better way to work together',
          p1: 'GitHub brings teams together to work through problems, move ideas forward, and learn from each other along the way.',
          btn1: 'Sign up your team >',
          messa2:'Security and administration',
          h2:'Your business needs, met',
          p2:'From flexible hosting to granular access controls, we’ve got your security requirements covered.',
          btn2:'Learn how GitHub Enterprise works ->',
          messa3:'Integrations',
          h3:'Build on GitHub',
          p3:'Customize your process with GitHub apps and an intuitive API. Integrate the tools you already use or discover new favorites to create a happier, more efficient way of working.',
          btn3:'Learn about intergrations',
    }
  },
  components: {
    Navigation,BodyFirst,Repeat,Zujian,vue1,robot,bodyScend,foot,last,
  }
}
</script>

<style>
*{
  padding: 0;
  margin: 0;
  text-decoration: none;
 list-style: none;
}

</style>
