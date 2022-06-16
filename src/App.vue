<template>
    <div>
      <Home />
      <Journey />
      <About />
    </div>
</template>

<script>
/* eslint-disable */
import Home from './pages/Home';
import Journey from './pages/Journey';
import About from './pages/About';
// eslint-disable-line
export default {
  name: 'App',
  components: {
    Home,
    Journey,
    About,
  },
};
</script>

<style scoped>
body{
  background-color:#FFF;
}
.container {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding: 0px;
  background-color:#FFF;
  min-height: 100vh;

}
.background-name{
  text-align:center;
  font-size: 10rem;
  color:#232324;
}


</style>
