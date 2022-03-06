<template>
<main>
    <div class="row justify-content-center ms_container_nero">

        <div class="col-3 py-5 me-5">
            <div class="contenitore_testo">
                <h1 class="titolo">Let's Make Things Happen</h1>
                <p class="sotto_titolo">
                    Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.
                </p>
                <div class="linea"></div>
                <p class="sotto_titolo_italic">
                    "The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and
                    offline. We have experienced year on year growth due to their progressive approach.""
                </p>
                <p class="nome">George Anderson</p>
                <p class="carica">Digitalbox CEO</p>
            </div>
        </div>

        <div class="col-3 py-5">
            <div class="ms_container_destra">
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
    name: "MakeThings"

}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {

    overflow: hidden;

    .ms_container_nero{

        background-color: black;

        .ms_container_destra {
        height: 425px;
        text-align: center;
        background-color: white;
        border-radius: 10px;
        width: 333px;
        padding-top: 1px;

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

        .ms_width_285{
            width: 285px;
        }
        }

        .contenitore_testo{
            width: 350px;
            color: white;

            .titolo{
                font-weight: 700;
            }

            .sotto_titolo{
                font-size: 16px;
                font-weight: 400;
                padding-bottom: 1.5rem;
            }

            .linea {
                width: 60px;
                height: 1px;
                background-color: rgba(255, 255, 255, 0.3);
                margin-bottom: 30px;
            }

            .sotto_titolo_italic{
                font-size: 12px;
                font-weight: 500;
                font-style: italic;
            }

            .nome {
                font-size: 14px;
                font-weight: 600;
                padding-top: 5px;
            }

            .carica {
                font-size: 11px;
                font-weight: 300;
                margin-top: -15px;
            }
            
        }

    }

}
</style>