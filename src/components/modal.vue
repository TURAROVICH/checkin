<template>
 <transition name="slide-fade">
    <div v-if="modal" class="main">

        <div class="menu">
    
       <div class="support-menu">
                 <div class="support-container-menu">
                      <a href="">Специалисты</a>
                      <a href="">Учреждения</a>
                      <a href="">О нас</a>
                 </div>
            </div>

        </div>

    </div>
         </transition>
</template>


<script>
export default {
    props:["modal"],
    data:()=>({
      
    })
}
</script>

<style scoped>

.slide-fade-enter-active {
  transition: all .3s ease;
}
.slide-fade-leave-active {
  transition: all .8s cubic-bezier(1.0, 0.5, 0.8, 1.0);
}
.slide-fade-enter, .slide-fade-leave-to
/* .slide-fade-leave-active до версии 2.1.8 */ {
  transform: translateX(100px);
  opacity: 0;
}

        .main{
    position: absolute;
    display: block;
    width: 400px;
    height: 500px;
    background: rgba(0,0,0,0.6);
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 10px 13%;
    border-radius: 25px;
}

.menu{
    display: flex;
    align-items: center;
    justify-content: center;
}
.support-container-menu{
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
    gap: 30px;
}
a{
    text-decoration: none;
    font-size: 20px;
}
@media screen and (max-width:520px) {
    .main{
        margin: 10px 10px;
    }
}
@media screen and (max-width:439px) {
    .main{
        width: 300px;
    }
}
</style>