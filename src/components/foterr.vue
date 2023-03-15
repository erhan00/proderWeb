<template>
   <div>
      <div class="row" style="background-color: #9FB8AD;">
        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-danger"><h3 style="background-color:#b0edeb;border-radius: 10px;">İletişim Bilgileri</h3></strong>
         
            <li class="text-dark" style="font-family: italic;">
                <img src="../assets/172496_location_icon.png" class="bg-success mt-4" style="width: 30px;height: 30px; "><br>
                <h5 class="mt-2">
                    Konya Teknokent Selçuk Universitesi Teknoloji Geliştirme Bölgesi Akademi Mah. Gürbulut Sok. 
                      Safir Panorama Blok Kat: 2 No: 202 Selçuklu / KONYA
                </h5>
            </li>
            <li>
                <img src="../assets/33860_tel_telephone_icon.png" style="width: 30px;height: 30px; "><br><h5>0332 321 36 66</h5><br>
                <img src="../assets/4691507_gmail_icon.png" style="width: 30px;height: 30px;"><br><a href="#" style="text-decoration: none;"> <h5>web@proder.com.tr</h5></a>
            
            </li><br>
            <li>
                <span class="text-dark"><h5>Social Media</h5></span>
                <a href="#"><img src="../assets/9040489_globe_icon.png" class="mx-2 mt-2" style="width: 35px;height: 27px;"></a>
              <a href="#"><img src="../assets/4691507_gmail_icon.png" class="mx-2 mt-2" style="width: 35px;height: 30px;"></a>
              <a href="#"><img src="../assets/211904_social_github_icon.png" class="mx-2 mt-2" style="width: 36px;height: 31px;"></a>
            </li>
          
        </ul>

        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-danger"> <h3 style="background-color:#b0edeb;border-radius: 10px;"> Bayilik</h3></strong>
          <img src="../assets/bayi.png" style="width: 30px;height: 30px;" class="bg-success mt-4"><br>

          <li class="text-dark mt-2" style="font-family: italic;">
             <h5>Bayilerimiz</h5>
          </li>
          <li class="text-dark mt-2" style="font-family: italic;">
             <h5>Bayimiz Olun</h5>
          </li>
          <li class="text-dark mt-2" style="font-family: italic;">
             <h5>Online Bayilik Başvurusu</h5>
          </li>
          <li class="text-dark mt-2" style="font-family: italic;">
             <h5>Neden Proder</h5>
          </li>

          
        </ul>
        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-danger"> <h3 style="background-color:#b0edeb;border-radius: 10px;"> Çözümler</h3></strong>
          <img src="../assets/ıkon.png" style="width: 30px;height: 30px;" class="bg-success mt-4"><br>

          <li class="text-dark mt-2" style="font-family: italic;">
             <h5>Ticari Yazılımlar</h5>
          </li>
          <li class="text-dark" style="font-family: italic;">
             <h5>Sektörel Yazılımlar</h5>
          </li>
          <li class="text-dark" style="font-family: italic;">
             <h5> Web Yazılımlar </h5>
          </li>
          <li class="text-dark" style="font-family: italic;">
             <h5>Mobil Yazılımlar</h5>
          </li>
        </ul>
        
        

        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-danger"> <h3 style="background-color:#b0edeb;border-radius: 10px;"> Blog</h3></strong>
           <label>email</label>
           <input type="text" v-model="içerik">
           <h4>{{içerik}}</h4>
          
        </ul>

        
      </div>
   </div>
</template>

<script>

export default {

  data(){
    return{
      içerik:'erhan'
    }
  }

}
</script>

<style>

</style>