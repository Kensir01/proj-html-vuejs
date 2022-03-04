<template> 
<header>

    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-light bg-white">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="../assets/images/mc-favicon.png" alt="" class="logo mx-2">
                    AvadaConsultant
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <!-- Primo dropdown -->
                    <div class="ms_navbar_border">
                        <li class="nav-item dropdown">
                            <a class="nav-link active dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Home
                            </a>
                            <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                            </ul>
                        </li>                          
                    </div>
  
                    <!-- Secondo dropdown -->
                    <li class="nav-item dropdown">
                        <a class="nav-link active dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Services
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                        </ul>
                    </li>    
                    <!-- Resto di link header -->
                    <a class="nav-link active" aria-current="page" href="#">Why Us</a>
                    <a class="nav-link active" aria-current="page" href="#">Case Studies</a>
                    <a class="nav-link active" aria-current="page" href="#">About</a>
                    <a class="nav-link active" aria-current="page" href="#">Blog</a>
                    <a class="nav-link active mx-4" aria-current="page" href="#"><i class="fa-solid fa-phone mx-1"></i> (555) 802-1234</a>
                    <a class="btn btn-primary ms_bottone_arancione" href="#" role="button" disabled>Free Quote</a>
                </div>
                </div>
            </div>
        </nav>       
    </div>

</header>
</template>

<script>
export default {
    name: "MyHeader"
}
</script>

<style scooped lang="scss">

@import '../style/generali.scss';

header{

    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 14mx;

    .logo{
        width: 15%;
        height: 15%;
    }


    .ms_navbar_border {
        border-bottom: 2px solid #f76210;
    }

    .navbar .navbar-nav div li a {
        color: #f76210 !important;  
    }

    .ms_bottone_arancione{
        color: #f76210;
        background-color: rgba(247,98,16, 0.1);
        border: none;
        padding: 9px 25px;
        font-size: 13px;
        border-radius: 10px;


        &:hover{
            background-color: #f76210;
        }
    }    
}



</style>