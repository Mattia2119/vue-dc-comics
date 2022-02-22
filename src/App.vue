<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MyBlueSection/>
    <MyFooterTop/>
    <MyFooterBottom/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyBlueSection from './components/MyBlueSection.vue'
import MyFooterTop from './components/MyFooterTop.vue'
import MyFooterBottom from './components/MyFooterBottom.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyBlueSection,
    MyFooterTop,
    MyFooterBottom,
  }
}
</script>

<style lang="scss">
 @import "src/assets/style/general.scss";
</style>
