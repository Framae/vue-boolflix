<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyHeader from './components/MyMain.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain
  }
}
</script>

<style lang="scss">

</style>
