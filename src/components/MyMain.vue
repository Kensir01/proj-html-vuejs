<template>
    <main>
        <MarketingIntro />
        <GetConsultation />
        <AffiliatedBrands />
        <LeadingOrganisations />
    </main>
</template>

<script>
import MarketingIntro from './MarketingIntro.vue'
import GetConsultation from './GetConsultation.vue'
import AffiliatedBrands from './AffiliatedBrands.vue'
import LeadingOrganisations from './LeadingOrganisations.vue'



export default {
  name: "MyMain",
  components: {
    MarketingIntro,
    GetConsultation,
    AffiliatedBrands,
    LeadingOrganisations,
  }
}
</script>

<style>

</style>