<template>
  <div class="container">
    <nav class="navbar">
      <h1>Cold Cofee</h1>
      <div>
        <ul>
          <li>Home</li>
          <li>Preços</li>
          <li>Contato</li>
        </ul>
      </div>
      <div class="icons">
        <ul>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
    </nav>
    <!-- <img class="img" src="../assets/cafetop.png" alt=""> -->
    <div class="central">
      <h1 class="titulo">COLD CREAM</h1>
      <div class="forma"></div>
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
.container {
  color: #FEFEFE;
  background-color: #008f5a;
  width: 100vw;
  height: 100vh;
}

.central{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.titulo{
  font-size: 30vh;
  height: 37.5vh;
  font-family: Barlow-SemiBold, sans-serif;
  display: inline-block;
  transform: scale(1, 1.6);
  transform-origin: center;
  line-height: normal;
}

.forma{
  background-color: #4bff87;
  height: 25vh;
  width: 28vw;
  border-radius: 0px 0px 200px 200px;
}

.img{
  width: 16%;
  position: absolute;
  left: 42vw;
  top: 11vh;
}
</style>
