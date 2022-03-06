<template>
<main>
    <div class="container-fluid">

        <div class="row justify-content-center">
            <div class="col-12">
                <h1 class="text-center ms_organisations pb-4">Trusted by Leading Organisations</h1>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_img">
                    <img src="../assets/images/case-studies-1-1200x1349.jpg" alt="">
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_img">
                    <img src="../assets/images/case-studies-4-1200x1349.jpg" alt="">
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_img">
                    <img src="../assets/images/case-studies-6-1200x1349.jpg" alt="">
                </div>
            </div>
        </div>

        <div class="row justify-content-center">
            <div class="col-3">
                <div class="ms_contenitore_txt pt-4">
                    <p>How Spaces attracted five million visitors by improving the content</p>
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_txt pt-4">
                    <p>Creativity helped Hemisferio to increase their brand reach vertically</p>
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_txt pt-4">
                    <p>How DigitalBox used AI-powered data insight to boost sales</p>
                </div>
            </div>
        </div>

        <div class="row justify-content-center">
            <div class="col-3">
                <div class="ms_contenitore_numero ">
                    <p>200%</p>
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_numero ">
                    <p>10x</p>
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_numero ">
                    <p>3-year</p>
                </div>
            </div>
        </div>

        <div class="row justify-content-center">
            <div class="col-3">
                <div class="ms_contenitore_sottotitolo ">
                    <p>Higher revenue from digital</p>
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_sottotitolo ">
                    <p>Sales increase with the same ad spend</p>
                </div>
            </div>
            <div class="col-3">
                <div class="ms_contenitore_sottotitolo ">
                    <p>Partnership with Avada Consultant</p>
                </div>
            </div>
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
export default {
    name: "LeadingOrganisations"

}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {


    .ms_organisations {
        font-size: 35px;
    }

    
    .ms_contenitore_img {
        background-color: rgba(248, 96, 17, 0.7);

        img {
            width: 100%;
            height: 100%;

            &:hover {
                -webkit-mask-image: linear-gradient(black, transparent);
                mask-image: linear-gradient(black, transparent);
            }

        }


    }

    .ms_contenitore_txt{
        border: none;
        border-bottom: 1px dashed rgba(128, 128, 128, 0.4);

        p {
        font-size: 24px;
        font-weight: 00;
        }
    }

    .ms_contenitore_numero p{
        font-size: 28px;
        font-weight: 600;
        padding-top: 10px;
    }

    .ms_contenitore_sottotitolo p{
        font-size: 10px;
        font-weight: 300;
        margin-top: -18px;
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