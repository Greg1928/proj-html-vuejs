<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/blocks/BaseHeader.vue'
import BaseMain from './components/blocks/BaseMain.vue'
import BaseFooter from './components/blocks/BaseFooter.vue'

export default {
  name: 'App',
  components:{
    BaseHeader,
    BaseMain,
    BaseFooter
  }
}
</script>

<style lang="scss">
@import "./assets/style/global.scss";
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
