<template>
<main>
    <div class="container ms_container">
        <div class="row justify-content-center">
            <div class="col-4">
                <img src="../../assets/svg/img1.svg" alt="" class="ms_svg">
            </div>
            <div class="col-4">
                <div class="mt-5">
                    <div class="ms_tag m-2">
                        <div class="ms_iconablu position-relative">
                            <div class="white_pebble_uno position-absolute"></div>
                            <div class="white_pebble_due position-absolute"></div>
                            <div class="white_pebble_tre position-absolute"></div>
                            <div class="white_pebble_quattro position-absolute"></div>

                        </div>
                        <p class="ms-1">Business Growth</p>
                    </div>
                    <div class="ms_titolo m-2">
                        <h3>Increase Brand Awareness</h3>
                    </div>
                    <div class="ms_sottotitolo mt-4 ms-2">
                        <p>
                            Lorm ipsum dolor sit amet, consectetur adipiscing elit. sed auctor placerat luctus.
                            Nullam sit amet ante sed orci convallis gravida et at massa.
                        </p>
                    </div>
                    <div class="ms_bottone mt-4 ms-2">
                        <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Get a Consultation</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</main>
</template>

<script>
export default {
    name: "GetConsultationUno"
}
</script>

<style scooped lang="scss">
@import '../../style/generali.scss';

main {

    .ms_container {
        padding-top: 10vh;
    }

    .ms_svg{
        width: 100%;
        height: 100%;
    }

    div .ms_bottone_secondo{
    color: white;
    background-color: #f76210;
    border: none;
    width: 160px;
    border-radius: 10px;
    font-size: 12px;
    font-weight: 400;

    }

    div .ms_tag {

        p {
        font-size: 10px;
        font-weight: 400;
        display: inline-block;
        }

        .ms_iconablu {
            display: inline-block;
            width: 25px;
            height: 25px;
            background-color: #0064fe;
            border-radius: 50%;
            vertical-align: middle;

            .white_pebble_uno {
                height: 6px;
                width: 3px;
                background-color: white;
                border-radius: 40%;
                transform: rotate(127deg);
                top: 7px;
                left: 8px;
            }

            .white_pebble_due {
                height: 6px;
                width: 3px;
                background-color: white;
                border-radius: 40%;
                transform: rotate(127deg);
                top: 7px;
                left: 13px;
            }
            
            .white_pebble_tre {
                height: 6px;
                width: 3px;
                background-color: white;
                border-radius: 40%;
                transform: rotate(127deg);
                top: 11px;
                left: 13px;
            }
            
            .white_pebble_quattro {
                height: 6px;
                width: 3px;
                background-color: white;
                border-radius: 40%;
                transform: rotate(127deg);
                top: 12px;
                left: 9px;
            }            
        }
    }

    div .ms_titolo h3 {
        font-weight: 600;
        max-width: 20vw;

    }

    div .ms_sottotitolo p {
        font-size: 14px;
        font-weight: 400;
        text-align: left;
        max-width: 20vw;
    }

}



</style>