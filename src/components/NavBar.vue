<template>
  <div class="container">
    <nav class="navbar">
      <h1 class="logo">Cold Cofee</h1>
      <div>
        <ul class="nav">
          <li><a href="">Home</a></li>
          <li><a href="">Prices</a></li>
          <li><a href="">Contact</a></li>
        </ul>
      </div>
      <div class="icons">
        <ul>
          <li><i class="pi pi-search" style="font-size: 1.5rem; color: white;"></i></li>
          <li><i class="pi pi-user" style="font-size: 1.5rem; color: white"></i></li>
          <li><i class="pi pi-user-plus" style="font-size: 1.5rem; color: white"></i></li>
        </ul>
      </div>
    </nav>
    <img class="img" src="../assets/cafetop.png" alt="Imagem maior de Café com cobertura">
    <div class="central">
      <h1 class="titulo">COLD CREAM</h1>
      <p class="linha"></p>
      <div class="forma"></div>
      <h3 class="sabores">Coffee with Vanilla<img class="estrela" src="../assets/estrela.png">Cofee with Caramel<img
          class="estrela" src="../assets/estrela.png">Coffe with Chocolate</h3>
      <h3 class="sabores">Coffe with Almond Milk<img class="estrela2" src="../assets/estrela.png">Coffe with Mint</h3>
    </div>

    <div class="lateral">
      <h5 class="texto">Experience the freshness of iced coffee and add a unique touch
        to your day! Refreshing, energizing and irresistible, it is the perfect choice
        for coffee lovers looking for an intense flavor at any time. Come try it and fall
        in love with this refreshing experience!
      </h5>
      <img class="original" src="../assets/100.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #fefefe;
  cursor: pointer;
}

.container {
  color: #FEFEFE;
  background-color: #005e3b;
  height: 100vh;
}

.navbar,
.nav,
.icons ul {
  display: flex;
  flex-direction: row;
  align-items: center;
  font-family: Barlow-SemiBold, sans-serif;
}

.navbar {
  height: 10vh;
  padding: 1%;
  gap: 25vw;
}

.logo {
  font-size: 4vh;
}

.nav {
  gap: 10vw;
  font-size: 2vh;
  z-index: 99999;
}

.icons ul {
  gap: 2vw;
}

.central {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 8vh;
}

.titulo {
  font-size: 30vh;
  height: 41vh;
  font-family: Barlow-SemiBold, sans-serif;
  display: inline-block;
  transform: scale(0.9, 2);
  transform-origin: center;
  line-height: normal;
  user-select: none;
}

.linha {
  position: absolute;
  height: 1vh;
  width: 74vw;
  background-color: #005e3b;
  top: 36vh;
}

.forma {
  background-color: #4bff87;
  height: 25vh;
  width: 24vw;
  border-radius: 0px 0px 200px 200px;
}

.img {
  width: 15%;
  position: absolute;
  left: 42.5vw;
  top: 26.3vh;
  border-radius: 0px 0px 100px 100px;
  z-index: 9999;
}

.lateral {
  display: flex;
  flex-direction: row;
  align-items: center;
  position: absolute;
  justify-content: space-around;
  gap: 20vw;
  top: 60vh;
}

.texto {
  margin-left: 9vw;
  width: 24vw;
  font-size: medium;
  font-family: Barlow-SemiBold, sans-serif;
}

.original {
  width: 12%;
}

.sabores {
  margin-top: 1vh;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  font-family: Barlow-SemiBold, sans-serif;
}

.estrela {
  width: 3%;
}

.estrela2 {
  width: 4.5%;
}
</style>
