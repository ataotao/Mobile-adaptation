<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Test msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Test from './components/Test.vue'

export default {
  name: 'app',
  components: {
    Test
  }
}
</script>

<style>
  body,div,li,ol,p,td,th,ul{margin:0;padding:0}li{list-style:none}img{border:0;-webkit-user-select:none;user-select:none;-webkit-touch-callout:none;touch-callout:none}table{border-spacing:0;border-collapse:collapse}html{font-family:sans-serif;-webkit-user-select:none;user-select:none;-webkit-text-size-adjust:100%;-ms-text-size-adjust:100%}:focus{outline:0}:link,:visited{text-decoration:none}a:active,a:hover{outline:0}.clearfix:after{display:block;clear:both;height:0;font-size:0;content:''}.pull-left{float:left}.pull-right{float:right}.show{display:block!important}.hide{display:none!important}.visible{visibility:visible}.invisible{visibility:hidden}.text-left{text-align:left}.text-center{text-align:center}.text-right{text-align:right}.dv{display:inline-block;vertical-align:middle}.di{display:inline-block}.text-hide{border:0;background-color:transparent;font:0/0 a;color:transparent;text-shadow:none}.text-ellipsis{overflow:hidden;white-space:nowrap;text-overflow:ellipsis}.btn{display:inline-block;cursor:pointer;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;text-align:center;vertical-align:middle;white-space:nowrap;-webkit-tap-highlight-color:transparent}.btn:hover{text-decoration:none};*{-webkit-box-sizing:border-box;box-sizing:border-box}

body{
  width: 16rem;
  margin: 0 auto;
  padding: 0;
}

#app {


  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
