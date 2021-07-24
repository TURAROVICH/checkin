<template>
    <div class="main">
         <div class="side-bar-container">

              <div class="side-bar-component">
                  <div class="icon">
                      <img src="../assets/Group.png" alt="">
                  </div>

                  <div class="title">
                       Кто мы?
                  </div>
              </div>

              <div class="side-bar-component">
                  <div class="icon">
                      <img src="../assets/Vector.svg" alt="">
                  </div>

                  <div class="title">
                       Специалистам
                  </div>
              </div>


                  <div class="side-bar-component">
                  <div class="icon">
                      <img src="../assets/Vector4.png" alt="">
                  </div>

                  <div class="title">
                       О нас
                  </div>
              </div>

                <div class="side-bar-component">
                  <div class="icon">
                      <img src="../assets/Group1.png" alt="">
                  </div>

                  <div class="title">
                       Преимущества
                  </div>
              </div>

                 <div class="side-bar-component">
                  <div class="icon">
                      <img src="../assets/Group2.png" alt="">
                  </div>

                  <div class="title">
                      Партнерам
                  </div>
              </div>


                 <div class="side-bar-component">
                  <div class="icon">
                      <img src="../assets/Group3.png" alt="">
                  </div>

                  <div class="title">
                   Контакты
                  </div>
              </div>

         </div>
    </div>
</template>

<style scoped>
.side-bar-container{
    width: 1000px;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 4em;
}
.side-bar-component{
   display: flex;
   align-items: center;
   justify-content: space-around;
   width: 100px;
   gap: 20px;
}
.main{
    width: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #4F4F4F;
}
.title{
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 20px;
}

@media screen and (max-width : 1000px) {
    .main{
        display: none;
        overflow: hidden;
    }
}
</style>