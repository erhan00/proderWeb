<template>
   <div>
      <!--arka plan footer : #9FB8AD-->
      <div class="row" style="background-color:#212121;">
        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-dark"><h3 style="background-color:#E57373;border-radius: 10px;">İletişim Bilgileri</h3></strong>
         
            <li class="text-white" style="font-family: italic;">
                <img src="../assets/172496_location_icon.png" class=" mt-4" style="width: 30px;background-color:#DF2E38; height: 30px; "><br>
                <h6 class="mt-2"><code class="text-white">
                    Konya Teknokent Selçuk Universitesi Teknoloji Geliştirme Bölgesi Akademi Mah. Gürbulut Sok. 
                      Safir Panorama Blok Kat: 2 No: 202 Selçuklu / KONYA</code>
                </h6>
            </li>
            <li>
                <img src="../assets/33860_tel_telephone_icon.png" class="mt-3" style="width: 35px;height: 30px; border-radius: 5px;height: 27px;background-color:white; "><br><h6 class="text-white">0332 321 36 66</h6><br>
                <img src="../assets/4691507_gmail_icon.png" style="width: 35px;height: 30px; border-radius: 5px;height: 27px;background-color:white;"><br><a href="#" style="text-decoration: none;"> <h5>web@proder.com.tr</h5></a>
            
            </li><br>
            <li>
                <span class="text-white"><h6>Social Media</h6></span>
                <a href="#"><img src="../assets/9040489_globe_icon.png" class="mx-2 mt-1 EFEKT1" style="width: 30px;height: 30px;"></a>
              <a href="#"><img src="../assets/4691507_gmail_icon.png" class="mx-2 mt-1 EFEKT1" style="width: 30px;height: 30px;"></a>
              <a href="#"><img src="../assets/211904_social_github_icon.png" class="mx-2 mt-1 EFEKT1" style="width: 30px;height: 31px;"></a>
            </li>
          
        </ul>

        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-dark"> <h3 style="background-color:#E57373;border-radius: 10px;"> Bayilik</h3></strong>
          <img src="../assets/bayi.png" style="width: 30px;height: 30px; background-color:#DF2E38;" class=" mt-4"><br>

          <li class="text-white mt-2" style="font-family: italic;">
             <h6>Bayilerimiz</h6>
          </li>
          <li class="text-white mt-2" style="font-family: italic;">
             <h6>Bayimiz Olun</h6>
          </li>
          <li class="text-white mt-2" style="font-family: italic;">
             <h6>Online Bayilik Başvurusu</h6>
          </li>
          <li class="text-white mt-2" style="font-family: italic;">
             <h6>Neden Proder</h6>
          </li>

          
        </ul>
        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-dark"> <h3 style="background-color:#E57373;border-radius: 10px;"> Çözümler</h3></strong>
          <img src="../assets/ıkon.png" style="width: 30px;height: 30px; background-color: #DF2E38;" class=" mt-4"><br>

          <li class="text-white mt-2" style="font-family: italic;">
             <h6>Ticari Yazılımlar</h6>
          </li>
          <li class="text-white" style="font-family: italic;">
             <h6>Sektörel Yazılımlar</h6>
          </li>
          <li class="text-white" style="font-family: italic;">
             <h6> Web Yazılımlar </h6>
          </li>
          <li class="text-white" style="font-family: italic;">
             <h6>Mobil Yazılımlar</h6>
          </li>
        </ul>
        
        

        <ul class="col-sm-3 mt-5" style="list-style: none;"><strong class="text-dark"> <h3 style="background-color:#E57373;border-radius: 10px;"> Blog</h3></strong>
           <label>email</label>
           <input type="text" v-model="içerik">
           <h4>{{içerik}}</h4>
          
        </ul><br>
        
        <h6 style="text-align: center;color: antiquewhite;"> © 2005 - 2020 PRODER YAZILIM İLETİŞİM SİSTEMLERİ TİC. A.Ş. - Her Hakkı Saklıdır.</h6>
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