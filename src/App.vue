<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app{
  display: flex;
  align-items: center;
  justify-content: center;
}
body {
    margin: 0px;
    padding: 0px
  }
html{
  box-sizing: border-box;
}
*, *::before, *::after{
  box-sizing: inherit;
  text-decoration: none;
  outline: none;
}
</style>
