<template>

  <div class="container-fluid box">
    <div class="row">
      
      <div class="col-sm-8">
        <div class="box-head">
          <h1>Dilum Sadeepa</h1>
          <br>
          
          <h4>I'm an undergraduate student of the University of Ruhuna in Sri Lanka</h4>
          <br>
          <ul class="nav" type="none">
            <li class="nav-item"><RouterLink to="/" class="nav-link lc">Home</RouterLink></li>
            <li class="nav-item"><RouterLink to="/about" class="nav-link lc">About</RouterLink></li>
            <li class="nav-item"><RouterLink to="/resume" class="nav-link lc">Resume</RouterLink></li>
            <!--li class="nav-item"><RouterLink to="/about" class="nav-link lc">Awards</RouterLink></li-->
            <li class="nav-item"><RouterLink to="/project" class="nav-link lc">Projects</RouterLink></li>
            <li class="nav-item"><RouterLink to="/contact" class="nav-link lc">Contact</RouterLink></li>
          </ul>
          <br>
          <div class="link">
            <ul class="nav" type="none">
              <li class="nav-item"><a href="tel:+94789843284" class="bi bi-telephone-fill nav-link lc"></a></li>
              <li class="nav-item"><a href="https://wa.me/0789843284" class="bi bi-whatsapp nav-link lc"></a></li>
              <li class="nav-item"><a href="mailto:dilumhello@gmail.com" class="bi bi-envelope-fill nav-link lc"></a></li>
              <li class="nav-item"><a href="https://github.com/dilumsadeepa" class="bi bi-githubnav-link lc"></a></li>
              <li class="nav-item"><a href="https://www.facebook.com/dilum.sadeepa.7" class="bi bi-facebook nav-link lc"></a></li>
              <li class="nav-item"><a href="https://www.linkedin.com/in/dilum-sadeepa-b077801a4/" class="bi bi-linkedin nav-link lc"></a></li>
            </ul>
          </div>
        </div>
      </div>

      <div class="col-sm-2">
        <img src="/img/proimg.png" class="rounded-circle img-fluid float-right proimg" alt="Profile">
      </div>

    </div>

  </div>




</template>

<script>
export default {

}
</script>

<style>

  .box{
    height: 100vh;
    color: white;
    background-color: #06061c;
  }

  .box-head{
    top: 30vh;
    margin-top: 30vh;
    margin-left: 10%;
  }

  .proimg{
    border: 5px solid #32b1db;
    margin-top: 20vh;
    margin-left: 10%;
    animation: shake 1s linear infinite;
  }

  @keyframes shake{
    0%{
      transform: rotate(-3deg);
      transform: translateX(0px);
    }
    20%{
      transform: rotate(0deg);
      transform: translateX(-3px);
    }
    40%{
      transform: rotate(3deg);
      transform: translateX(0px);
    }
    60%{
      transform: rotate(-3deg);
      transform: translateX(0px);
    }
    80%{
      transform: rotate(4deg);
      transform: translateX(3px);
    }
    100%{
      transform: rotate(0deg);
      transform: translateX(0px);
    }
  }

  .lc{
    color:white;
  }

  .lc:hover{
    color: white;
    border-bottom: 2px solid #0af00a;
    transition-delay: 0.5;
  }

  .txin{
    padding: 10px;
    animation: borderrider 1s linear infinite;
  }

  @keyframes borderrider{
    0%{
      border-bottom: 2px solid #03fc0f;
    }
    25%{
      border-right: 2px solid #0398fc;
    }
    50%{
      border-top: 2px solid #9803fc;
    }
    100%{
      border-left: 2px solid #fc0341;
    }

    
  }

  

</style>