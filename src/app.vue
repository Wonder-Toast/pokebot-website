<div id="app">
    <img src="http://vuejs.org/images/logo.png">
    <h1>\{{ msg }}</h1>
    <h2>Github Build</h2>
    <ul>
      <li><a href="https://www.github.com/YaBoyWonder" target="_blank">Github</a></li>
    </ul>
  </div>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome To PokeBot!'
    }
  }
}
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #A4322B;
  margin-top: 42px;
}
img {
  width: 110px;
  height: 400px;
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
  margin: 0 13px;
}
a {
  color: #F15252;
}
</style>
