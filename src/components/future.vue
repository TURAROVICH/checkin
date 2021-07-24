<template>
    <div class="main">
         <div class="main-container">
             <div class="img-container">
                 <div class="left-circle">
                      <div class="big-circle"></div>
                                            <div class="small-circle">

                      </div>
                 </div>

                 <div class="img">

                 </div>

                 <div class="right-circle">
                       <div class="small-circle1"></div>
                       <div class="big-circle1"></div>
                 </div>
             </div>
             <div class="title-text-wrapper">
                 <div class="text">Будущее – за высокими технологиями.
Будущее – за нами!
</div>
             </div>
         </div>
    </div>
</template>


<style scoped>
.text{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
text-align: center;

color: #0F2A56;
}
.title-text-wrapper{
    max-width: 753px;
    margin-top: 50px;
    display: flex;
    align-items: center;
    /* justify-tracks: ; */
    justify-content: center;
}
.img-container{
    display: flex;
    align-items: center;
    justify-content: center;
}
.main-container{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.img{
    background: url("../assets/Group9.png") no-repeat;
    box-sizing: border-box;
    background-size: cover;
    min-width: 656px;
    min-height: 596px;
}
.small-circle1{
    background: linear-gradient(90deg, #4DC2B3 0%, #24AAC5 100%);
    width: 63px;
    height: 63px;
    border-radius: 50%;
}
.big-circle1{
    
background: linear-gradient(90deg, #4DC2B3 0%, #24AAC5 100%);
opacity: 0.1;
width: 213px;
height: 213px;
border-radius: 50%;
}
.small-circle{
    background: #4DC2B3;
opacity: 0.1;
width: 36px;
height: 36px;
border-radius: 50%;
}
.big-circle{
    background: #24AAC5;
opacity: 0.3;
border-radius: 50%;
width: 80px;
height: 80px;
}
.main{
    margin-top: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    min-height: 90vh;
}

@media screen and (max-width:975px){
    .right-circle{
        display: none;
        overflow: hidden;
    }

    .left-circle{
        display: none;
        overflow: hidden;
    }
}


@media screen and (max-width:723px) {
    .img{
        width: 50%;
        background-size: 70% 60%;
        background-position: center center;

    }
    .title-text-wrapper{
        margin: -50px 0px 0px 0px;
        width: 70%;
    }
}

@media screen and (max-width:500px) {
   .img{
        width: 50%;
        background-size: 60% 50%;
        background-position: center center;
    }   
}

@media screen and (max-width:460px) {
    .title-text-wrapper{
        width: 50%;
    }
}
</style>