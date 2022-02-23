<template>
  <div id="app">
    <MyHeader/>
    <MyJumbotron/>
    <MyMain/>
    <MyBlueSection/>
    <MyFooterTop/>
    <MyFooterBottom/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyJumbotron from './components/MyJumbotron.vue'
import MyBlueSection from './components/MyBlueSection.vue'
import MyFooterTop from './components/MyFooterTop.vue'
import MyFooterBottom from './components/MyFooterBottom.vue'
import MyMain from './components/MyMain.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbotron,
    MyBlueSection,
    MyFooterTop,
    MyFooterBottom,
    MyMain,
  }
}
</script>

<style lang="scss">
 @import "src/assets/style/general.scss";
</style>
