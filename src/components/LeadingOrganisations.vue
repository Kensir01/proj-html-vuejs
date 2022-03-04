<template>
<main>
    <div class="container-fluid">
        <div class="row justify-content-evenly">
            <div class="col-2">
                <div class="card ms_card" style="width: 18rem;">
                    <img src="../assets/images/case-studies-1-1200x1349.jpg" class="card-img-top" alt="">
                    <div class="card-body">
                        <p class="card-text ms_card_text">How Spaces attracted five million visitors by improving the content</p>
                    </div>
                </div>
            </div>
            <div class="col-2">
                <div class="card ms_card" style="width: 18rem;">
                    <img src="../assets/images/case-studies-4-1200x1349.jpg" class="card-img-top" alt="">
                    <div class="card-body">
                        <p class="card-text ms_card_text">Creativity helped Hemisferio to increase their brand reach vertically</p>
                    </div>
                </div>
            </div>
            <div class="col-2">
                <div class="card ms_card" style="width: 18rem;">
                    <img src="../assets/images/case-studies-6-1200x1349.jpg" class="card-img-top" alt="">
                    <div class="card-body">
                        <p class="card-text ms_card_text">How DigitalBox used AI-powered data insight to boost sales</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</main>
</template>

<script>
export default {
    name: "LeadingOrganisations"

}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {

    .ms_card {
        border: none;
        background-color: #f86011;


        .ms_card_text {
            width: 225px;
            font-size: 17px;
        }

        img  {
            -webkit-mask-image: linear-gradient(black, transparent);
            mask-image: linear-gradient(black, transparent);
        }
    }

}

</style>