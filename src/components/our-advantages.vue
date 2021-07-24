<template>
    <div id="advantages" class="main">
        <div class="main-container">
            <div class="main-title">
                <div class="title-text">Наши преимущества
</div>
            </div>

            <div class="cards">
              
              
                <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-1">

                          </div>

                          <div class="card-description">
Более 1000 врачей по всему 
Кыргызстану используют 
Checkin и обслуживают более 
2 000 000 пациентов и сотрудников.
                          </div>
                      </div>
                </div>

                  <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-2">

                          </div>

                          <div class="card-description">
У нас на сайте вы найдете 
практически полный список медицинских центров Бишкека 
и сможете ознакомиться с их услугами.
                          </div>
                      </div>
                </div>

                  <div class="card">
                      <div class="card-wrapper">
                          <div class="card-img-3">

                          </div>

                          <div class="card-description">
Мы работаем 
более чем с 25 больницами Бишкека 
и сотнями лучших специалистов. 

                          </div>
                      </div>
                </div>


            </div>

        </div>
    </div>
</template>


<style scoped>
.card-description{
    margin-top: 50px;
    font-family: Montserrat;
font-style: normal;
font-weight: 900;
font-size: 18px;
line-height: 22px;
text-align: center;

color: #0F2A56;
}
.card-img-1{
    background: url("../assets/Group6.png") no-repeat;
    width: 383px;
    height:245px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}

.card-img-2{
    background: url("../assets/Group7.png") no-repeat;
    width: 265px;
    height:245px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}

.card-img-3{
    background: url("../assets/Group8.png") no-repeat;
    width: 330px;
    height:245px;
    background-size: cover;
    background-position: center center;
    box-sizing: border-box;
}
.card-wrapper{
    width: 382px;
}
.card{
    width: 440px;
    height: 500px;
    background: #FFFFFF;
   display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
box-shadow: 0px 3px 10px rgba(0, 0, 0, 0.05);
border-radius: 20px;

margin-left: 10px;
}
.cards{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    /* flex-wrap: wrap; */
    margin-top: 50px;
}
.main{
    margin-top: 100px;
    width: 100%;
    min-height: 70vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.main-container{
   width: 95%;
}
.title-text{
    font-weight: 600;
font-size: 36px;
line-height: 44px;



color: #0F2A56;

}


@media screen and (max-width:1200px){
    .cards{
        flex-direction: column;
    }
    .card{
        margin-top: 50px;
    }
    .title-text{
        text-align: center;
    }
    .main{
        margin-top: 220px;
    }
    .card-img-1{
        width: 70%;
    }
}


@media screen and (max-width:530px){
     .card{
         width: 70%;
     }
     .card-wrapper{
         display: flex;
         align-items: center;
         justify-content: center;
         flex-direction: column;
     }

     .card-description{
         width: 230px;

     }

     .card-img-3{
         width: 200px;
     }

}

@media screen and (max-width:420px) {
    .card-img-1,.card-img-2,.card-img-3{
        width: 150px;
    }
}
</style>