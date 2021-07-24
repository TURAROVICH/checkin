<template>
    <div class="main">
        <div class="main-container">
               


        <div class="text-img-wrapper">
               <div class="img-container">
                    <div class="img">
                        <img src="../assets/Group4.svg" alt="">
                    </div>
               </div>


               <div class="text-container">
                   <div class="title-container">
                       <div class="title">
                                Записывайтесь к любым врачам
онлайн на сайте <span class="logo-text">checkin.kg</span>
                       </div>
                   </div>

                   <div class="button-container">
                       <div class="button">
                           <div class="button-text">
Записаться на прием
                           </div>
                       </div>
                   </div>
               </div>
        </div>

        </div>  
    </div>
</template>

<style scoped>
.title-container{
    display: flex;
    align-items: center;
    justify-content: center;
}
.main{
    margin-top: 100px;
}
.text-container{
    margin-top: 50px;
    width: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.text-img-wrapper{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
text-align: center;

color: #0F2A56;
}
.logo-text{
    /* color: linear-gradient(98.5deg, #1BEFDC 0%, #24CEDA 100%); */
      background:  linear-gradient(98.5deg, #1BEFDC 0%, #24CEDA 100%);;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.button-container{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 30px;
}
.button{
    background: linear-gradient(98.5deg, #1BEFDC 0%, #24CEDA 100%);
box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.07);
border-radius: 25px;
width: 254px;
height: 52px;
display: flex;
align-items: center;
justify-content: center;
}
.button-text{
    font-family: Montserrat;
font-style: normal;
font-weight: 500;
font-size: 18px;
line-height: 22px;
/* identical to box height */


color: #FFFFFF;
}

@media screen and (max-width:908px) {
    img{
        width: 532px;
        height: 561px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .img-container{
        display: flex;
        align-items: center;
        justify-content: center;
    }
}

@media screen and (max-width:622px) {
    img{
        width: 80%;
    }

    .main{
         margin-top: 0px;
    }
    .title{
        text-align: center;
        width: 70%;
    }
    .text-container{
        margin-top: -50px;
    }

}
</style>