<template>
<main class="jumbo">

    <div class="container">
        <div class="row justify-content-center">
            <div class="col-4 debug">
                <h1>
                    Unlock Your Online Growth Potential
                </h1>
                <p>Online marketing to secure customer retention, leads, and sales.
                    We focus on the bigger picture.
                </p>
                <button type="button" class="btn btn-light">
                    Our Services
                    <i class="fa-solid fa-arrow-right"></i>
                </button>
            </div>
            <div class="col-4 debug align-self-end">
                <div class="m-auto ms_sfera_account"></div>
                <div>
                    <p>Richard Madsen</p>
                    <p>Marketing Consultant Expert</p>
                    <p><i class="fa-solid fa-phone mx-1"></i> (555) 802-1234</p>
                </div>
                <div class="m-2">
                    <div class="proveform ms_width_325 m-2">
                        <img src="../assets/images/image.png" class="sbirulino">
                        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Your Name*">
                    </div>
                    <div class="m-2 ms_width_325">
                        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Your Email*">
                    </div>
                    <div class="m-2 ms_width_325">
                        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Your Phone Number*">
                    </div>
                    <div class="m-2 ms_width_325">
                        <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Get a Callback</a>
                    </div>
                    <div>
                        <p>By submitting my data i agree to be contacted</p>
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

<style scooped lang="scss">
@import '../style/generali.scss';

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
    width: 325px;
}

.ms_width_325{
    width: 325px;
}

.debug {
    background-color: lightblue;
    height: 250px;
}
.jumbo {
    text-align: center;
    height: 800px;
}


// .ms_height{
//     height: 100%;
// }
// .ms_marketing{
//     height: 750px;
//     background-image: url(../assets/images/marketing-intro.jpg);
//     background-size: cover;
//     background-repeat: no-repeat;
//     background-position: center;
// }

// .ms_relative_marketing{
//     position: relative;
// }

// .ms_absolute_bot_marketing{
//     position: absolute;
//     top: 150px;
// }


// .ms_marketing {
//     background-image: url(../assets/images/marketing-intro.jpg);
//     height: 400px;
//     background-size: contain;
//     background-repeat: no-repeat;
//     background-position: center;
// }
</style>

                <!-- <h1>Unlock Your Online Growth Potential</h1>
            </div>
            <div class="text-jumbotron">
                <p>Online marketing to secure customer retention, leads, and sales.
                    We focus on the bigger picture.</p>
                <a class="btn btn-big" href="#">
                    Our Services
                    <i class="fa-solid fa-arrow-right"></i>
                </a> -->
                        <!-- <div class="container-fluid ms_marketing">

            <div class="row ms_height">

                <div class="col-12 col-lg-5 ms_relative_marketing ms_height text-white">
                    <div class="card border-0 bg-transparent ms_absolute_bot_marketing">

                        <div class="card-body">
                            <h1 class="mb-3 fw-bold">Un'avventura cooperativa selvaggia ti attende</h1>
                            <p class="mb-3 fw-bold">
                                Trova un amico e partite insieme per l'avventura pi&ugrave; folle delle vostre vite in It Takes Two,
                                un gioco d'avventura cooperativa a piattaforme che stravolge il suo genere.
                            </p>
                            <button class="btn" type="button">Acquista ora</button>
                        </div>

                    </div>
                </div>

            </div>

        </div>   -->