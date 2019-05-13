<template>

  <div id="app">
    
    <b-container-fluid>

      <b-nav tabs align='center'>
        <b-col></b-col>
        <b-col>
          <b-nav-item>About</b-nav-item>
          <img src="./assets/logo2.png" width="70px" height='50' >
          <b-nav-item>Contact</b-nav-item>
        </b-col>
        <b-col></b-col>
      </b-nav>
      </b-col>
    </b-container-fluid>

  </div>
</template>

<script>
import BCard from 'bootstrap-vue/es/components/card/card'
import BCardBody from 'bootstrap-vue/es/components/card/card-body'
import BCardFooter from 'bootstrap-vue/es/components/card/card-footer'
import BCardHeader from 'bootstrap-vue/es/components/card/card-header'
import BCardImg from 'bootstrap-vue/es/components/card/card-img'
import BTable from 'bootstrap-vue/es/components/table/table'

export default {
  name: 'app',
  components: {
    BCard,
    BCardBody,
    BCardFooter,
    BCardHeader,
    BCardImg,
    BTable
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  justify-content: center;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 15px;
  margin-bottom: 5px;
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
