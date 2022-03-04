<template>
  <main>
      <GetConsultationUno />
      <GetConsultationDue />
      <GetConsultationTre />
  </main>
</template>

<script>
import GetConsultationUno from './partials/GetConsultationUno.vue'
import GetConsultationDue from './partials/GetConsultationDue.vue'
import GetConsultationTre from './partials/GetConsultationTre.vue'


export default {
    name: "GetConsultation",
    components : {
        GetConsultationUno,
        GetConsultationDue,
        GetConsultationTre
    }
}
</script>

<style scoped lang="scss">

</style>