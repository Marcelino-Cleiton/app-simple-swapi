<template>
  <div id="app">
    <img src="./assets/download.png">
    <h1>{{ msg }}</h1>
    <b-button variant="outline-primary">Que a força esteja com você </b-button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Qual persongem de Star Wars você seria ?'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #feeb20;
  margin-top: 60px;
  background-color:#000000;
}

h1, h2 {
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
</style>
