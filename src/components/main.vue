<template>
    <div class="main">
        <div class="content-container">
             <div class="content">
                 <div class="content-title">
                            Находите нужного врача 
и записывайтесь на прием 
онлайн даже с телефона!
                 </div>
                 <div class="content-helper-text">
Мы максимально упрощаем поиск медцентров и специалистов и запись к ним!
                 </div>

                 <div class="buttons">

                  <div class="button b1">
                      <div class="button-text">
                         Записаться на прием
                      </div>
                  </div>

                  <div class="button">
                      <div class="button-text">
                         Стать специалистом
                      </div>
                  </div>

                 </div>

             </div>

             <div class="img">

             </div>
        </div>
    </div>
</template>


 <script>
// export default {
    // data:()=>({
    //     ipad:false
    // }),
    // mounted(){
//         const getUA = () => {
//     let device = "Unknown";
//     const ua = {
//         "Generic Linux": '/Linux/'+i,
//         "Android": /Android/i,
//         "BlackBerry": /BlackBerry/i,
//         "Bluebird": /EF500/i,
//         "Chrome OS": /CrOS/i,
//         "Datalogic": /DL-AXIS/i,
//         "Honeywell": /CT50/i,
//         "iPad": /iPad/i,
//         "iPhone": /iPhone/i,
//         "iPod": /iPod/i,
//         "macOS": /Macintosh/i,
//         "Windows": /IEMobile|Windows/i,
//         "Zebra": /TC70|TC55/i,
//     }
//     Object.keys(ua).map(v => navigator.userAgent.match(ua[v]) && (device = v));
//     return device;
// }

// console.log(getUA());
//     }
// }
</script>



<style scoped>
.buttons{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 600px;
    margin-top: 40px;

}
.button{
    background: #FFFFFF;
border: 1px solid #FFFFFF;
box-sizing: border-box;
box-shadow: 0px 2px 10px rgba(255, 255, 255, 0.15);
border-radius: 26px;
display: flex;
align-items: center;
justify-content: center;
width: 254px;
height: 52px;
}
.button-text{
font-family: Montserrat;
font-style: normal;
font-weight: 700;
font-size: 18px;
line-height: 22px;
/* identical to box height */


color: #0F2A56;
}
.main{
    width: 100%;
    height: 80vh;
    background: radial-gradient(149.04% 1096.52% at 99.9% 100%, #1BEFDC 0%, #24CEDA 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}
.content-container{
    width: 90%;
    height: 60%;
    display: flex;
}
.img{
 width: 100%;
 height: 165%;
 background: url("../assets/img.png") no-repeat;
 background-size: cover;
 margin-top: -100px;
}
.content-title{
    font-family: Montserrat;
font-style: normal;
font-weight: 600;
font-size: 48px;
line-height: 59px;
width: 700px;

}
.content-helper-text{
    margin-top: 30px;
    width: 500px;
    font-style: normal;
font-weight: normal;
font-size: 20px;
line-height: 24px;
}

@media screen and (max-width:1125px){
    .content-container{
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
    }
    .main{
        height: 130vh;
    }
    .img{
        margin-top: 0;
        background-size:473px 393px;
         width:  500px;
         height: 400px;
         /* margin-top: 150px; */
    }
    .content-container{
        /* margin-top: -120px; */
        height: 130vh;
    }
}

@media screen and (max-width:730px) {
    .content-title{
        font-size: 35px;
    }
    .buttons{
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .b1{
        margin-bottom:30px;
    }

    .content-container{
        width: 500px;
        justify-content: center;
        align-items: center;
    }
    .content-title{
        width: 500px;
        text-align: center;
    }
    .content-helper-text{
        text-align: center;
    }
}

@media screen and (max-width:594px) {
     .content-title{
     width: 400px;
     margin-left: 40px;
     }

     .content-helper-text{
         width: 300px;
         margin-left: 50px;
     }

}


@media screen and (max-width:471px) {
    .content{
        margin-left: 150px;
    }
    .content-container{
        width: 500px;
        justify-content: center;
        align-items: center;
    }
    .content-title{
        width: 300px;
        text-align: center;
    }
    .content-helper-text{
        text-align: center;
    }
    .button{
        margin-left: -150px;
    }
}

@media screen and (max-width:380px) {
    .content{
        align-items: center;
        justify-content: center;
        display: flex;
        flex-direction: column;
        margin-left: -40px;
    }
    .content-title{
        text-align: center;
        width: 250px;
    }
    .content-helper-text{
        text-align: center;
        width: 250px;
    }
    .buttons{
        margin-left: 180px;
    }
    
    
}
</style>