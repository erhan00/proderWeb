<template>
  <div class="container-fluid">
    <div class="row mt-1" style="background-color:#39AEA9">
      <div class="col-sm-5"><img class="mb-4 mt-2" src="./assets/proderlogo.gif" style="width: 50%;height: 58px;"></div>
      <div class="col-sm-1"></div>
      <div class="col-sm-6">
          <div class="row">
            <div class="col-sm-4 mx-3" style="border-style:inset;border-color:#3C6255; border-radius: 25px;">
              <router-link to=""><img src="./assets/9040489_globe_icon.png" class="mx-2 mt-1" style="width: 30px;height: 27px;"></router-link>
              <router-link to=""><img src="./assets/4691507_gmail_icon.png" class="mx-2 mt-1" style="width: 30px;height: 30px;"></router-link>
              <router-link to=""><img src="./assets/211904_social_github_icon.png" class="mx-2 mt-1" style="width: 30px;height: 31px;"></router-link>
               
            </div>
            <div class="col-sm-6">

               <img class="mt-2" src="./assets/contact.jpg" style="width: 35%; border-radius: 7px;"><br>
               <img class="mt-4" style=" height: 20px; border-radius: 7px;" src="./assets/slogan.png"></div>

            </div>
          </div>
    </div><!--***-->
    <nav class="navbar navbar-expand-sm navbar-dark" style="background-color:#F0DBDB;">
  <div class="container-fluid">
    <a class="navbar-brand mx-5" href="#"><img src="./assets/logox.png" style="margin-right: 45px;"></a>
    
    <div class="collapse navbar-collapse mx-5" id="collapsibleNavbar">
      <ul class="navbar-nav">

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"> <strong>Kurumsal</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="/" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"><strong> Ürünlerimiz</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>


        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"><strong> Bayilik</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="" class="dropdown-item">Link</router-link></li>
            <li><router-link to="" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>
        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Kampanyalar</strong></button>
        </li>
        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Dropdown</strong></button>
        </li>

        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Referanslar</strong></button>
        </li>  

        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#"><strong> Destek</strong></button>
        </li>  

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark" style="border-style: inset;border-color:brown" href="#" role="button" data-bs-toggle="dropdown"><strong> İletişim</strong></button>
          <ul class="dropdown-menu">
            <li><router-link to="/iletişim" class="dropdown-item">Link</router-link></li>
            <li><router-link to="/iletişim" class="dropdown-item">Another link</router-link></li>
            <li><router-link to="/iletişim" class="dropdown-item">A third link</router-link></li>
          </ul>
        </li>
        
      </ul>
    </div>

    <button style="border-radius: 7px;" class="navbar-toggle" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon bg-secondary"></span>
    </button>


  </div>
</nav>

  <!--
    <nav>
     <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  --><anasayfa/>
  <router-view/> 
  <!--<input type="text" ref="metin2"> -->
  <foterr/>
</div>

</template>
  
 <script>
   import foterr from './components/foterr.vue'
   export default {
    name: 'App',
    components :{
      foterr
    },
    data(){
      return{
        yazi:"erhan kalkan",
        yazı01:"kalkan69",
        sonuc:" ",
        sonuc02:0
      }
    },
    methods:{
       tıkla(){
         this.sonuc = this.$refs.metin.value;
       },
       SİL(){
        this.$refs.metin2.value='';
       },
       gelen(sonucc){
        this.sonuc02 =sonucc
       }
    }
   }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
