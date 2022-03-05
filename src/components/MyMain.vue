<template>
    <main>
        <MarketingIntro />
        <GetConsultation />
        <AffiliatedBrands />
        <LeadingOrganisations />
        <WorkWithUs />
        <MyTestimonial />
        <MarketingResources />
        <MakeThings />
    </main>
</template>

<script>
import MarketingIntro from './MarketingIntro.vue'
import GetConsultation from './GetConsultation.vue'
import AffiliatedBrands from './AffiliatedBrands.vue'
import LeadingOrganisations from './LeadingOrganisations.vue'
import WorkWithUs from './WorkWithUs.vue'
import MyTestimonial from './MyTestimonial.vue'
import MarketingResources from './MarketingResources.vue'
import MakeThings from './MakeThings.vue'



export default {
  name: "MyMain",
  components: {
    MarketingIntro,
    GetConsultation,
    AffiliatedBrands,
    LeadingOrganisations,
    WorkWithUs,
    MyTestimonial,
    MarketingResources,
    MakeThings,
  }
}
</script>

<style>

</style>