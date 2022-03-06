<template>
<main>
    <div class="container-fluid ms_container">

        <div class="row justify-content-center ms_spacer">
            <div class="col-3">
                <h3 class="marketing_testo">
                    Marketing Resources: Insider Advice on How to Increase Online Sales
                </h3>
            </div>
            <div class="col-3 align-self-end clearfix">
                <div class="float-end">
                    <a class="btn btn-primary ms_bottone_secondo" href="#" role="button" disabled>Explore All Resources</a>
                </div>
            </div>
        </div>

        <div class="row justify-content-center">
            <div class="col-2 carte">
                <div class="contenitore_img">
                    <img src="../assets/images/blog-posts-6.jpg" alt="">
                </div>
                <div>
                    <p class="ms_sottotitolo">Marketing Tips And Tricks For Your Website</p>
                </div>
            </div>
            <div class="col-2 carte">
                <div class="contenitore_img">
                    <img src="../assets/images/blog-posts-5.jpg" alt="">
                </div>
                <div>
                    <p class="ms_sottotitolo">How to Write Stunning Blog Post Titles</p>
                </div>
            </div>
            <div class="col-2 carte">
                <div class="contenitore_img">
                    <img src="../assets/images/blog-posts-4.jpg" alt="">
                </div>
                <div>
                    <p class="ms_sottotitolo">Techniques to Reduce Facebook Ads Spend</p>
                </div>
            </div>
        </div>

    </div>
</main>
</template>

<script>
export default {
    name:"MarketingResources"

}
</script>

<style scoped lang="scss">
main {

    .ms_container {
        background-color: #f4f4f6;
        padding-bottom: 3rem;
        .ms_spacer{
            padding-top: 5rem;

            .marketing_testo{
                width: 330px
            }

            .ms_bottone_secondo{
                color: white;
                background-color: #f76210;
                border: 1px solid #f76210;
                width: 220px;
                border-radius: 10px;

                &:hover,&:focus,&:active {
                    background-color: white;
                    color: #f76210;
                    border: 1px solid #f76210;
                    outline: none ;
                    box-shadow: none;
                }       
            }
        }

        .carte {

            .contenitore_img {

                padding-top: 4rem;

                img {
                    width: 80%;
                    height: 80%;
                }
            }   
            
            p {
                font-size: 14px;
                font-weight: 300;
                padding-top: 10px;
                width: 190px;
            }
        }


    }

}

</style>