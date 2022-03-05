<template>
<main>
    <div class="container_fluid ms_container">
        <div class="row justify-content-center">
            <div class="col-3">
                <img src="../assets/images/large-testimonial.jpg" alt="" class="ms_testimone">
            </div>
            <div class="col-3 align-self-center">
                <div class="ms_contenitore_testo">
                    <h5>
                        "The team at Avada Marketing Consultant is fabulous. They helped us unlock our
                        potential online and offline. We have experienced year on year growth due to their 
                        progressive approach."
                    </h5>
                    <p class="nome">Kate Schadler</p>
                    <p class="carica"> Marketing Consultant - Abstract</p>
                </div>
            </div>
        </div>
    </div>
</main>
</template>

<script>
export default {
    name: "MyTestimonial"
}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

main {

    overflow: hidden;
    
    .ms_container{

        padding-top: 3rem;
        padding-bottom: 3rem;
        
        .ms_testimone{
            width: 100%;
            height: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);        
        }

        .ms_contenitore_testo {
            margin-left: 65px;

            .nome{
                font-size: 13px;
                font-weight: 500;
                padding-top: 10px;
                margin-bottom: 0px;            
            }

            .carica{
                font-size: 10px;
                font-weight: 400;
            }
        }

    }

}
</style>