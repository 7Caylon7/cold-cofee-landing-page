<template>
  <NavBar/>
  <SecondComp/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SecondComp from './components/SecondComp.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    SecondComp
  }
}
</script>

<style>
@font-face {
  font-family: 'Barlow-SemiBold';
  src: url('@/assets/fonts/Barlow-SemiBold.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

:root {
    --primary-color: #005e3b;
    --accent-color: #4bff87;
    --font-family: Barlow-SemiBold, sans-serif;
}


*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
}


i{
  cursor: pointer;
}
</style>
