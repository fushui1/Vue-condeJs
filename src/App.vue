<template>
  <div id="app">
    <header/>

    <router-view/>

    <footer/>
  </div>
</template>

<script>
import header from '@/components/common/header'
import footer from '@/components/common/footer'

export default {
  name: 'app',
  components : {
    header,
    footer
  }
}
</script>

<style lang="scss" scoped="" type="text/css">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
