<template>
  <div id="app">
    <Navbar></Navbar>
    <h1>7 Wonders Of Oregon</h1>
    <Home></Home>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Home from './components/Home'

export default {
  name: 'App',
  components: {
    Navbar,
    Home
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Otomanopee+One&display=swap');
#app {
  font-family: 'Otomanopee One', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

h1{
  padding: 0;
  margin: 50px;
}
</style>
