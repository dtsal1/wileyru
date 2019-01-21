<template>
  <div id="container">
    <div id="app">
      <img src="./assets/wiley-wordmark.png">
      <!--<h1>{{ msg }}</h1>-->
    </div>
    <app-header></app-header>
    <app-footer></app-footer>
  </div>

</template>

<script>
import wileyHeader from "./components/wileyHeader";
import wileyFooter from "./components/wileyFooter";
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    appHeader: wileyHeader,
    appFooter: wileyFooter
  }
}
</script>

<style>

#container {
background-color: moccasin;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 20px;
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
  margin: 0 20px;
}

a {
  color: #86b983;
}
</style>
