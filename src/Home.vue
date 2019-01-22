<template>
  <div id="container">
<!--    <div id="app">
      <img src="./assets/wiley-wordmark.png">
      &lt;!&ndash;<h1>{{ msg }}</h1>&ndash;&gt;
    </div>-->
    <app-header></app-header>
<!--
    <app-footer></app-footer>
-->
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

/* this is temporary for header */
/*background-color: moccasin;*/
/*border-width: 1px;*/
/*border-style: solid;*/
/*border-color: #1b1c1d;*/

}

</style>
