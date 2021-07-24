<template>
    <div class="main">
         <div class="main-container">
             <div class="line"></div>

             <div class="title-text-container">
                 <div class="title">
Преимущества для партнеров!
                 </div>
             </div>

             <div class="cards-container">


                    <div class="cards_1">

                     <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group15.svg" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                                            Возможность просто и эффективно 
управлять частной клиникой

                                 </div>
                             </div>
                         </div>
                     </div>

                       <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group16.svg" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                              Экономия времени и ресурсов

                                 </div>
                             </div>
                         </div>
                     </div>


                       <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group17.svg" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                     Отсутствие бумажной волокиты

                                 </div>
                             </div>
                         </div>
                     </div>


                       <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group18.png" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                   Интуитивно понятный интерфейс

                                 </div>
                             </div>
                         </div>
                     </div>

                    </div>


                    <div class="cards_2">


<div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group19.png" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                     Бесплатная техническая поддержка со стороны
наших специалистов


                                 </div>
                             </div>
                         </div>
                     </div>



                     <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group20.png" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                      Обучение вашего персонала

                                 </div>
                             </div>
                         </div>
                     </div>


                     <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group15.svg" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                           Внедрим систему всего за 5 дней!

                                 </div>
                             </div>
                         </div>
                     </div>



                     <div class="card-container">
                         <div class="card card-1">
                             <div class="img">
                                 <img src="../assets/Group21.png" alt="">
                             </div>

                             <div class="text-container">
                                 <div class="text-description">
                            Ваши данные надежно защищены

                                 </div>
                             </div>
                         </div>
                     </div>



                    </div>


             </div>
         </div>
    </div>
</template>

<style scoped>
.img{
    display: flex;
    align-items: center;
    justify-content: center;
}
.main-container{
    padding: 40px 5px;
}
.card{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 500px;
    margin-top: 20px;
}
.text-description{
    font-family: Montserrat;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 22px;
width: 350px;

color: #FFFFFF;
}
.img{
    width: 120px;
    height: 120px;
    background: #fff;
    border-radius: 50%;
}
.cards_1{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.cards-container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 50px;

}
.title-text-container{
    display: flex;
    align-items: flex-start;
    justify-content: flex-start;
    margin-top: 50px;
}
.line{
    background: #FFFFFF;
    width: 76px;
    height: 7px;
}
.title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #FFFFFF;
}
.main{
    width: 100%;
    min-height:70vh;
    background: #1E1E20;
    margin-top: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
}

@media screen and (max-width:1042px) {
    .line{
        display: none;
        overflow: hidden;
    }
    .title-text-container{
       align-items: center;
       justify-content: center;
    }

    .card{
        flex-direction: column;
    }
    .text-description{
        text-align: center;
    }
}


@media screen and (max-width:880px) {
    .cards-container{
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .card{
    margin-top: 40px;
    }
}


@media screen and (max-width:530px) {
    .title-text-container{
        align-items: center;
        justify-content: center;
        display: flex;
    }
    .title{
        text-align: center;
    }
}
</style>