<template>
  <div id="app">
    <img src="./assets/images/pokeball.png" />
    <h1>{{ msg }}</h1>
    <h2>Links</h2>
    <ul>
      <li><a href="https://pokeapi.co/" target="_blank">pokeapi</a></li>
      <li><a href="https://github.com/APIs-guru/graphql-apis" target="_blank">apis</a></li>
      
    </ul>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Pokedex",
    };
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

img { 
  width: 10%;
  opacity: 0.5;
}
</style>
