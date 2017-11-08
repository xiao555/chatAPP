<template>
  <div id="app">
    <HelloWorld/>
    <Chat/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Chat from './components/Chat'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Chat
  }
}
</script>

<style lang="stylus">
@import url("../node_modules/font-awesome/css/font-awesome.css")

*, *:after, *:before
  box-sizing: border-box

ul
  list-style none
  word-wrap break-word

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
