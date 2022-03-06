<template>

  <footer class="">
    <div class="row justify-content-center g-2">

        <div class="position-relative">
            <div class="position-absolute contenitore_bottone_chat" v-on:click="isHidden = !isHidden">
                <i class="fa-regular fa-message primo_mess position-absolute"></i>
                <i class="fa-solid fa-message secondo_mess position-absolute"></i>
                <i class="fa-solid fa-message quarto_mess position-absolute"></i>
            </div>
            
            <div class="position-absolute contenitore_chat" v-if="!isHidden">
                <div class="contenitore_interno_chat">
                    <p>
                        This is a free HubSpot live chat. You can create your own chat flows and
                        engage your customers with Avada & HubSpot!
                    </p>                    
                </div>
                <div class="ms_sfera_account position-absolute"></div>
                <div class="contenitore_X position-absolute" v-on:click="isHidden = !isHidden">
                    <div class="barra_uno position-absolute"></div>
                    <div class="barra_due position-absolute"></div>
                                    
                </div>
            </div>
        </div>

        <div class="col-2 ms_social me-5">
            <h5>Grow Your Online Business Strategically, and Improve Custome Retention.</h5>
            <ul class="list-unstyled d-flex">
                <li><a class="link-dark" href="#"><i class="fa-brands fa-facebook-f"></i></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><i class="fa-brands fa-twitter"></i></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><i class="fa-brands fa-instagram"></i></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><i class="fa-brands fa-youtube"></i></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><i class="fa-brands fa-linkedin-in"></i></a></li>
                <li class="ms-3"><a class="link-dark" href="#"><i class="fa-brands fa-tiktok"></i></a></li>
            </ul>
        </div>

      <div class="col-1 ms_testopiccolo">
        <h5>Services</h5>
        <ul class="nav flex-column">
            <li v-for="(link, i) in footLinks" :key="i" class="nav-item mb-2">
                <a href="#"
                class="nav-link p-0 text-muted"
                :class="(activePage == i)">
                {{link}}</a>
            </li>        
        </ul>
      </div>

      <div class="col-1 ms_testopiccolo mx-5">
        <h5>Resources</h5>
        <ul class="nav flex-column">
            <li v-for="(link, i) in footLinks" :key="i" class="nav-item mb-2">
                <a href="#"
                class="nav-link p-0 text-muted"
                :class="(activePage == i)">
                {{link}}</a>
            </li>
        </ul>
      </div>

      <div class="col-1 ms_testopiccolo">
        <h5>Company</h5>
        <ul class="nav flex-column">
            <li v-for="(link, i) in footLinksTre" :key="i" class="nav-item mb-2">
                <a href="#"
                class="nav-link p-0 text-muted"
                :class="(activePage == i)">
                {{link}}</a>
            </li>
        </ul>
      </div>

    </div>

    <div class="d-flex justify-content-around py-4 my-4 fondo_footer">
        <p class="ms-auto">© 2021 Company, Inc. All rights reserved.</p>
        <p class="ms-auto me-auto">Call Us (555) 802-1234</p>
        <p class="me-auto">info@yourcompany.com</p>
    </div>

  </footer>
</template>

<script>
export default {
    name:"MyFooter",
    data() {
        return {
            footLinks: ['Marketing Plan', 'Sales Development', 'Digital Marketing', 'Pricing', 'Why Us', 'Case Studies'],
            footLinksDue: ['Learning Center', 'Video Tutorials', 'Customers', 'Blog'],
            footLinksTre: ['Who We Are', 'Contact Us', 'Carrers'],
            activePage: 0,
            isHidden: true
        }
    }}
</script>

<style scoped lang="scss">
@import '../style/generali.scss';

footer {
    padding-top: 6rem;
    overflow-x: hidden;

    .contenitore_chat {

        height: 110px;
        width: 190px;
        right: 25px;
        bottom: -220px;
        border-radius: 5px;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);

        .ms_sfera_account {
            background-image: url(../assets/images/marketing-expert-cta.png);
            background-size: cover;
            height: 40px;
            width: 40px;
            border-radius: 50%;
            margin: auto;
            margin-top: 20px;
            top: -45px;
            right: 75px;
        }

        .contenitore_interno_chat{

            padding-top: 17px;
            padding-left: 9px;
            width: 180px;

            p {
                font-size: 11px;
                font-weight: 400;
            }
        }



        .contenitore_X {

            width: 15px;
            height: 15px;
            background-color: transparent;
            top: 5px;
            right: 7px;
            cursor: pointer;


            .barra_uno{
                width: 1px;
                height: 10px;
                background-color: black;
                top: 2px;
                left: 7px;
                transform: rotate(45deg);
            }

            .barra_due{
                width: 1px;
                height: 10px;
                background-color: black;
                bottom: 3px;
                right: 7px;
                transform: rotate(135deg);
            }
        }
    }

    .contenitore_bottone_chat {
        width: 40px;
        height: 40px;
        background-color: #f76210;
        bottom: -275px;
        right: 25px;
        border-radius: 50%;
        cursor: pointer;

        .primo_mess {
            top: 12px;
            left: 13px;
            color: #f76210;
            z-index: 3;
        }

        .secondo_mess {
            bottom: 11px;
            right: 12px;
            color: white;
            z-index: 4;
        }

        .quarto_mess {
            bottom: 13px;
            right: 10px;
            color: white;
            z-index: 2;
        }
    }

    .ms_social {
        h5 {
            font-size: 16px;
        }

        ul li {
            font-size: 11px;
        }
    }

    .ms_testopiccolo {

        h5 {
            font-size: 14px;
        }

        li {
            font-size: 10px;
        }
    }

    .fondo_footer p {
        font-size: 8px;
        font-weight: 300;
    }
}
</style>