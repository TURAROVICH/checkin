<template>
    <div class="main">
       <div class="main-container">
           <div class="img">
                  <img src="../assets/Group5.png" alt="">
           </div>

           <div class="content-container">
               <div class="content">
                   <div class="content-header">
                          <div class="small-circle"></div>
                          <div class="large-circle"></div>
                   </div>

                   <div class="content-text">
                     <div class="content-title">Наши сотрудники

</div>

                     <div class="content-description">Слово «компетентность» является основным критерием для сотрудников. Поэтому у нас в штате работают только профессионалы своего дела. Мы – заслуженные лидеры в своей нише! 
</div>
                   </div>

                  <div class="content-footer">
                        <div class="small-circle1">
                        </div>

                        <div class="large-circle1"></div>
                  </div>

               </div>
           </div>
       </div>
    </div>
</template>

<style scoped>
.content-footer{
    margin-top: 100px;
    /* margin-left: 100px; */
    display: flex;
    width: 150px;
    justify-content: space-between;
}
.small-circle1{
    background: #4DC2B3;
opacity: 0.1;
width: 28px;
height: 28px;
border-radius: 50%;
align-self: flex-end;
}
.large-circle1{
    justify-self: flex-start;
    align-self: flex-start;
    background: #24AAC5;
opacity: 0.3;
width: 63px;
height: 63px;
border-radius: 50%;
}
.content-header{
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    width: 400px;
    margin-left: 200px;
}
.small-circle{
    width: 50px;
    height: 50px;
    background: linear-gradient(90deg, #4DC2B3 0%, #24AAC5 99.99%);
    border-radius: 50%;
}
.large-circle{
    background: linear-gradient(90deg, #4DC2B3 0%, #24AAC5 100%);
opacity: 0.1;
width: 168px;
height: 168px;
border-radius: 50%;
}
.main {
    width: 100%;
    margin-top: 100px;
}
.main-container{
    display: flex;
}
.content-description{
    margin-top: 30px;
    font-family: Montserrat;
font-style: normal;
font-weight: 900;
font-size: 18px;
line-height: 22px;
width: 600px;
color: #0F2A56;
}
.content-title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #0F2A56;
}
@media screen and (max-width:1200px) {
    .content-header{
        margin-left: 0px;
    }
    .content-description{
        width: auto;
    }
}

@media screen and (max-width:1100px){
    .main-container{
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .content-container{
        width: 600px;
        margin-top: -200px;
    }
}


@media screen and (max-width:725px) {
    img{
        width: 70%;
    }
    .img{
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .content-footer{
        display: none;
    }
    .content-header{
        display: none;
    }
    .content-text{
        margin-top: 200px;
        width: 70%;

    }
    .content{
        display: flex;
        align-items: center;
        justify-content: center;
    }
}


@media  screen and (max-width:449px) {
    .content-description{
        width: 300px;
    }
    .content-title{
        width: 300px;
        text-align: center;
    }
    .content-container{
        text-align: center;
        margin-left: 100px;
    }
}

@media screen and (max-width:330px) {
     .content-title{
        width: 150px;
        /* text-align: center; */
    }
    .content-container{
        text-align: center;
        margin-left: 200px;
    }
    .content-description{
        width: 200px;
    }
}
</style>