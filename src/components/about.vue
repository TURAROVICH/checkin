<template>
    <div id="about" class="main">


       <div class="about-container">
              <div class="about-1 ">

                 <div class="about-container-1">
                    <div class="about-title-container">
                        <div class="about-title">
                            Какие проблемы решает Checkin?
                        </div>
                    </div>

                    <div class="description-container">
                        <div class="about-description_1">
Тратить время и силы на долгие ожидания в очередях не хочется никому. И даже запись по телефону - не самый удобный вариант, ведь порой в регистратуру не дозвониться. 
                        </div>

                        <div class="about-description_2">
                            Сервис онлайн-записи к специалистам Checkin решает эту проблему и предоставляет возможность записаться на прием 
к любому врачу онлайн, самостоятельно выбрав удобные 
для себя дату и время!
                        </div>
                    </div>
                     </div>

                    <div class="about-img">
                        <img src="../assets/about.png" alt="">
                    </div>

              </div> 




              <div class="about-2 ">

                 <div class="about-container-2">
                    <div class="about-title-container">
                        <div class="about-title">
                           Выбирайте врача, к которому хотите попасть на прием, в режиме онлайн!

                        </div>
                    </div>

                    <div class="description-container">
                        <div class="about-description_1">
Клиники не всегда предоставляют развернутую информацию о каждом своем специалисте. И зачастую клиенты не могут самостоятельно выбрать врача.
  </div>

                        <div class="about-description_2">
А с помощью сервиса Checkin.kg вы можете в пару кликов найти врача нужной специализации, ознакомиться с рейтингом каждого специалиста и почитать комментарии. Это позволит вам найти самый оптимальный для себя вариант и в пару кликов записаться к понравившемуся врачу на прием онлайн.
                        </div>
                    </div>
                     </div>

                    <div class="about-img">
                        <img src="../assets/about1.png" alt="">
                    </div>

              </div> 



       </div>
    </div>
</template>

<style scoped>
.about-description_2{
    margin-top: 15px;
}
.about-description_1{
    margin-top: 15px;
}
.about-1{
    display: flex;
    justify-content: center;
    align-items: center;
}

.about-2{
    display: flex;
    justify-content:space-between;
    align-items: center;
    flex-direction: row-reverse;
}
.about-container-1{
    
    width: 600px;
}
.about-container-2{
 width: 600px;
}
.description-container > div{
    font-family: Montserrat;
font-style: normal;
font-weight: 900;
font-size: 18px;
line-height: 22px;

color: #0F2A56;
}
.about-title{
    font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #0F2A56;
}
.about-container{
    width: 90%;
}
.main{
    min-height: 100vh;
    width: 100%;
    height: 100%;
    background: #e5e5e5;
    display: flex;
    align-items: center;
    justify-content: center;
}
@media screen and (max-width:1000px) {
    .about-1{
        flex-direction: column-reverse;
        margin-top: 50px;
    }
    .about-2{
        flex-direction: column-reverse;
        margin-top: 50px;
    }
}

@media screen and (max-width:643px) {
    img{
        width: 90%;
    }
    .about-title{
        width: 90%;
        margin-left: 50px;
    }

    .about-container-1{
    
    width: 90%;
}
.about-container-2{
 width: 90%;
}
    
}
</style>