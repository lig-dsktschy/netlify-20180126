<template>
  <div class="wrapper">
    <h1 class="heading">づやかい！</h1>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'づやかい！'
    }
  }
}
</script>

<style scoped>
.wrapper {
  width: 100vw;
  height: 100vh;
  position: relative;
}
.heading {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 48px;
}
</style>
