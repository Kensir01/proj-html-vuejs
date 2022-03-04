<template>
<main>
    <div class="container-fluid mt-5">
        <div class="row justify-content-center mb-5">
            <div class="col-12">
                <h1 class="text-center">Some Brands We Work With</h1>
            </div>
            <div class="col-12">
                <p class="text-center ms_titolo mb-4">Quisque aliquet, libero consequat elementum convalis.</p>
            </div>
            <div class="col-1 mx-3">
                <img src="../assets/images/abstract.png" alt="">
            </div>
            <div class="col-1 mx-3">
                <img src="../assets/images/cglobal.png" alt="">
            </div>
            <div class="col-1 mx-3">
                <img src="../assets/images/next.png" alt="">
            </div>
            <div class="col-1 mx-3">
                <img src="../assets/images/hemisferio.png" alt="">
            </div>
            <div class="col-1 mx-3">
                <img src="../assets/images/spaces.png" alt="">
            </div>                
            <div class="col-1 mx-3">
                <img src="../assets/images/digitalbox.png" alt="">
            </div>
        </div>
        <div class="row justify-content-center clearfix mb-5">
            <div class="col-8 debug1">
                <div class="contenitore debug2">
                    <div class="ms_sfera_account float-start ms-3 mt-2"></div>
                    <div class="float-start mx-4 mt-2">
                        <p class="ms_nome">Sandy Reiff</p>
                        <br> 
                        <p class="ms_ruolo">Marketing Consultant Expert</p>
                    </div>
                    <div class="float-start mt-4 mx-3">Drive Leads and Sales with Avada</div>
                    <div class="ms_bottone float-end mx-3 mt-3">
                        <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>
                            <p><i class="fa-solid fa-phone mx-1"></i> (555) 802-1234</p>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</main>
</template>

<script>
export default {
    name: "AffiliatedBrands"
}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {

    overflow-x: hidden;

    .col-1 img {
        width: 100%;
        height: 100%;
    }

    .ms_titolo{
        font-weight: 400;
    }

    .debug1 {
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        border-radius: 10px;
        height: 60px;
    }

    .debug2 {
        background-color: blue;

        .ms_sfera_account {
            background-image: url(../assets/images/marketing-expert-cta.png);
            background-size: cover;
            height: 45px;
            width: 45px;
            border-radius: 50%;
        }   

        .ms_nome {
            font-size: 15px;
            margin-top: 3px;
            margin-bottom: -25px;
        }

        .ms_ruolo {
            font-size: 12px;
            font-weight: 300;
            margin: 0;
        }

        div .ms_bottone_secondo{
            color: #f76210;
            background-color: rgba(247,98,16, 0.2);
            border: none;
            padding: 9px 25px;
            font-size: 13px;
            border-radius: 10px;
            width: 175px;
            height: 35px;

            p {
                font-size: 11px;
                color: #f86011;
            }

        }

    }


}

</style>