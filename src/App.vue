<template>
  <Navbar />
  <Landing />
  <img class="vector" src="./assets/vector.png" alt="">
</template>

<script>
import Navbar from './components/Navbar'
import Landing from './components/Landing'

export default {
  name: 'App',
  components: {
    Navbar,
    Landing
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}

.vector {
  position: absolute;
  bottom: 0rem;
  left: 0;
  z-index: -1;
  width: 100vw;
  height: 50vh;
}
</style>
