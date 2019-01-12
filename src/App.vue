<template>
  <div id="app">
    <vue-typed-js :strings="['Gerwin en Sophie']" :showCursor="false">
      <h1 class="typing"></h1>
    </vue-typed-js>
    <vue-typed-js :strings="['22 juni 2019']" :startDelay="2000" :showCursor="false">
      <h2 class="typing"></h2>
    </vue-typed-js>
    <vue-typed-js :strings="['Informatie volgt...']" :startDelay="3500" :showCursor="false">
      <h3 class="typing"></h3>
    </vue-typed-js>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  // components: {
  //   HelloWorld
  // }
}
</script>

<style>
@media only screen and (min-width: 600px) {
  h1 {
    font-size: 80px;
    margin-bottom: 0px;
  }

  h2 {
    font-size: 60px;
  }

  h3 {
    font-size: 30px;
  }
}

h2 {
  font-weight: 400;
}

h3 {
  margin-top: 100px;
  font-style: italic;
  font-weight: 200;
}

.typed-element {
  justify-content: center;
}

#app {
  font-family: 'Montserrat', Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  @media only screen and (min-width: 600px) {
   margin-top: 60px; 
  }
}
</style>
