<template>
  <div id="app">
    <Header_tmp @modal="modal"/>
    <SideBar/>
       <Modal :modal="modalV"/>
    <Main_tmp/>
    <div class="media-off">
      <helper/>
    </div>
    <About/>
    <forspegialic/>
    <subscibe/>
    <aboutCompany/>
    <our_worker/>
    <our_mission/>
    <our_advantages/>
    <future/>
    <for_pather/>
    <request/>
    <advantages_for_pather/>
    <follow/>
    <form_support/>
    <footer_tmp/>
    
  </div>
</template>

<script>
import Header_tmp from './components/header'
import SideBar from './components/sideBar'
import Main_tmp from './components/main'
import About from './components/about'
import forspegialic from './components/forspecialic'
import subscibe from './components/subscribe-me'
import aboutCompany from './components/about-company'
import our_worker from './components/our-worker'
import our_mission from "./components/our-mission"
import our_advantages from './components/our-advantages'
import future from './components/future'
import for_pather from './components/for-partner'
import request from './components/request'
import advantages_for_pather from './components/advantages_for_pather'
import follow from './components/follow'
import form_support from './components/form'
import footer_tmp from './components/footer'
import helper from './components/helper'


import Modal from './components/modal'
export default {
  name: 'App',
  data:()=>({
     modalV:false
  }),
  methods:{
     modal(v){
       return this.modalV = v
     }
  },
  components: {
    Header_tmp,
    SideBar,
     Main_tmp,
     About,
     forspegialic,
     subscibe,
     aboutCompany,
     our_worker,
     our_mission,
    our_advantages,
    future,
    for_pather,
    request,
    advantages_for_pather,
    follow,
    form_support,
    footer_tmp,
    helper,
    Modal
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Montserrat;
  color:#fff;
}
html,body {
  overflow-x: hidden;
  scroll-behavior: smooth;
}
#app{
  background: #E5E5E5;;
  max-width: 1920px;
}
.media-off{
    display: none;
  }

@media screen and (max-width:1000px) {
  .media-off{
    display: block;
  }
}
</style>
