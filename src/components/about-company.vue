<template>
    
    <div id="about1" class="main">
       <div class="main-container">
               <div class="about-container">
                   <div class="about-header">
                      <div class="line"></div>
                       
                       <div class="circles">
                           <div class="large-circle"></div>
                           <div class="small-circle"></div>
                       </div>
                   </div>

                   <div class="about-content">
                       <div class="about-title">
                           <div class="text">
                               О компании
                           </div>
                       </div>

                       <div class="description">
                           ОсОО «Новатек Плюс» начала свою деятельность 1 января 2019 года и стала примером успешного создания и внедрения программных продуктов в работу медицинских учреждений. 
                       </div>

                       <div class="description">
                           ОсОО «Новатек Плюс» начала свою деятельность 1 января 2019 года и стала примером успешного создания и внедрения программных продуктов в работу медицинских учреждений. 
                       </div>

                       <div class="description">
                           ОсОО «Новатек Плюс» начала свою деятельность 1 января 2019 года и стала примером успешного создания и внедрения программных продуктов в работу медицинских учреждений. 
                       </div>
                   </div>

                   <div class="about-footer">
                         <div class="large-circle1"></div>
                         <div class="small-circle1"></div>
                   </div>
               </div>

               <div class="bg-img">
                   <img src="../assets/okay.png" alt="">
               </div>
       </div>
    </div>
</template>

<style scoped>
.about-footer{
    display: flex;
    margin-top: 15px;
}
.large-circle1{
    background: linear-gradient(90deg, #4DC2B3 0%, #24AAC5 100%);
opacity: 0.1;
transform: matrix(-1, 0, 0, 1, 0, 0);
width: 115px;
height: 115px;
border-radius: 50%;
}
.small-circle1{
    background: linear-gradient(90deg, #4DC2B3 0%, #24AAC5 100%);
transform: matrix(-1, 0, 0, 1, 0, 0);
width: 34px;height: 34px;
border-radius: 50%;
}
.about-header{
    width: 300px;
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
}
.line{
    border-bottom: 4px solid #000;
    width: 50px;
}
.large-circle{
    background: #24AAC5;
opacity: 0.3;
transform: matrix(-1, 0, 0, 1, 0, 0);
width: 43px;
height: 43px;
border-radius: 50%;
}
.small-circle{
    background: #4DC2B3;
opacity: 0.1;
transform: matrix(-1, 0, 0, 1, 0, 0);
width: 19px;
height: 19px;
border-radius: 50%;
}
.about-content{
    width: 614px;
}
.about-title .text{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #0F2A56;
}
.description{
    font-family: Montserrat;
font-style: normal;
font-weight: 900;
font-size: 18px;
line-height: 22px;
color: #0F2A56;
}
.main{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}
.main-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

@media  screen and (max-width:1250px) {
    .main-container{
        flex-direction: column-reverse;
    }
    .main{
        margin-top: 200px;
    }
    .line{
        display: none;
    }
    .large-circle,.large-circle1,.small-circle,.small-circle1{
        display: none;
    }
}

@media screen and (max-width:757px) {
    img{
        width: 80%;
        box-sizing: border-box;
        margin: 0  5%;
    }
    .description{
        width: 80%;
        text-align: center;
    }
    .text{
        text-align: center;
    }
    .about-content{
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;
    }
    .main-container{
        display: flex;
        align-items: center;
        justify-content: center;
        /* flex-direction: column; */
    }
    .bg-img{
         display: flex;
        align-items: center;
        justify-content: center;
    }
}

@media screen and (max-width:520px) {
    img{
        width: 50%;
    }
    .description{
        width: 60%;
    }
}
</style>