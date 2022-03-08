<template>
  <div id="app">
    <MyHeader :navLinks="navLinks" :navLinksDue="navLinksDue"/>    
    <MyMain />
    <MyFooter :footLinks="footLinks" :footLinksDue="footLinksDue" :footLinksTre="footLinksTre"/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
  },
  data () {
    return {
      navLinks: ['Home', 'About', 'Services', 'Showcase', 'Blog', 'Contact'],
      navLinksDue: ['Never', 'Gonna', 'Give', 'You', 'Up'],
      footLinks: ['Marketing Plan', 'Sales Development', 'Digital Marketing', 'Pricing', 'Why Us', 'Case Studies'],
      footLinksDue: ['Learning Center', 'Video Tutorials', 'Customers', 'Blog'],
      footLinksTre: ['Who We Are', 'Contact Us', 'Carrers'], 
    }
  }
}
</script>

<style lang="scss">

  @import './style/generali.scss';

</style>
