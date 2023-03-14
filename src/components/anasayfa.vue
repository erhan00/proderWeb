<template>
  <div class="container-fluid mt-2">
     <!--#1797a6-->
    <nav class="navbar navbar-expand-sm navbar-dark" style="background-color:#F0DBDB;">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img src="../assets/logox.png"></a>
    


    <div class="collapse navbar-collapse mx-5" id="collapsibleNavbar">
      <ul class="navbar-nav">

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"> <strong>Kurumsal</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"><strong> Ürünlerimiz</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>


        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"><strong> Bayilik</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>
        <li class="nav-item">
          <button class="nav-link btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Kampanyalar</strong></button>
        </li>
        <li class="nav-item">
          <button class="nav-link btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Dropdown</strong></button>
        </li>

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"><strong> Referanslar</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>

        <li class="nav-item">
          <button class="nav-link btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Destek</strong></button>
        </li>  

        <li class="nav-item">
          <button class="nav-link btn mx-3 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> İletişim</strong></button>
        </li>  

        
      </ul>
    </div>


    <button class="navbar-toggle" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon bg-secondary"></span>
    </button>


  </div>
</nav>


<div id="demo" class="carousel slide" data-bs-ride="carousel">

<!-- Indicators/dots -->
<div class="carousel-indicators">
  <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active bg-primary"></button>
  <button type="button" data-bs-target="#demo" data-bs-slide-to="1" class="bg-primary"></button>
  <button type="button" data-bs-target="#demo" data-bs-slide-to="2" class="bg-primary"></button>
  <button type="button" data-bs-target="#demo" data-bs-slide-to="3" class="bg-primary"></button>

</div>

<!-- The slideshow/carousel -->
<div class="carousel-inner">
  <div class="carousel-item active">
    <img src="../assets/01010.png" alt="solution01" class="d-block mt-2" style="height: 420px;width:80%; margin-left: 60px;">
    <div class="carousel-caption">
      <h3 class="text-danger">Proder</h3>
      <p class="text-danger">Profesyonel Solution</p>
    </div>
  </div>
  <div class="carousel-item">
    <img src="../assets/0303.png" alt="solution02" class="d-block mt-2" style="height: 420px;width:80%;margin-left: 130px;">
    <div class="carousel-caption">
        <h3 class="text-danger">Proder</h3>
      <p class="text-danger">Profesyonel Solution</p>
    </div> 
  </div>
  <div class="carousel-item">
    <img src="../assets/01.png" alt="solution03" class="d-block mt-2" style="height: 420px;width:80%;margin-left: 150px;">
    <div class="carousel-caption">
        <h3 class="text-danger">Proder</h3>
      <p class="text-danger">Profesyonel Solution</p>
    </div>  
  </div>

  <div class="carousel-item">
    <img src="../assets/0404.jpg" alt="solution04" class="d-block mt-2" style=" height: 420px;width:80%;margin-left: 100px;">
    <div class="carousel-caption">
        <h3 class="text-danger">Proder</h3>
      <p class="text-danger">Profesyonel Solution</p>
    </div>  
  </div>
</div>

<!-- Left and right controls/icons -->
<button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
  <span class="carousel-control-prev-icon bg-secondary"></span>
</button>
<button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
  <span class="carousel-control-next-icon bg-secondary"></span>
</button>
</div>



  </div>

  
   
  
  




</template>

<script>

export default {
 name: 'anasayfa'
}
</script>

<style>

</style>