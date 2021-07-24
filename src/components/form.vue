<template>
    <div class="main">
        <div class="main-container">
            <div class="img">
                <img src="../assets/Group1.svg" alt="">
            </div>
            <div class="title-text">    
                <div class="title">У вас остались вопросы?</div>
                <div class="helper-text">Напишите нам</div>
            </div>

            <div class="form">
                <form action="#">
                    <div class="input"><input type="text" placeholder="  Ваше имя"></div>
                    <div class="input"><input type="text" placeholder="  Номер телефона"></div>
                    <div class="input"><input type="text" placeholder="  E-mail (необязательно)"></div>
                    <div class="button-container">
                        <div class="button">
                            <div class="button-text">Отправить заявку</div>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>

<style scoped>
.img{
    display: none;
}
.button-container{
    margin-top: 20px;
}
form{
    display: flex;
    align-items: flex-start;
    justify-content:flex-start;
    flex-direction: column;
}
input{
     outline: none;
    border: none;
    background: transparent;
    width: 400px;
    height: 45px;
     color: rgba(0, 0, 0, 0.9);
    font-weight: 700;
}
.input{
    width: 440px;
    height: 52px;
    border-radius: 25px;
    margin-top: 15px;
    background: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
}
.title{
    font-weight: 600;
font-size: 36px;
line-height: 44px;
}
.helper-text{
    font-family: Source Sans Pro;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 23px;

}
.main-container{
    width: 80%;
}
.main{
    background:url("../assets/Group22.png") no-repeat, url("../assets/Group15.png") no-repeat;
    width: 100%;
    min-height: 80vh;
    background-size: 760px 380px,cover;
    background-position: center right,center center;
    margin-top: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.button{
    background: linear-gradient(98.5deg, #1BEFDC 0%, #24CEDA 100%);
box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.07);
border-radius: 26px;
width: 440px;
height: 52px;
display: flex;
align-items: center;
justify-content: center;
}
input::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
  font-family: Source Sans Pro;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 23px;

color: rgba(15, 42, 86, 0.5);
  opacity: 1; /* Firefox */
}


@media  screen and (max-width:919px) {
   .main{
    background: url("../assets/M.png") no-repeat;
    width: 100%;
    min-height: 160vh;
    /* background-size: 760px 380px,cover; */
    background-position: bottom center;
   }
   .main-container{
       width: 100%;
       align-items: center;
       justify-content: center;
       display: flex;
       flex-direction: column;
   }
   .img{
       display: block;
       
   }
}

@media  screen and (max-width:680px) {
    img{
        width: 90%;
    }
}

@media screen and (max-width:470px) {
    .input{
        width: 300px;
    }
    .button{
        width: 300px;
    }
}
</style>