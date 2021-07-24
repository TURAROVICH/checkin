<template>
    <div class="main">
        <div class="main-container">
            <div class="title-wrapper">
                <div class="title">Что вы получите:
</div>
            </div>

            <div class="cards-container">
                <div class="cards">
                            <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-3">

                          </div>

                          <div class="card-description">
Комфортная работа 
с расписанием, никакой бумажной волокиты
Готовые шаблоны для документов (направления, справки, результаты приема)

                          </div>
                      </div>
                </div>


     <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-2">

                          </div>

                          <div class="card-description">
Удобная коммуникация сотрудников учреждения между собой внутри системы, готовые шаблоны для документов (направления, справки, результаты приема)

                          </div>
                      </div>
                </div>



     <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-1">

                          </div>

                          <div class="card-description">
Увеличение количества пациентов и дохода учреждения, благодаря продвижению 
на нашей площадке
    </div>
                      </div>
                </div>


                  <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-4">

                          </div>

                          <div class="card-description">
Управление 
медицинским предприятием 
с любой точки мира.
Расчет пациента (реализована интеграция с 1С Бухгалтерия)

    </div>
                      </div>
                </div>





                </div>
            </div>

            <div class="button-container">
                   <div class="button">
                       <div class="button-text">
Оставить заявку

                       </div>
                   </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.main   {
    margin-top: 100px;
}
.cards-container{
    margin-top: 70px;
}
.button-container{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    margin-top: 50px;
}
.card-wrapper{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.card-description{
    padding: 10px 0;
font-family: Montserrat;
font-style: normal;
font-weight: 700;
font-size: 18px;
line-height: 22px;
text-align: center;
width: 291px;
color: #0F2A56;
}
.card-img-1{
    background: url("../assets/Group13.png") no-repeat;
    width: 250px;
    height:160px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}
.card-img-4{
    background: url("../assets/Group14.png") no-repeat;
    width: 208px;
    height:160px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}

.card-img-2{
    background: url("../assets/Group12.png") no-repeat;
    width: 212px;
    height:160px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}

.card-img-3{
    background: url("../assets/Group11.png") no-repeat;
    width: 245px;
    height:160px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}
.cards{
    /* width: 382px; */
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.card{
    padding: 20px;
    width: 323px;
    /* height: 240px; */
    background: #FFFFFF;
   display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
box-shadow: 0px 3px 10px rgba(0, 0, 0, 0.05);
border-radius: 20px;

margin-left: 10px;
}
/* .card{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    /* flex-wrap: wrap; */
    /* margin-top: 50px; */



.title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #0F2A56;

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


@media screen and (max-width:1200px) {
    .cards{
        flex-wrap:wrap;
    }
    .card{
        margin-top: 20px;
    }
    .title{
        text-align: center;
    }
}
</style>