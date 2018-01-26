<template>
  <div class="wrapper">
    <h1 class="heading">
      <span>ず</span>
      <span>や</span>
      <span>か</span>
      <span>い</span>
    </h1>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'づやかい'
    }
  }
}
</script>

<style scoped>
.wrapper {
  width: 100vw;
  height: 100vh;
  position: relative;
  background: #000;
}
.heading {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 100px;
  font-family: "Nikukyu";
}
.heading > span:nth-child(1) { color: #9b30ff }
.heading > span:nth-child(2) { color: #ff34b3 }
.heading > span:nth-child(3) { color: #4eee94 }
.heading > span:nth-child(4) { color: #ffa500 }
</style>
