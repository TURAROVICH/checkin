<template>
    <div id="contacts" class="main">
        <div class="main-container">
            <div class="logo-wrapper">
                <div class="logo">
                   <img src="../assets/logo.png" alt="">
                </div>
            </div>

            <div class="line"></div>

            <div class="support">
       

       <div class="media">
                  <div class="our-1">
                         <div class="title">Мы в социальных сетях</div>

                         <div class="lists">
                             <ul class="flex">
                                 <li><img src="../assets/facebook.png" alt=""></li>
                                 <li><img src="../assets/instagram.png" alt=""></li>
                                 <li><img src="../assets/ok.png" alt=""></li>

                             </ul>
                         </div>
                    </div>



                     <div class="our-app-1">
                         <div class="title">Ищите наше приложение</div>

                         <div class="lists">
                             <ul class="app">
                                 <li><img src="../assets/play-market.png" alt=""></li>
                                 <li><img src="../assets/app-store.png" alt=""></li>

                             </ul>
                         </div>
                    </div>

</div>



                <div class="support-wrapper">


                    <div class="contacts">
                         <div class="title">Контакты</div>

                         <div class="lists">
                             <ul>
                                <li><img class="mail" src="../assets/mail.png" alt=""> checkin.kg@gmail.com</li>
                                 <li><img class="phone" src="../assets/phone.svg" alt="">+996 755 338 338</li>
                                 <li>+996 702 338 338</li>
                                 <li>+996 776 338 338</li>
                             </ul>
                         </div>
                    </div>


    <div class="navigation">
                         <div class="title">Навигация</div>

                         <div class="lists">
                             <ul>
                                 <li>Специалисты</li>
                                 <li>Учреждения</li>
                                 <li>Помощь</li>
                                 <li>О нас</li>
                             </ul>
                         </div>
                    </div>


  <div class="manage">
                         <div class="title">Управление</div>

                         <div class="lists">
                             <ul>
                                 <li>Стать специалистом</li>
                                 <li>Стать учреждением</li>
                             </ul>
                         </div>
                    </div>


  <div class="our">
                         <div class="title">Мы в социальных сетях</div>

                         <div class="lists">
                             <ul class="flex">
                                 <li><img src="../assets/facebook.png" alt=""></li>
                                 <li><img src="../assets/instagram.png" alt=""></li>
                                 <li><img src="../assets/ok.png" alt=""></li>

                             </ul>
                         </div>
                    </div>



                     <div class="our-app">
                         <div class="title">Ищите наше приложение</div>

                         <div class="lists">
                             <ul class="app">
                                 <li><img src="../assets/play-market.png" alt=""></li>
                                 <li><img src="../assets/app-store.png" alt=""></li>

                             </ul>
                         </div>
                    </div>




                </div>




<div class="media-1">

                     <div class="our-app-1">
                         <div class="title">Ищите наше приложение</div>

                         <div class="lists">
                             <ul class="app">
                                 <li><img src="../assets/play-market.png" alt=""></li>
                                 <li><img src="../assets/app-store.png" alt=""></li>

                             </ul>
                         </div>
                    </div>


 <div class="manage-1">
                         <div class="title">Управление</div>

                         <div class="lists">
                             <ul>
                                 <li>Стать специалистом</li>
                                 <li>Стать учреждением</li>
                             </ul>
                         </div>
                    </div>

                     
</div>

<div class="our-1">
                         <div class="title">Мы в социальных сетях</div>

                         <div class="lists">
                             <ul class="flex">
                                 <li><img src="../assets/facebook.png" alt=""></li>
                                 <li><img src="../assets/instagram.png" alt=""></li>
                                 <li><img src="../assets/ok.png" alt=""></li>

                             </ul>
                         </div>
                    </div>




            </div>
        </div>
    </div>
</template>

<style scoped>
.media-1{
    display: none;
}
.mail,.phone{
    position: absolute;
    left: -30px;
}
li{
    display: flex;
    align-items: center;
    justify-content: flex-start;
    position: relative;
}
.logo-wrapper{
    /* padding: 50px; */
    margin-top: -50px;
    margin-bottom: 50px;
}
.app{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.flex{
    width: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.lists{
    display: flex;
    align-items: flex-start;
    justify-content: flex-start;
}
.support-wrapper{
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    width: 1000px;
}
.title{
    font-weight: 600;
font-size: 16px;
line-height: 20px;
margin-bottom: 20px;

}
li{
    list-style: none;
    font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 20px;
}

.main{
    width: 100%;
    height: 50vh;
    display: flex;
    align-items: center;
    justify-content: center;
     background: #24CEDA;
     margin-top: 100px;
}

.main-container{
    width: 80%;
    display: flex;
    align-items: flex-start;
    justify-content: flex-start;
    flex-direction: column;
}

.media{
    display: none;
}
.our-1{
    display: none;
}
@media screen and (max-width:1200px) {
    .support-wrapper{
        width: auto;
    }
    .main{
        height: 55vh;
    }
    .line{
        border: 1px solid #1EC7D2;
        width: 105%;
        height: 2px;
        margin-left: -50px;
        margin: -20px 0 30px 0;
    }


}

@media screen and (max-width:1030px) {

    .support-wrapper{
        width: 600px;
        padding: 30px;
    }
    .our{
        display: none;
    }
    .our-app{
        display: none;
    }

    .support{
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    flex-direction: column;
}
.media{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.our-app-1{
    margin-left: 30px;
}

.main{
    height: 80vh;
}

}


@media screen and (max-width:723px) {
        .our-1{
        display: block;
    }
    .main-container{
    width: 400px;
    }
    .line{
        width: 40%;
    }
     .support-wrapper{
        width: 400px;
        padding: 0px;
    }
    .support-wrapper{
        flex-wrap: wrap;
    }
    .media{
        display: none;
    }
    .manage{
        display: none;
    }
    /* .flex{
        width: auto;
    } */
    .main{
        justify-content: center;
    }
    .media-1{
        display: flex;
        justify-content: flex-start;
        align-items: flex-start;
        /* flex-wrap: wrap; */
        margin-top: 30px;
        margin-left: -80px;
    }
    .manage-1{
        margin-left: 70px;
    }

    .our-1{
        margin-left: -50px;
        margin-top: 50px;
    }

}


@media screen and (max-width:530px) {
   .media-1{
       margin-left: -40px;
   }

    .our-1{
        margin-left: -10px;
        margin-top: 50px;
    }
    .main{
        height: 100vh;
    }
    
}


@media screen and (max-width:500px) {
  .support-wrapper{
      flex-wrap: wrap;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
  }
  .navigation{
      margin-top: 50px;
  }
  .main{
      height: 140vh;
  }
  .media-1{
      flex-direction: column;
      align-items: center;
      justify-content: center;
      margin-left: 30px;
      margin: 50px;
  }
  .manage-1{
      margin-top: 50px;
  }
   .our-1{
       margin-left: 100px;
   }
   .logo-wrapper{
       justify-content: center;
       align-items: center;
       margin-left: 30px;
   }
}
</style>