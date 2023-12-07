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
</div>

</template>



<style scoped>

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

  

</style>
