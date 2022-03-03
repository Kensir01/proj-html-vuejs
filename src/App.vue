<template>
  <div id="app">
    <MyHeader />    
    <MarketingIntro />
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MarketingIntro from './components/MarketingIntro.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MarketingIntro,
  }
}
</script>

<style lang="scss">

  @import './style/generali.scss';

</style>
