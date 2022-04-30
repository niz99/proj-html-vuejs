<template>
  <div id="app">
    <HeaderComp/>
  </div>
</template>

<script>
import "bootstrap"
import HeaderComp from './components/HeaderComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp
  }
}
</script>

<style lang="scss">
@import "bootstrap/dist/css/bootstrap.min.css";
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
