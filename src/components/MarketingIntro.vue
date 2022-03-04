<template>
<main class="main_contaner">

    <div class="container-fluid row ms_container_grande row position-relative ">
        <div class="ms_opacita position-absolute"></div>

        <!-- Icona Demos -->
        <div class="ms_demos position-absolute">
            <div class="iconcina_barra_uno position-absolute"></div>
            <div class="iconcina_barra_due position-absolute"></div>
            <div class="iconcina_demos position-absolute">
                <i class="fa-brands fa-atlassian position-absolute fa-flip-horizontal"></i>
            </div>
            <div class="ms_demos_testo position-absolute">
                Demos
            </div>
        </div>

        <!-- icona On Sale -->
        <div class="ms_onSale position-absolute">
            <div class="iconcina_dollaro position-absolute">$</div>
            <div class="ms_onSale_cifra position-absolute">39</div>
            <div class="ms_onSale_testo position-absolute">On Sale</div>
        </div>        


        <div class="ms_container_sinistra col-4 position-absolute">
            <h1>
                Unlock Your Online Growth Potential
            </h1>
            <p>Online marketing to secure customer retention, leads, and sales.
                We focus on the bigger picture.
            </p>
            <button type="button" class="btn btn-light ms_button_services">
                Our Services
                <i class="fa-solid fa-arrow-right"></i>
            </button>
        </div>

        <div class="col-3 pt-5">
            <div class="ms_container_destra position-absolute">
                <div class="ms_sfera_account"></div>
                <div>
                    <p class="m-2">Richard Madsen</p>
                    <p class="ms_testo_grigio">Marketing Consultant Expert</p>
                    <p class="ms_numero"><i class="fa-solid fa-phone mx-1"></i> (555) 802-1234</p>
                </div>
                <div class="m-2">
                    <div class="ms_form ms_width_285 m-3">
                        <img src="../assets/images/image.png" class="sbirulino">
                        <input type="email" class="form-control ms_form" id="exampleFormControlInput1" placeholder="Your Name*">
                    </div>
                    <div class="m-3 ms_width_285">
                        <input type="email" class="form-control ms_form" id="exampleFormControlInput1" placeholder="Your Email*">
                    </div>
                    <div class="m-3 ms_width_285">
                        <input type="email" class="form-control ms_form" id="exampleFormControlInput1" placeholder="Your Phone Number*">
                    </div>
                    <div class="m-3 ms_width_285">
                        <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Get a Callback</a>
                    </div>
                    <div>
                        <p class="ms_testo_piccolo m-4">By submitting my data i agree to be contacted</p>
                    </div>
                </div>            
            </div>
        </div>

    </div>

</main>
</template>

<script>
export default {
    name: "MarketingIntro"
}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

.ms_container_sinistra {
    height: 250px;
    top: 90px;
    left: 18vw;

    h1, p {
        color: white;
    }

    .ms_button_services{
        font-size: 12px;
        padding: 6px 20px;
        border-radius: 7px;

        &:hover{
            background-color: transparent;
            color: white;
        }
    }
}

.ms_container_destra {
    height: 425px;
    bottom: -20px;
    right: 23vw;
    text-align: center;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 10px 20px 0 rgba(0, 0, 0, 0.19);

    .ms_testo_grigio{
        color: grey;
        font-size: 12px;
    }

    .ms_numero{
        font-size: 13px;
        color: #f76210;
    }

    .ms_testo_piccolo{
        font-size: 9px;
        color: grey;
    }

    .ms_form {
    position: relative;
    }

    ::-webkit-input-placeholder {
        font-size: 13px;
    }

    :-moz-placeholder { /* Firefox 18- */
        font-size: 13px;
    }

    ::-moz-placeholder {  /* Firefox 19+ */
        font-size: 13px;
    }

    .sbirulino {
        position: absolute;
        right: 12px;
        top: 12px;
    }

    .ms_sfera_account {
        background-image: url(../assets/images/marketing-consultant-expert.jpg);
        background-size: cover;
        height: 45px;
        width: 45px;
        border-radius: 50%;
        margin: auto;
        margin-top: 20px;
    }

    div .ms_bottone_secondo{
        color: white;
        background-color: #f76210;
        border: none;
        width: 285px;
        border-radius: 10px;

    }

    .ms_width_285{
        width: 285px;
    }
}

.ms_container_grande {
    height: 500px;
    background-image: url(../assets/images/marketing-intro.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;

    .ms_opacita {
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.3);
        top: 0;
        left: 0;
    }

    .ms_demos{
        width: 50px;
        height: 50px;
        background-color: white;
        top: 35px;
        right: 15px;
        border-radius: 7px;

        .iconcina_demos{
            width: 20px;
            height: 15px;
            background-color: #33475b;
            top: 17px;
            left: 16px;
            border-radius: 3px;

            .fa-atlassian{
                font-size: 8px;
                color: white;
                left: 6px;
                top: 3px;
            }
        }

        .iconcina_barra_uno{
            width: 16px;
            height: 2px;
            background-color: #33475b;
            top: 14px;
            left: 18px;

        }

        .iconcina_barra_due{
            width: 12px;
            height: 2px;
            background-color: #33475b;
            top:11px;
            left: 20px;

        }

        .ms_demos_testo{
            font-size: 9px;
            bottom: 4px;
            left: 11px;
        }
    }

    .ms_onSale{
        width: 50px;
        height: 50px;
        background-color: white;
        top: 90px;
        right: 15px;
        border-radius: 7px;  
        
        .iconcina_dollaro{
            color: #65bc7b;
            font-size: 12px;
            top: 4px;
            left: 7px;
        }

        .ms_onSale_cifra{
            color: #65bc7b;
            top: 2px;
            left: 14px;
            font-size: 22px;
        }

        .ms_onSale_testo{
            font-size: 9px;
            bottom: 6px;
            left: 11px;
        }

    }
}

.main_contaner {
    height: 555px;
    -ms-overflow-style: none; 
    scrollbar-width: none; 
    overflow-y: scroll;
}

.main_contaner::-webkit-scrollbar {
  display: none;
}

</style>
