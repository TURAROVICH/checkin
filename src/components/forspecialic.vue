<template>
    <div id="special" class="main">
           <div class="special-container">
               <div class="img"><img src="../assets/Group4.png" alt=""></div>
                <div class="special-title">
Специалистам
                </div>

                <div class="description-1">Медицинские специалисты могут и сами добавлять информацию о себе в нашу систему. При этом вы получите огромную аудиторию потенциальных клиентов и удобный сервис.</div>
                <div class="description-2">Специалисты смогут отслеживать запись на прием и составлять удобный для себя график работы.
</div>
                <div class="description-3">Используя нашу систему, специалисты не тратят время и нервы 
на рутину, следовательно, доброжелательно относятся к клиентам. 
А пациенты все больше проявляют лояльность к клинике.</div>

           </div>
    </div>
</template>

<style scoped>
.description-1,.description-2,.description-3{
    font-size: 18px;
line-height: 22px;
}
.description-1{
    margin-top: 15px;
}
.description-2{
    margin-top: 10px;
}
.description-3{
    margin-top: 10px;
}
.main{
    margin: 0;
    width: 100%;
    min-height: 100vh;
    background:url("../assets/Group4.png") no-repeat, url("../assets/gr5.png") no-repeat ;
    background-position: 700px 0,left top;
    background-size: auto 400px,100% 430px;
    display: flex;
    align-items: center;
    justify-content:flex-start;
}
.special-container{
    height: 500px;
    width: 650px;
    margin-left: 100px;
    margin-top: 20px;
    position: relative;
}
.special-title{
    font-weight: 600;
font-size: 36px;
line-height: 44px;
/* identical to box height */


color: #FFFFFF;
}

.img{
     display: none;
     visibility: hidden;
}
@media screen and (max-width:1125px){
    .main{
           background: url("../assets/Mask1.png") no-repeat ;
    background-position: bottom center;
    background-size: 100% 100%;
    margin-top: 140px;
    }
    .special-container{
        margin: 0 0 0 20%;
        padding-top: 25% ;
    }
    .img{
        display: block;
        visibility: visible;
        top: -200px;
        position: absolute;
    }
}

@media screen and (max-width:912px){
    .special-container{
        padding-top: 300px;
    }
}

@media screen and (max-width:786px) {
    .special-container{
        margin: 0 0 0 100px;
        padding-top: 250px;
    }
    
}
@media screen and (max-width:718px) {
    .special-container{
        margin: 0 0 0 60px;
        padding-top: 200px;
    }
    .img{
         top: -250px;
         left: -50px;
    }
    .main{
        margin-top: 200px;
    }
    
}


@media screen and (max-width:594px) {
    .main{
        margin-top: 250px;
    }

    img{
      width: 120%;
    }
}

@media screen and (max-width:574px) {

    .img{
      width: 90%;
      top: -190px;
    }
    .main{
        margin-top: 150px;
        background-size: cover;
    }
    .special-container{
        margin-top: -60px;
    }
    
}

@media screen and (max-width:436px) {
    .main{
        background: #000;
        height: 130vh;
    }
    .description-1,.description-2,.description-3{
    margin-left: -30px;
}
}
</style>