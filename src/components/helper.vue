<template>
<div class="main">
             <div class="helper-container">
             <div class="cards">

    <a href="#about">
                 <div class="card active">
                 
                  <div class="icon">
                      <img src="../assets/Group.png" alt="">
                  </div>
                  <div class="title">
                       Кто мы?
                  </div>
                  
                 </div>
                  </a>

<a href="#special">
                 <div class="card">
                  <div class="icon">
                      <img src="../assets/Vector.svg" alt="">
                  </div>
                  <div class="title">
                      Специалистам
                  </div>
                 </div>
</a>


<a href="#about1">
                 <div class="card">
                  <div class="icon">
                      <img src="../assets/Vector4.png" alt="">
                  </div>
                  <div class="title">
                     О нас
                  </div>
                 </div>
</a>


<a href="#advantages">
                 <div class="card">
                  <div class="icon">
                      <img src="../assets/Group1.png" alt="">
                  </div>
                  <div class="title">
                        Преимущества
                  </div>
                 </div>
</a>


<a href="#mission">
 <div class="card">
                  <div class="icon">
                      <img src="../assets/v.png" alt="">
                  </div>
                  <div class="title">
                        Наша миссия
                  </div>
                 </div>
</a>


<a href="#pather">
                 <div class="card">
                  <div class="icon">
                      <img src="../assets/Group2.png" alt="">
                  </div>
                  <div class="title">
                  Партнерам
                  </div>
                 </div>
</a>

<a href="#contacts">
                 <div class="card">
                  <div class="icon">
                      <img src="../assets/Group3.png" alt="">
                  </div>
                  <div class="title">
                    Контакты
                  </div>
                 </div>
</a>

             

             </div>
         </div>
</div>
</template>


<style scoped>
a{
    text-decoration: none;
}
.cards{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    flex-wrap: wrap;
}
.main{
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 20px;
    padding: 30px;
}

.card{
    margin: 10px;
    background: #4F4F4F;
border-radius: 8px;
width: 243px;
height: 52px;
    display: flex;
    align-items: center;
    justify-content: center;

}

.icon{
   margin: 5px;
}

.active{
    background: radial-gradient(149.04% 1096.52% at 99.9% 100%, #1BEFDC 0%, #24CEDA 100%);
}
</style>