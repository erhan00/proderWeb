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
    </div>
    

    
  <!--
    <nav>
     <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  -->
  <router-view/>
  <anasayfa/>
  <!--<input type="text" ref="metin2"> -->
  <foterr/>
</div>

</template>
  
 <script>
   import anasayfa from './components/anasayfa.vue'
   import foterr from './components/foterr.vue'

   export default {
    name: 'App',
    components :{
      anasayfa,
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
