<template>
<main>
    <div class="container ms_container">
        <div class="row justify-content-center">
            <div class="col-4">
                <div class="mt-5">
                    <div class="ms_tag m-2">
                        <div class="ms_iconagialla position-relative">
                            <div class="quarter_uno position-absolute"></div>
                            <div class="quarter_due position-absolute"></div>
                            <div class="quarter_tre position-absolute"></div>
                            <div class="quarter_quattro position-absolute"></div>
                        </div>
                        <p class="ms-1">Investors In People</p>
                    </div>
                    <div class="ms_titolo m-2">
                        <h3>In-House Sales Training</h3>
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
            <div class="col-4">
                <img src="../../assets/svg/img2.svg" alt="" class="ms_svg">
            </div>
        </div>
    </div>
</main>
</template>

<script>
export default {
    name: "GetConsultationDue"
}
</script>

<style scoped lang="scss">
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
        border: 1px solid #f76210;
        width: 160px;
        border-radius: 10px;
        font-size: 12px;
        font-weight: 400;
    
        &:hover,&:focus,&:active {
            background-color: white;
            color: #f76210;
            border: 1px solid #f76210;
            outline: none; 
            box-shadow: none;
        }
               
    }

    div .ms_tag {

        p {
        font-size: 10px;
        font-weight: 400;
        display: inline-block;
        }

        .ms_iconagialla {
            display: inline-block;
            width: 25px;
            height: 25px;
            background-color: #f8cc23;
            border-radius: 50%;
            vertical-align: middle;

            .quarter_uno {
                width: 4px;
                height: 4px;
                border-top-right-radius:0;
                border-top-left-radius:0;
                border-bottom-right-radius:100%;
                border-bottom-left-radius:0;
                border: 2px solid white;
                border-top: 0px;
                border-left: 0px;                
                top: 9px;
                left: 9px;
            }

            .quarter_due {
                width: 4px;
                height: 4px;
                border-top-right-radius:0;
                border-top-left-radius:0;
                border-bottom-right-radius:100%;
                border-bottom-left-radius:0;
                border: 2px solid white;
                border-top: 0px;
                border-left: 0px;                
                top: 9px;
                left: 13px;
            }
            
            .quarter_tre {
                width: 4px;
                height: 4px;
                border-top-right-radius:0;
                border-top-left-radius:100%;
                border-bottom-right-radius:0;
                border-bottom-left-radius:0;
                border: 2px solid white;
                border-bottom: 0px;
                border-right: 0px;                
                top: 13px;
                left: 12px;
            }
            
            .quarter_quattro {
                width: 4px;
                height: 4px;
                border-top-right-radius:0;
                border-top-left-radius:100%;
                border-bottom-right-radius:0;
                border-bottom-left-radius:0;
                border: 2px solid white;
                border-bottom: 0px;
                border-right: 0px;                
                top: 13px;
                left: 8px;
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