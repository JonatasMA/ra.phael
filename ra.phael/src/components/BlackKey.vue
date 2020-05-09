<template>
  <div class="blackKey">
    <audio id="ra_phael" src="contents/phael.mp3"></audio>
  </div>
</template>

<script>
export default {
  name: 'BlackKey',
  props: {
    note: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.blackKey {
    background-color: black;
    border: 1px solid #fff;
    width: 64px;
    height: 150px;
}
</style>
