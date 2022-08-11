<template>
  <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <div class="container">
    <h2><RouterLink to="/" class="nav-link lc">Dilum Sadeepa</RouterLink></h2>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse mal" id="collapsibleNavbar">
      <ul class="nav" type="none">
            <li class="nav-item"><RouterLink to="/" class="nav-link lc">Home</RouterLink></li>
            <li class="nav-item"><RouterLink to="/about" class="nav-link lc">About</RouterLink></li>
            <li class="nav-item"><RouterLink to="/resume" class="nav-link lc">Resume</RouterLink></li>
            <!--li class="nav-item"><RouterLink to="/about" class="nav-link lc">Awards</RouterLink></li-->
            <li class="nav-item"><RouterLink to="/project" class="nav-link lc">Projects</RouterLink></li>
            <li class="nav-item"><RouterLink to="/contact" class="nav-link lc">Contact</RouterLink></li>
          </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {

}
</script>

<style>

.mal{
    margin-left: 20%;
}

</style>