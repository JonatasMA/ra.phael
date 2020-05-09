<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <div class="keys">
      <WhiteKey note="C"/>
      <BlackKey note="C#"/>
      <WhiteKey note="D"/>
      <BlackKey note="D#"/>
      <WhiteKey note="E"/>
      <WhiteKey note="F"/>
      <BlackKey note="F#"/>
      <WhiteKey note="G"/>
      <BlackKey note="G#"/>
      <WhiteKey note="A"/>
      <BlackKey note="A#"/>
      <WhiteKey note="B"/>
    </div>
  </div>
</template>

<script>
import WhiteKey from './components/WhiteKey.vue'
import BlackKey from './components/BlackKey.vue'

export default {
  name: 'App',
  components: {
    WhiteKey,
    BlackKey
  }
}
</script>

<style>
.keys {
  display: flex;
  flex-direction: row;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: aquamarine;
}
</style>
