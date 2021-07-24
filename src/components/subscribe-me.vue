<template>
    
<div class="main">
    <div class="img">
        <img src="../assets/notebook.png" alt="">
    </div>

    <div class="content-container">
        <div class="content">
            <div class="content-title">
Улучшайте процессы своей работы 
и присоединяйтесь к нашей команде
            </div>

            <div class="description">Улучшайте процессы своей работы и присоединяйтесь к нашей команде </div>
            <div class="description">Наша система создана для того, чтобы облегчить жизнь пациентов 
и врачей, помочь сэкономить главный ресурс - время. Планируйте 
свой визит заранее и записывайтесь на прием в удобное для вас время.
</div>

           <div class="button-container">
               <div class="button">
                   <div class="button-text">
Стать специалистом
                   </div>
               </div>
           </div>
           
           <div class="lieaner lienar-1">
                   <img src="../assets/Vector5.png" alt="">
           </div>


        </div>
    </div>
</div>

</template>


<style scoped>
.content{
    position: relative;
}
.lieaner{
    margin-left: 300px;
    margin-top: -30px;
}
.button-container{
    margin-top: 20px;
}
.button {
    background: linear-gradient(98.5deg, #1BEFDC 0%, #24CEDA 100%);
box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.07);
border-radius: 25px;
width: 254px;
height: 54px;
display: flex;
align-items: center;
justify-content: center;
}
.content-title{
    font-weight: 600;
font-size: 36px;
line-height: 44px;

color: #0F2A56;
}
.description{
    margin-top: 15px;
    font-family: Montserrat;
font-style: normal;
font-weight: 900;
font-size: 18px;
line-height: 22px;

color: #0F2A56;

}
.main{
    width: 90%;
    min-height:800px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: -100px;
}
.content-container{
 width: 730px;
 display: flex;
 align-items: center;
 justify-content: center;
}
@media screen and (max-width:1030px){
    .lienar{
        margin-left: -200px;
    }
}
@media screen and (max-width:1000px) {
    .main{
        display: none;
        overflow: hidden;
    }
}
</style>