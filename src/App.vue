<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="fundo">
    <img src="../src/assets/Rectangle 8.png" class="img">

  </div>
      <nav class="navbar">
        <div class="container-fluid">
    <a class="linkcor" href=""><h1 class="titulo">MVP Games</h1></a>
    </div>

    <div>

        <RouterLink class="champions" to="/">CHAMPIONS</RouterLink>
        <RouterLink class="runes" to="/about">RUNES</RouterLink>
        <RouterLink class="rank" to="/about">RANK</RouterLink>
    </div>

    <div>
    <form class="d-flex">
      <input class="pesquisa" type="search" placeholder="     SEARCH CHAMPIONS OR SUMMONER" aria-label="Search">
    </form>
  </div>

      </nav>

  <RouterView />

  <div class="retangle">
  <h2 class="winrate">Win Rate</h2>
  <div class="progress">
  <div class="progress-bar bg-success" style="width:65%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-success" style="width:59%"></div>
</div>
<p class="porce">51,90%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-success" style="width:48%"></div>
</div>
<p class="porce">51,89%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-success" style="width:30%"></div>
</div>
<p class="porce">51,84%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
  
</div>


<div class="retangle2">
  <h2 class="winrate">Ban Rate</h2>
  <div class="progress">
  <div class="progress-bar bg-danger" style="width:29%"></div>
</div>
<p class="porce">29,12%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
  <br>
  <div class="progress">
  <div class="progress-bar bg-danger" style="width:16%"></div>
</div>
<p class="porce">16,33%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-danger" style="width:14%"></div>
</div>
<p class="porce">14,62%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-danger" style="width:13%"></div>
</div>
<p class="porce">13,46%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
  

<div class="retangle3">
  <h2 class="winrate">Pick Rate</h2>
  <div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
  <br>
  <div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
  <br>
  <div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="pick" src="../src/assets/campeao.png" alt="">
</div>

  

</div>







</template>



<style scoped>

.pick{
  filter: brightness(2.1);
  width: 10%;
  margin-left: 8.5%;
  margin-top: -18%;
  border-radius: 20%;
}

.img{
  background-repeat: no-repeat, repeat;
  height:100vh;
  width: 100vw;
  margin-top:8%;

  background-position-y: -17%;
  background-size: 100%;
  margin-bottom: 50%;
  position: absolute;
  filter: brightness(1);
  


}
header {
  line-height: 1.5;
  max-height: 100vh;
}




nav a.router-link-exact-active {
  color: var(--color-text);
}





.navbar{
  background: linear-gradient(180deg, #A4B2FF 0%, rgba(0, 41, 255, 0.20) 0.01%, rgba(0, 163, 255, 0.20) 47.4%, rgba(0, 240, 255, 0.10) 100%, rgba(0, 240, 255, 0.20) 100%);
    height: 150px;

}
.pesquisa{
  margin-right: 50%;
  margin-left: 2%;
  margin-bottom: 50px;
  border-radius: 10px;
  width: 1000px;
height: 35px;
align-items: center;
}

.titulo{
  margin-left: 100px;
 margin-top: 20px;
  font-family: Marko One;
font-size: 40px;
font-style: normal;
font-weight: 400;
line-height: normal;
background: linear-gradient(180deg, #0A05FF 0%, #DB00FF 100%);
background-clip: text;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}

.linkcor{
  color: red;
  text-decoration: none;
}

.champions{
  margin-left: 100px;
  color: #000;
font-family: Marcellus SC;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;

}

.runes{
  margin-left: 10px;
  color: #000;
font-family: Marcellus SC;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;

}

.rank{
  margin-left: 20px;
  color: #000;
font-family: Marcellus SC;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;
}

.retangle{
  width: 500px;
height: 780px;
border-radius: 110px;
background: rgba(187, 210, 255, 0.12);
position: absolute;
margin-left: 50px;
margin-top: 20px;
filter:contrast(5);
}
.winrate{
  margin-left: 3.5%;
  margin-top: 5%;
  color: #FFF;
text-align: center;
font-family: Manjari;
font-style: normal;
line-height: normal;
}
  
.progress{
  width: 35%;
  height: 5%;
  margin-left: 23%;
  margin-top: 20%;
  
}

.retangle3{
  width: 500px;
height: 780px;
border-radius: 110px;
background: rgba(187, 210, 255, 0.12);
position: absolute;
margin-left: 650px;
margin-top: -145%;
filter:contrast(5);
}
.retangle2{
  width: 500px;
height: 780px;
border-radius: 110px;
background: rgba(187, 210, 255, 0.12);
position: absolute;
margin-left: 700px;
margin-top: 20px;
filter:contrast(5);
}

.progress{
  width: 35%;
  height: 5%;
  margin-left: 23%;
  margin-top: 20%;
  
}

.porce{
  margin-left: 63%;
  margin-top: -6%;
  color: #000;
font-family: Farro;
font-size: 25px;
font-style: normal;
font-weight: 500;
line-height: normal;
}
</style>
