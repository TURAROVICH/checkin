<template>
    <div id="pather" class="main">
        <div class="main-container">
            <div class="img-container">
                <img src="../assets/Group10.png" alt="" class="img">
            </div>

            <div class="text-container">
                <div class="line line-1"><img src="../assets/Vector1.svg" alt=""></div>

                <div class="text-wrapper">
                    <div class="text-title">Партнерам</div>

                    <div class="text-description">
Врачи, администраторы и другие лица, связанные с работой медучреждений, могут упростить свою работу при помощи нашей системы. Станьте нашим партнером и получите доступ к собственному личному кабинету, ведите запись клиентов онлайн и делайте пометки в истории болезни пациента в электронном формате. Автоматизируйте все процессы в своей клинике!
                    </div>
                </div>
                <div class="line line-2"><img src="../assets/Vector1.svg" alt=""></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.line-2{
    margin-left: 70px;
}
.line-1{
    margin-left: -100px;
}
.main{
    margin-top: 100px;
    display: flex;
    /* align-content: ; */
    align-items: center;
    justify-content: center;
    width: 100%;
}
.img-container{
    max-width: 705px;
    box-sizing: border-box;
    display: flex;
    align-items: center;
    justify-content: center;
}
.main-container{
display: flex;
align-items: center;
justify-content: center;

}

.text-title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #0F2A56;
}
.text-description{
    font-family: Montserrat;
font-style: normal;
font-weight:900;
font-size: 18px;
line-height: 22px;

color: #0F2A56;

}

@media screen and (max-width:945px) {
    .main-container{
        flex-direction: column;
    }
    .text-wrapper{
        text-align: center;
    }
    .text-container{
        width: 70%;
    }
    .line{
        display: none;
    }


    img{
        width: 70%;
    }
}


</style>