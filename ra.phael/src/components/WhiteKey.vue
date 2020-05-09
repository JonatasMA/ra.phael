<template>
  <div class="whiteKey">
    <audio id="ra_phael" src="contents/phael.mp3"></audio>
  </div>
</template>

<script>
export default {
  name: 'WhiteKey',
  props: {
    note: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.whiteKey {
    background-color: #FFF;
    border: 1px solid black;
    width: 64px;
    height: 300px;
}
</style>
