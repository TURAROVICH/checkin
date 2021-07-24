<template>
<div>
    <div class="main">
        <div class="header-container">
            <div class="logo">
                <img src="../assets/logo.png" alt="">
            </div>

            <div class="support">
                 <div class="support-container">
                      <a href="">Специалисты</a>
                      <a href="">Учреждения</a>
                      <a href="">О нас</a>
                 </div>
            </div>


            <div class="search">
                <div class="search-container">
               <img src="../assets/Vector3.png" alt="">
                 <input placeholder="Найти специалиста, учреждение или услугу" type="text">
                </div>
            </div>

            <div class="imgs">
                <img src="../assets/Vector.png" alt="">
                <img src="../assets/Vector1.png" alt="">
                <img src="../assets/Vector2.png" alt="">

            </div>
         

            <div @click="showMenu" :class="{cont:show}" class="burger-container">
                <div class="burger" :class="{rotate:show}"></div>
                <div class="burger" :class="{none:show}"></div>
                <div class="burger" :class="{rotate1:show}"></div>
            </div>




         
        </div>


           <div class="media-input">
                    <div class="search-container1">
               <img src="../assets/Vector3.png" alt="">
                 <input placeholder="Найти специалиста, учреждение или услугу" type="text">
                </div>
            </div>

    </div>




</div>
</template>


<script>
export default {
    data:()=>({
        show:false
    }),

    methods:{
        check(){
           return this.show ? false : true;
        },
        showMenu(){
           this.$emit('modal',this.check())
           this.show = !this.show
        }
    }
}
</script>



<style scoped>
.none{
  transition:all .3s ease;
  opacity: 0;
}
.rotate{
  transition:all .3s ease;
  transform: rotate(49deg) translate(8px,9px);
    
}
.cont{
    transition: all .2s ease;
    /* transform: rotate(185deg); */
}
.rotate1{
     transition:all .3s ease;
  transform: rotate(140deg) translate(-3px,7px);
  margin-bottom:3px;
}
.media-input{
    display: none;
    overflow: hidden;
}
.support-container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: nowrap;
}


.search-container{
    width: 100%;
    display: flex;
align-items: center;
justify-content: space-evenly;
height: 100%;
}
.search-container input{
    width: 320px;
    height: 20px;
    border-radius: 20px;
    outline: none;
    border: none;
    background: transparent;
    color: #fff;
}
   .search-container input::placeholder {
       color: #fff;
     }
.search{
      background: #24CEDA;
border: 1px solid #1BEFDC;
box-sizing: border-box;
border-radius: 29px;
width: 350px;
height: 40px;
}
.header-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    /* flex-direction: column; */
}

.main{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 70px;
    background: radial-gradient(149.04% 1096.52% at 99.9% 100%, #1BEFDC 0%, #24CEDA 100%);
    flex-direction: column;
}
.support-container a{
     font-family: Montserrat;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 20px;
/* identical to box height */


color: #FFFFFF;



margin: 0px 30px;
text-decoration: none;
}
.imgs{
   display: flex;
   justify-content: space-between;
   align-items: center;
   width: 200px;
}
.burger{
   border-bottom: 4px solid #ffc;
    width: 30px;
}
.burger-container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-direction: column;
    gap: 5px;
    display: none;
}
@media screen and (max-width:1125px) {
     .support-container a{
        margin: 0 10px;
     }
     .search{
         width: 270px;
     }
     .imgs{
         width: 150px;
     }
     .search-container input{
    width: 250px;
    height: 20px;
     }
}

@media screen and (max-width:1024px){
     .search{
         display: none;
         overflow: hidden;
     }
     .main{
         height: 110px;
        padding: 10px 0;
     }
     .search-container1{
        width: 100%;
    display: flex;
align-items: center;
justify-content: space-between;
height: 100%;
}
.media-input{
    display: block;
    overflow: visible;
    width: 100%;
    height:52px;
          background: #24CEDA;
border: 1px solid #1BEFDC;
box-sizing: border-box;
border-radius: 29px;
margin: 15px 0;
}
.search-container1 input{
    width: 100%;
    height: 40px;
    border-radius: 20px;
    outline: none;
    border: none;
    background: transparent;
    color: #fff;
    padding: 0 30px;
}
   .search-container1 input::placeholder {
       color: #fff;
     }



}

@media screen and (max-width:650px) {
    .support{
        display: none;
    }
    .burger-container{
        display: flex;
    }
}

</style>