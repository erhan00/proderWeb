<template>
  <div>
    <div class="row">
      <div class="col-sm-5">
        <div class="card" style="margin-top:100px"> 
          <img class="card-img-top mx-4" style="width: 25%;height: 30%;" alt="" src="../assets/proderlogo.gif">
          <div class="card-header"><h4 class="text-primary">Proder Yazılım</h4></div>
          <div class="card-body"><h6><strong> Konya Teknokent Selçuk Universitesi Teknoloji Geliştirme Bölgesi Akademi Mah.
                 Gürbulut Sok. Safir Panorama Blok Kat: 2 No: 202 Selçuklu / KONYA</strong>
          </h6></div>
        </div>
      
      <div class="card mt-3">
        <img class="card-img-top mx-4" style="width: 10%;height:45px" alt="" src="../assets/dene.jpg">
        <div class="card-header"><h4 class="text-primary"> Diğer İletişim Merkezleri</h4></div>
                <div class="card-body"><h6>
                 <strong> Çağrı Merkezi:</strong> 444 21 25<br><br><strong>Adres: </strong>
                   ESENTEPE MAH. GÜNEY SK. DURMAZ İŞ MERKEZİ<br> NO:2 KAT 3/3/ BURSA<br><br>
                   <img src="../assets/ıkon.png" class="bg-danger mt-2 mb-2" style="width: 8%; height: 35px;border-radius: 7px;"><br>
                  <strong>  Çağrı Merkezi:</strong> 444 21 25<br><br>
                 <strong> Adres:</strong> Sonsbeeksingel 110, 6822 BJ Arnhem / NEDERLAND  ( HOLLANDA )
                </h6></div>
      </div>

      <div class="card mt-3">
        <img class="card-img-top mx-4" style="width: 10%;height:45px" alt="" src="../assets/dene.jpg">
        <div class="card-header"><h4 class="text-primary"> Telefon  & E-Posta</h4></div>
            <div class="card-body"><h6>
                 <strong>Çağrı Merkezi:</strong>  444 21 25<br><br>

                  (+90) 332 262 00 88 (PBX)<br>
                  (+90) 332 262 00 15<br><br>
                  <img src="../assets/4691507_gmail_icon.png" class="mt-2 mb-2 bg-danger" style="width: 8%; border-radius: 7px; height: 35px;"><br>

                      <strong> Genel :</strong> <a href="info@proder.com.tr" style="text-decoration: none;">info@proder.com.tr</a><br>
                      <strong> Destek :</strong><a href="destek@proder.com.tr" style="text-decoration: none;">destek@proder.com.tr</a><br> 
                      <strong> Bayi :</strong><a href="bayi@proder.com.tr" style="text-decoration: none;">bayi@proder.com.tr</a> <br><br>
                      <strong> İnsan Kaynakları :</strong><a  href="insankaynaklari@proder.com.tr" style="text-decoration: none;;">insankaynaklari@proder.com.tr</a><br>
                      <strong> Pazarlama :</strong><a href="pazarlama@proder.com.tr" style="text-decoration: none;">pazarlama@proder.com.tr</a>                                     
                  
            </h6></div>
          </div>
    </div> 

     <div class="col-sm-2" style="margin-top:100px"></div>

      <div class="col-sm-5" style="margin-top:100px">

        <form action="/action_page.php" class="mt-4 was-validated">
    <div class="form-floating mb-3 mt-3">
      <input type="text" class="form-control" id="user" style="width: 75%;height: 50px;" placeholder="name username" name="kullanıcı" required>
      <label for="user">Ticari Ünvan / Ad Soyad</label>
    </div>
    <label for="browser"  class="form-label">Konu Seçiniz :</label>
    <select style="width: 75%;" class="form-select form-select-sm mt-3">
     <option>Genel</option>
     <option>Şikayet</option>
     <option>Bilgi</option>
     <option>Servis Talep</option>
     <option>Diğer</option>
   </select>
   
   <div class="mt-3">
   <label for="browser" class="form-label">İletişim Tercihi :</label>
   <select style="width: 75%;" class="form-select form-select-sm mt-3">
     <option>E-posta</option>
     <option>Telefon</option>
   </select>
   
  </div>

    <div class="form-floating mb-3 mt-5">
      <input type="text" class="form-control" id="email" style="width: 80%;height: 50px;" placeholder="Enter email" required name="email">
      <label for="email">E-posta Adresi</label>
    </div>
    <div class="form-floating mt-4 mb-3">
      <input type="text" class="form-control" style="width: 80%;height: 50px;" id="pwd" placeholder="tel" required name="tel">
      <label for="pwd">Telefon</label>
    </div>
    <div class="form-floating mt-4 mb-3">
      <input type="text" class="form-control" style="width: 80%;height: 50px;" id="adrs" placeholder="adres bilgi" required name="adrs">
      <label for="adrs">Adres</label>
    </div>
    <div class="mb-3 mt-3">
      <label for="comment">Comments:</label>
      <textarea class="form-control" rows="5" style="width: 90%;" id="comment" name="text"></textarea>
    </div>
    
     <h6 class="text-dark"> *
       Sitemizi daha faydalı kılmak ve hizmet kalitemizi arttırmak <br>amacıyla öneri, şikayet ve isteklerinizi 
       bizimle paylaşabilirsiniz. İlginize Teşekkür Ederiz</h6>
       <button type="submit" class="btn btn-success mt-4">İleti Gönder</button>
  </form>

      </div>
     </div>
     <div class="alert alert-danger mt-3">
      <button type="button" class="">xx</button>
    <strong>Danger!</strong> You should <a href="#" class="alert-link">read this message</a>.
  </div>
  </div>
</template>

<script>
export default {
    components:{
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


 </style>