<template>
<main>
    <div class="container-fluid ms_container">
        <div class="row justify-content-center">
            <div class="col-3 ms_col_sx">
                <h3>We Boost Our Clients' Bottom Line by Optimizing Their Growth Potential.</h3>
                <p>Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.</p>
                <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Why Work With Us</a>
            </div>
            <div class="col-3 ms_col_dx">
                <img src="../assets/images/we-boost-our-clients.jpg" alt="">
            </div>
        </div>

        <div class="row justify-content-center">

            <div class="col-3 mt-5">
                <div class="col-12 cont_sx_1">
                    <h5>We Build Relationships</h5>
                    <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                </div>
                <div class="col-12 cont_sx_2">
                    <h5>Proprietary Processes</h5>
                    <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>
                </div>
            </div>

            <div class="col-3 mt-5">

                <div class="col-12 cont_dx_1 clearfix">
                    <div class="contenitore_bordo float-start">
                        <div class="contenitore_iconcina position-absolute">
                            <i class="fa-solid fa-magnifying-glass position-absolute"></i>
                            <div class="punto position-absolute"></div>
                            <div class="linea2 position-absolute"></div>
                            <div class="linea3 position-absolute"></div>
                            <div class="linea5 position-absolute"></div>
                        </div>                        
                    </div>

                    <div class="boh float-start">
                        <h5>Accountability</h5>
                        <p>Curabitur ac leo nunc vestibulum</p>
                    </div>

                </div>

                <div class="col-12 cont_dx_2 clearfix">

                    <div class="contenitore_bordo float-start">
                        <div class="contenitore_iconcina position-absolute">
                            <i class="fa-solid fa-plus position-absolute"></i>
                            <div class="punto position-absolute"></div>
                            <div class="linea2 position-absolute"></div>
                            <div class="linea3 position-absolute"></div>
                            <div class="linea5 position-absolute"></div>
                        </div>  

                    </div>

                    <div class="boh float-start">
                        <h5>Transparency</h5>
                        <p>Curabitur ac leo nunc vestibulum</p>
                    </div>

                </div>

                <div class="col-12 cont_dx_3 clearfix">

                    <div class="contenitore_bordo float-start">

                        <div class="contenitore_iconcina position-absolute">
                            <i class="fa-solid fa-signal position-absolute"></i>
                            <div class="punto position-absolute"></div>
                            <div class="linea2 position-absolute"></div>
                            <div class="linea3 position-absolute"></div>
                            <div class="linea5 position-absolute"></div>
                        </div>       

                    </div>

                    <div class="boh float-start">
                        <h5>Investment</h5>
                        <p>Curabitur ac leo nunc vestibulum</p>
                    </div>

                </div>

            </div>
        </div>
        
        <div class="row justify-content-center ms_awards pb-5">
            <div class="col-12">
                <h5 class="text-center">Awards</h5>
            </div>
            <div class="col-2">
                <div>
                    <img src="../assets/images/award-a.png" alt="" class="award_a">
                </div>
                <p class="sottotitolo text-center">Winner Seo Master MAGT</p>
                <p class="sottotitolo text-center">Smart Start Award 2017</p>
            </div>
            <div class="col-2">
                <div>
                    <img src="../assets/images/award-b.png" alt="" class="award_b">
                </div>
                <p class="sottotitolo text-center">Top Social Media Agencies</p>
                <p class="sottotitolo text-center">Next Partner 2018</p>
            </div>
            <div class="col-2">
                <div>
                    <img src="../assets/images/award-c.png" alt="" class="award_c">
                </div>
                <p class="sottotitolo text-center">10 Fastest Growing Abstract</p>
                <p class="sottotitolo text-center">Solution Providers 2019</p>
            </div>
            <div class="col-2">
                <div>
                    <img src="../assets/images/award-d.png" alt="" class="award_d">
                </div>
                <p class="sottotitolo text-center">National Excellence Agencie</p>
                <p class="sottotitolo text-center">Award Winner 2020</p>
            </div>
        </div>

    </div>
</main>
</template>

<script>
export default {
    name: "WorkWithUs"

}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {


    .cont_dx_1 {
        width: 100%;

        p {
            font-size: 12px;
            font-weight: 300;       
        }     

        .boh{
            padding-top: 6px;
            padding-left: 12px;
        }
        

        .contenitore_bordo{
            width: 60px;
            height: 60px;
            border: 2px solid #f76210;
            border-radius: 13px;
            position: relative;


            .contenitore_iconcina {
                width: 30px;
                height: 30px;
                background-color: #f76210;
                border-radius: 3px;
                bottom: 13px;
                right: 13px;
                   
            
                .fa-magnifying-glass {
                    font-size: 12px;
                    color: white;
                    bottom: 2px;
                    right: 2px;
                }

                .punto {
                    height: 2px;
                    width: 4px;
                    background-color: white;
                    top: 2px;
                    left: 2px;
                    border-radius: 40%;
                }

                .linea2{
                    height: 2px;
                    width: 7px;
                    background-color: white;
                    top: 2px;
                    left: 8px;
                    border-radius: 40%;
                }

                .linea3{
                    height: 2px;
                    width: 9px;
                    background-color: white;
                    top: 16px;
                    left: 2px;
                    border-radius: 40%;
                }


                .linea5 {
                    height: 2px;
                    width: 12px;
                    background-color: white;
                    top: 13px;
                    left: 2px;
                    border-radius: 40%;
                }
            }
        }

    }

    .cont_dx_2 {
        width: 100%;

        p {
            font-size: 12px;
            font-weight: 300;       
        }   

        .boh{
            padding-top: 6px;
            padding-left: 12px;
        }

        .contenitore_bordo{
            width: 60px;
            height: 60px;
            border: 2px solid #f76210;
            border-radius: 13px;
            position: relative;


            .contenitore_iconcina {
                width: 30px;
                height: 30px;
                background-color: #f76210;
                border-radius: 3px;
                bottom: 13px;
                right: 13px;
                   
            
                .fa-plus {
                    font-size: 18px;
                    color: white;
                    bottom: 4px;
                    right: 7px;
                }

                .punto {
                    height: 2px;
                    width: 4px;
                    background-color: white;
                    top: 2px;
                    left: 2px;
                    border-radius: 40%;
                }

                .linea2{
                    height: 2px;
                    width: 7px;
                    background-color: white;
                    top: 2px;
                    left: 8px;
                    border-radius: 40%;
                }

            }
        }
    }

    .cont_dx_3 {
        width: 100%;

        p {
            font-size: 12px;
            font-weight: 300;       
        }     

        .boh{
            padding-top: 6px;
            padding-left: 12px;
        }
        

        .contenitore_bordo{
            width: 60px;
            height: 60px;
            border: 2px solid #f76210;
            border-radius: 13px;
            position: relative;


            .contenitore_iconcina {
                width: 30px;
                height: 30px;
                background-color: #f76210;
                border-radius: 3px;
                bottom: 13px;
                right: 13px;
                   
            
                .fa-signal {
                    font-size: 16px;
                    color: white;
                    bottom: 5px;
                    right: 7px;
                }

                .punto {
                    height: 2px;
                    width: 4px;
                    background-color: white;
                    top: 2px;
                    left: 2px;
                    border-radius: 40%;
                }

                .linea2{
                    height: 2px;
                    width: 7px;
                    background-color: white;
                    top: 2px;
                    left: 8px;
                    border-radius: 40%;
                }

            }
        }

    }

    .cont_sx_1 {
        width: 100%;

        p {
            font-size: 12px;
            font-weight: 300;       
        }
    }

    .cont_sx_2 {
        width: 100%;

        p {
            font-size: 12px;
            font-weight: 300;       
        }        
    }

    .ms_container {
        background-color: #f4f4f6;
    }

    .ms_col_sx {
        margin-top: 80px;

        h3 {
            font-size: 31px;
        }

        p {
            font-size: 14px;
            font-weight: 300;
        }

        .ms_bottone_secondo{
            color: white;
            background-color: #f76210;
            border: 1px solid #f76210;
            width: 180px;
            border-radius: 10px;

            &:hover,&:focus,&:active {
                background-color: white;
                color: #f76210;
                border: 1px solid #f76210;
                outline: none; 
                box-shadow: none;
            }
        }
    }

    .ms_col_dx {
        margin-top: 60px;


        img {
            width: 100%;
            height: 100%;
        }
    }

    .ms_awards {
        margin-top: 50px;

        .sottotitolo{
            font-size: 12px;
            font-weight: 300;
            margin-bottom: 0px;
        }

        .award_a {
            width: 50%;
            height: 50%;
            filter: hue-rotate(190deg);
            margin-left: 4vw;
            opacity: 0.7;
        }

        .award_b {
            width: 50%;
            height: 50%;
            margin-left: 4vw;
        }
        
        .award_c {
            width: 50%;
            height: 50%;
            filter: saturate(3);
            margin-left: 4vw;

        }

        .award_d {
            width: 50%;
            height: 50%;
            filter: hue-rotate(210deg);
            margin-left: 4vw;

        }

    }

}
</style>