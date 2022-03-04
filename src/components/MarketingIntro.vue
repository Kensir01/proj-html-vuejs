<template>
<main class="main_contaner">

    <div class="container-fluid row debug4 row position-relative ">
        <div class="ms_opacita position-absolute"></div>

        <div class="debug2 col-4 position-absolute">
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

        <div class="debug3 col-3 position-absolute pt-5">
            <div class="m-auto ms_sfera_account"></div>
            <div>
                <p>Richard Madsen</p>
                <p class="ms_testo_grigio">Marketing Consultant Expert</p>
                <p class="ms_numero"><i class="fa-solid fa-phone mx-1"></i> (555) 802-1234</p>
            </div>
            <div class="m-2">
                <div class="proveform ms_width_285 m-2">
                    <img src="../assets/images/image.png" class="sbirulino">
                    <input type="email" class="form-control ms_form" id="exampleFormControlInput1" placeholder="Your Name*">
                </div>
                <div class="m-2 ms_width_285">
                    <input type="email" class="form-control ms_form" id="exampleFormControlInput1" placeholder="Your Email*">
                </div>
                <div class="m-2 ms_width_285">
                    <input type="email" class="form-control ms_form" id="exampleFormControlInput1" placeholder="Your Phone Number*">
                </div>
                <div class="m-2 ms_width_285">
                    <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Get a Callback</a>
                </div>
                <div>
                    <p class="ms_testo_piccolo">By submitting my data i agree to be contacted</p>
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

<style scooped lang="scss">
@import '../style/generali.scss';

.debug2 {
    height: 250px;
    top: 90px;
    left: 225px;

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

.debug3 {
    height: 450px;
    bottom: -20px;
    right: 250px;
    text-align: center;
    background-color: white;
    border-radius: 10px;

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
    }
}

.debug4 {
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
}

.proveform {
    position: relative;
}
.sbirulino {
    position: absolute;
    right: 12px;
    top: 12px;
}

.ms_sfera_account {
    background-image: url(../assets/images/marketing-consultant-expert.jpg);
    background-size: cover;
    height: 75px;
    width: 75px;
    border-radius: 50%;
    
}

div .ms_bottone_secondo{
    color: white;
    background-color: #f76210;
    border: none;
    width: 285px;
}

.ms_width_285{
    width: 285px;
}

.debug {
    background-color: lightblue;
    height: 250px;
}
.main_contaner {
    height: 800px;
    -ms-overflow-style: none; 
    scrollbar-width: none; 
    overflow-y: scroll;
}

.main_contaner::-webkit-scrollbar {
  display: none;
}

</style>
