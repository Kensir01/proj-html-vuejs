<template>
    <main>
        <MarketingIntro />
        <GetConsultation />
    </main>
</template>

<script>
import MarketingIntro from './MarketingIntro.vue'
import GetConsultation from './GetConsultation.vue'

export default {
  name: "MyMain",
  components: {
    MarketingIntro,
    GetConsultation,
  }
}
</script>

<style>

</style>