<template>
  <Navbar />
  <Landing />
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
</style>
