<template>
  <v-app class="calculator">    
        <Calculator />
  </v-app>
</template>

<script>
import Calculator from './main/Calculator';

export default {
  components: { Calculator }
};
</script>

<style>  
  *, html, body {
    margin: 0;
    text-align: center;
  }
 
  .calculator{
    margin: 0 auto;
    text-align: center;
    margin-top: .5rem;
  }
</style>