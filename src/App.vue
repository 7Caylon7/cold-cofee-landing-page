<template>
  <NavBar/>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar
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

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
