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

    <div>

        <img src="./assets/VOICE OVER_Page_1.png" width="500" height="auto">

    </div>
    <p id='titles'>
      <b-container>
        <b-row>
      
      <b-col>
        <h5>Commercial Demo</h5>
        <audio src="./assets/MarkWoodC1.mp3" type="audio/mpeg" controls></audio>
      </b-col>
      
      <b-col>
        <h5>Narration Demo</h5>
        <audio src="./assets/MarkWoodN.mp3" type="audio/mpeg" controls></audio>
      </b-col>
      
        </b-row>
      </b-container>
    </p>
    <p>
      <h4 style="padding-top: 40px; padding-bottom: 15px;"> About Me </h4>
      <b-container>
        <b-row>
          <b-col>
            <img src="./assets/Mark.jpg" width="250px" height='auto' id='right'>
          </b-col>
          <b-col>
          <div id='left'>
			I am located in the East San Francisco Bay Area. My voice has been described as, “A strong voice that is deep and inviting with a sharp, confident tone.”
			<p>
			My past experience in radio as well as many years of public speaking and in teaching  (MA in education) provide a great foundation for your voice over project. I will give your project that confidence and trust you are looking for. Contact me today to discuss how we can bring your project to life.</p>
		</div>
          </b-col>
          
        </b-row>
      </b-container>
    </p>
    <p>
      <h4 style="padding-top: 40px; "> Contact </h4>
      <b-container>
        <b-row>
          <b-col>
	<p><h5>Email: <i>markwoodvotalent@gmail.com</i></h5></p>
	<p><h5>Phone: 925-206-9070</h5></p>
          </b-col>
        </b-row>
      </b-container>
    </p>


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
#titles {
  margin-top: 25px;
}
h1, h2 {
  font-weight: normal;
}
#left {
  text-align: left !important;
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
