<template>
  <div id="app">
    <h1 class="animate__animated animate__bounce">CALCULATOR VUE</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from './main/Calculator'
export default {
  components: { Calculator }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap");

*,
html,
body {
  font-family: "Roboto", sans-serif;  
  box-sizing: border-box;
  margin: 0;
}

h1 {
  padding: 2rem;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #00f260; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #0575e6,
    #00f260
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #0575e6,
    #00f260
  );   
}
</style>
