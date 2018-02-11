<template>
  <div id="app">
    <!-- <img class="logo" src="./assets/logo.png"> -->
    <hello></hello>
    <message></message>
    <p>
      Welcome!
    </p>
    <p>
      This is a simple app that shows integration with Firebase.
    </p>
    <p>
    I'm also trying to prove that I can make changes to this repository from codesandbox.io.
    </p>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Message from './components/Message'
import store from './vuex/store'

export default {
  store,
  components: {
    Hello,
    Message
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
