<template>
  <div class="container-fluid">
    <div class="row mt-1" style="background-color:#da414d">
      <div class="col-sm-5"><img class="mb-3 mt-3 LOGO" src="./assets/proderlogo.gif"></div>
      <div class="col-sm-1"></div>
      <div class="col-sm-6">
          <div class="row">
            <div class="col-sm-4 mx-3 mt-2 EFEKT2">
              <router-link to=""><img src="./assets/9040489_globe_icon.png" class="mx-2 mt-2 EFEKT1" style="width: 30px;height: 27px;"></router-link>
              <router-link to=""><img src="./assets/4691507_gmail_icon.png" class="mx-2 mt-2 EFEKT1" style="width: 30px;height: 30px;"></router-link>
              <router-link to=""><img src="./assets/211904_social_github_icon.png" class="mx-2 mt-2 EFEKT1" style="width: 30px;height: 31px;"></router-link>
               
            </div>
            <div class="col-sm-6">

               <img class="mt-2 mb-3" src="./assets/contact.jpg" style="width: 35%; border-radius: 7px;"><br>
              <span style="background-color: gainsboro;border-radius: 7px; padding: 6px;"><strong> "Profesyonel</strong> <span > düşünenler </span><strong>  için!..."</strong></span>
              </div>

            </div>
          </div>
    </div><!--***-->
    <nav class="navbar navbar-expand-sm navbar-dark" style="background-color:#CFD8DC; box-shadow: 3px 10px 10px #B0BEC5	;">
  <div class="container-fluid">
    <a class="navbar-brand mx-5" href="#"><img src="./assets/logox.png" style="margin-right: 45px;"></a>
    
    <div class="collapse navbar-collapse mx-2" id="collapsibleNavbar">
      <ul class="navbar-nav">
        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark EFEKT" style="height: 50px;" href="#" role="button" data-bs-toggle="dropdown">
            <strong class="EFEKT">Kurumsal</strong></button>
          <ul class="dropdown-menu">
            <li class="dropdown-item MENU"><strong class="MenuAlt">Proder Hakkında</strong></li>
            <li><router-link to="/" class="dropdown-item BİLGİ1">Kurumsal Kimlik</router-link></li>
            <li><router-link to="" class="dropdown-item BİLGİ1">Misyon & Vizyon</router-link></li>
            <li><router-link to="" class="dropdown-item BİLGİ1">Yasal Haklar</router-link></li>
            <li><router-link to="" class="dropdown-item BİLGİ1">Evraklarımız</router-link></li>
            <li><router-link to="" class="dropdown-item BİLGİ1">Kredi Kartı ile Online Ödeme</router-link></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark EFEKT" style="height: 50px" href="#" role="button" data-bs-toggle="dropdown">
            <strong class="EFEKT" > Ürünlerimiz</strong></button>

          <div class="dropdown-menu" style="">
        
            <div class="col-sm-6 dropdown-item" style="border-style: double;display: inline;">
              <h5 class="" style="display: inline;">kalkan erhan</h5><br>
              <h5 class="" style="display: inline;">kalkan erhan</h5><br>
              <h5 class="" style="display: inline;">kalkan erhan</h5>
            </div>

           <div class="col-sm-6 dropdown-item" style="border-style: double;display: inline;">
            <h5 class="dropdown-item" style="display: inline;">kalkan erhan</h5>
          </div>
        </div>
        </li>


        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark EFEKT" style="height: 50px" href="#" role="button" data-bs-toggle="dropdown">
           <strong class="EFEKT"> Bayilik</strong></button>
          <ul class="dropdown-menu" style="width: 240px;">
          <li class="dropdown-item MENU"><strong class="MenuAlt">Bayilerimiz</strong></li>
            
             <li><router-link to="" class="dropdown-item BİLGİ1">Bayi Giriş</router-link></li>
             <li><router-link to="" class="dropdown-item BİLGİ1">Bayi Haritası</router-link></li>
             <li><router-link to="" class="dropdown-item BİLGİ1">İstek ve Öneriler</router-link></li>
            
             <li class="dropdown-item MENU"><strong class="MenuAlt"> Bayimiz Olun</strong></li>
             <li><router-link to="" class="dropdown-item BİLGİ1">Bayi Giriş</router-link></li>
             <li><router-link to="" class="dropdown-item BİLGİ1">Bayi Haritası</router-link></li>
             <li><router-link to="" class="dropdown-item BİLGİ1">İstek ve Öneriler</router-link></li>
        </ul>
        </li>
        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="height: 50px;" href="#"><strong class="EFEKT"> Kampanyalar</strong></button>
        </li>
        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="height: 50px" href="#"><strong class="EFEKT"> Dropdown</strong></button>
        </li>

        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="height: 50px" href="#"><strong class="EFEKT"> Referanslar</strong></button>
        </li>  

        <li class="nav-item">
          <button class="nav-link btn mx-1 text-dark" style="height: 50px" href="#"><strong class="EFEKT"> Destek</strong></button>
        </li>  

        <li class="nav-item dropdown">
          <button class="nav-link dropdown-toggle btn mx-1 text-dark EFEKT" style="height: 50px" href="#" role="button" data-bs-toggle="dropdown">
           <strong class="EFEKT"> İletişim</strong></button>
          <ul class="dropdown-menu">
            <li class="dropdown-item MENU"><strong class="MenuAlt"> Proder İletişim Bilgileri</strong></li>
            <li><router-link to="/iletişim" class="dropdown-item BİLGİ1">İrtibat Adresleri</router-link></li>
            <li><router-link to="/iletişim" class="dropdown-item BİLGİ1">Banka Hesap Bilgileri</router-link></li>
            <li><router-link to="/iletişim" class="dropdown-item BİLGİ1">Bize Yazın</router-link></li>
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
      
      } 
    },
    methods:{

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
.LOGO{
   width: 50%;height: 60px;
   border-radius: 10px;
   background-color: white;
  }
  .LOGO:hover{
    transform: scale(1.1  );
  }
.EFEKT{
  position: relative;
  display: block;
  transition: .5s;
  font-size: 16px;
  font-family: Verdana;
}
.EFEKT::after{
  position: absolute;
  width: 100%;
  top:100%;
  left: 0;
  transition: transform .3s;
  transform: scaleX(0);
  transform-origin: right;
}
.EFEKT:hover{
  color:#2962FF ;
  transition: 0.4s;
}
.EFEKT:hover::after{
  transform: scaleX(1);
  transform-origin: left;
  color:#0D47A1	;
}
.EFEKT1{
   background-color:#80DEEA;
   border-radius:1px 8px;
    }
  .EFEKT1:hover{
      transform: scale(1.2);
  }
    .EFEKT2{
      border-bottom-style:inset;
      border-width: 7px;
      border-radius: 7px;
      border-color:#455A64 ;
    }
.EFEKT2:hover{
  border-bottom-style:inset;
   border-color:#2F4F4F		;
}
.MENU-KART{
  border-bottom-style:inset;
  border-color:#2F4F4F		;
}
.BİLGİ1:hover{
   color:#FF0000AD;
}
.MENU{
  background-color:#90A4AE
}
.MenuAlt{
  font-family: Verdana;
  color:#FF0000AD;
  border-bottom-style: inset;
  border-color:#000000
}
  </style>
