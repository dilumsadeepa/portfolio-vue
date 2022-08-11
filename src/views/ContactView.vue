<template>
  <NavBarVue />
  <br><br><br><br>

    <div class="container bac">
        <h2 class="contact">Contact Me</h2>
            <br>
        <div class="row">
            
            <div class="col-sm-5 con-box">
                <div class="ico"><i class="bi bi-geo-alt-fill"></i></div>
                
                <div class="con-info">
                    <h3>My Address</h3>
                    <p>No.40, Aluth Dambewatana, Senapura, Ipalogama, Anuradhapura. 50284</p>
                </div>
            </div>

            <div class="col-sm-5 con-box">
                <div class="ico"><i class="bi bi-link-45deg"></i></div>
                
                <div class="con-info">
                    <h3>Social Profiles</h3>
                    <p><ul class="nav" type="none">
                        <li class="nav-item"><a href="tel:+94789843284" class="bi bi-telephone-fill nav-link"></a></li>
              <li class="nav-item"><a href="https://wa.me/0789843284" class="bi bi-whatsapp nav-link"></a></li>
              <li class="nav-item"><a href="mailto:dilumhello@gmail.com" class="bi bi-envelope-fill nav-link"></a></li>
              <li class="nav-item"><a href="https://github.com/dilumsadeepa" class="bi bi-githubnav-link"></a></li>
              <li class="nav-item"><a href="https://www.facebook.com/dilum.sadeepa.7" class="bi bi-facebook nav-link"></a></li>
              <li class="nav-item"><a href="https://www.linkedin.com/in/dilum-sadeepa-b077801a4/" class="bi bi-linkedin nav-link"></a></li>
                        </ul></p>
                </div>
            </div>

            <div class="col-sm-5 con-box">
                <div class="ico"><i class="bi bi-envelope-fill"></i></div>
                
                <div class="con-info">
                    <h3>Email Me</h3>
                    <p>dilum19990612@gmail.com<br>
                    dilumhello@gmail.com<br>
                    dilumsadeepa@outlook.com</p>
                </div>
            </div>

            <div class="col-sm-5 con-box">
                <div class="ico"><i class="bi bi-telephone-fill"></i></div>
                
                <div class="con-info">
                    <h3>Call me</h3>
                    <p>(+94) 789843284<br>
                    (+94) 701832929 </p>
                </div>
            </div>


        </div>

        <br><br>

        <div class="row">
            <div class="col-sm-12">
                <div class="embed-responsive embed-responsive-21by9">
                    <iframe class="embed-responsive-item" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3173.554207219221!2d80.46926643101028!3d8.078182405023352!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3afc94c4e0963299%3A0xe11cc7aa648660d6!2zOMKwMDQnNDIuMSJOIDgwwrAyOCcwOC42IkU!5e1!3m2!1sen!2slk!4v1660194228041!5m2!1sen!2slk" allowfullscreen width="100%" height="80%"></iframe>
                </div>
            </div>
        </div>
        <br><br>
    </div>

</template>

<script>
import NavBarVue from '../components/NavBar.vue'
export default {
    components:{
        NavBarVue
    }

}
</script>

<style>

    .bac{
        background-color: #06061c;
        color:white;
    }

    .contact{
        padding: 10px;
        margin: 5px;
        border-bottom: 2px solid green;
    }

    .con-box{
        padding: 20px;
        margin: 40px;
        background-color: #2f2f30;
        display: inline-flex;
    }

    @media only screen and (max-width: 600px) {
        
        .con-box {
            padding: 5px;
            margin: 2px;
            width: 80%;
        }
    }

    .ico{
        padding: 15px;
        margin-top: 15px;
        font-size: 30px;
        color: #13e836;
    }

    .con-info p{
        color: #e81341;
    }

</style>