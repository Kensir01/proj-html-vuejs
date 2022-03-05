<template>
    <main>
        <MarketingIntro />
        <GetConsultation />
        <AffiliatedBrands />
        <LeadingOrganisations />
        <WorkWithUs />
    </main>
</template>

<script>
import MarketingIntro from './MarketingIntro.vue'
import GetConsultation from './GetConsultation.vue'
import AffiliatedBrands from './AffiliatedBrands.vue'
import LeadingOrganisations from './LeadingOrganisations.vue'
import WorkWithUs from './WorkWithUs.vue'




export default {
  name: "MyMain",
  components: {
    MarketingIntro,
    GetConsultation,
    AffiliatedBrands,
    LeadingOrganisations,
    WorkWithUs,
  }
}
</script>

<style>

</style>