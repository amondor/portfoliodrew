<template>
  <div id="app">
     <HelloWorld hello="👋🏽 HELLO MY NAME IS ANDREW"/>
     <HelloWorld button="https://www.malt.fr/profile/andrewmondor"/>
    <HelloWorld msg="I’m a Freelance Software Engineer from Guadeloupe, France. 🇫🇷"/>
    <HelloWorld paragraph="I craft high-performing, beautiful websites that are conversion-focused, brand-accurate & people-friendly." />
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Futura, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 200px;
  margin-left: 150px;
  width: 600px;
  font-size: 22px;

}
</style>
