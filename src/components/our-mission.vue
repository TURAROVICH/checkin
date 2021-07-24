<template>
    <div class="main">
        <div class="mission-container">
              <div class="mission">
                  <div id="mission" class="mission-title">
Наша миссия
                  </div>

                  <div class="mission-description">
Наша миссия – повысить работоспособность медицинского персонала, обеспечить кыргызстанцам максимально комфортные условия при обращении за услугами к врачам и избавить регистратуры медицинских центров от устаревших технологий работы с пациентами.
                  </div>

                  <div class="button">
                      <div class="button-text">
                          Контакты
                      </div>
                  </div>
              </div>
        </div>
    </div>
</template>

<style scoped>
.main {
    min-height: 110vh;
    width: 100%;
    background: url("../assets/Vector6.png") no-repeat,url("../assets/our-mission.png") no-repeat;
    background-position: center left,center right;
    /* background-size: ; */
    display: flex;
    align-items: center;
    justify-content: flex-start;
    box-sizing: border-box;
}
.mission-container{
    margin-left: 200px;
    max-width: 658px;
    display: flex;
    flex-direction: column;
}
.mission-title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #0F2A56;

}
.mission-description{
    margin-top: 30px;
    font-family: Montserrat;
font-style: normal;
font-weight: 900;
font-size: 18px;
line-height: 22px;

color: #0F2A56;

}
.button{
    margin-top: 40px;
    width: 254px;
    height: 52px;
    background: linear-gradient(98.5deg, #1BEFDC 0%, #24CEDA 100%);
box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.07);
border-radius: 25px;
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

@media screen and (max-width:1200px) {
    .mission-description{
        max-width: 700px;
    }
    .mission{
        margin-top: 1200px;
    }
}

@media screen and (max-width:910px){
    .mission-container{
        width: 500px;
        margin-left: 100px;
        height: auto;
    }

}

@media screen and (max-width:795px){


     .main{
    min-height: 110vh;
    width: 70%;
    margin-left: 40px;
    background: url("../assets/our-mission.png") no-repeat;
    background-position: center;
    background-size: 90vw 80vh;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    box-sizing: border-box;
    margin-top: -300px;
    }
    .mission{
        margin-top: 1000px;
    }
}
@media screen and (max-width:442px) {
    .mission-description{
        margin-left: -100px;
        width: 300px;
        text-align: center;
    }
  .main{
      margin-top: -100px;
  }
  .mission-container{
    margin-left: 100px;}
    .mission-title{
        margin-left: -50px;
    }
    .button{
        margin-left: -50px;
    }

}

@media screen and (max-width:358px) {
    .mission-container{
        margin-left: 50px;
    }
    .main{
    background-size: 90vw 50vh;

    }
}
</style>