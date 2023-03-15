<template>
  <div class="container-fluid mt-2" > 
    
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

<!--
  <button @click="DENE">DENEE</button>
<br>
<input type="text" v-model="sayı1">
<input type="text" v-model="sayı2">
 <button @click="topla">topla uste gonder</button>
 -->
</div>


</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>
