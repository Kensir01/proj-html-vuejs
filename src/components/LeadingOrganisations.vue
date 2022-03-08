<template>
<main>
    <div class="container-fluid">

        <div class="row justify-content-center">
            <div class="col-12">
                <h1 class="text-center ms_organisations pb-4">Trusted by Leading Organisations</h1>
            </div>
        </div>

        <div class="row row-cols-4 justify-content-center">
            <LeadingCard v-for="(card, i) in cardsData" :key="i" :cardData="card" />
        </div>
        
        <div class="row py-5">
            <div class="col-12 text-center">
                <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Read More Case Studies</a>
            </div>
        </div>

    </div>
</main>
</template>
<script>

import LeadingCard from './LeadingCard.vue'

export default {
    name: "LeadingOrganisations",
    components: {
        LeadingCard
    },
    data () {
        return {
            cardsData: [
                {
                    img:'case-studies-1-1200x1349.jpg',
                    title: 'How Spaces attracted five million visitors by improving the content',
                    data: '200%',
                    subtext: 'Higher revenue from digital'
                },
                {
                    img:'case-studies-4-1200x1349.jpg',
                    title: 'Creativity helped Hemisferio to increase their brand reach vertically',
                    data: '10x',
                    subtext: 'Sales increase with the same ad spend'
                },
                {
                    img:'case-studies-6-1200x1349.jpg',
                    title: 'How DigitalBox used AI-powered data insight to boost sales',
                    data: '3-year',
                    subtext: 'Partnership with Avada Consultant'
                },

            ]
        };
    }
}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {


    .ms_organisations {
        font-size: 35px;
    }

    
    div .ms_bottone_secondo{
        color: white;
        background-color: #f76210;
        border: 1px solid #f76210;
        width: 285px;
        border-radius: 10px;

        &:hover,&:active,&:focus {
            background-color: white;
            color: #f76210;
            border: 1px solid #f76210;
            outline: none ;
            box-shadow: none;
        }
    }
}

</style>