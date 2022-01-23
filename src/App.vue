<template>
  <div id="app_wrapper">
    <h1>{{ text }}</h1>
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      text: 'welcom to vue'
    }
  }
}

</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app_wrapper {
  width: 100vw;
  height: 100vh;
  background-color: darkkhaki;
}
</style>

