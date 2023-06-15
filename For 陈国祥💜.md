<html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
  
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="https://feeldreams.github.io/night/style.css" rel="stylesheet" type="text/css" />

<head>
<title>Script HTML Night</title>
<!-- 

  Made with love by Moon !
  
-->
</head>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="https://feeldreams.github.io/understand.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://raw.githubusercontent.com/IMG_4873.jpeg" id="wallpaper"/><div id="beneranblur"></div>
   </div>
   
   <div id='Content'>

     <div id="suratin" onClick="memulai();">
       <!-- Tombol Surat --><img src="https://raw.githubusercontent.com/moon/Love/main/%E2%80%94Pngtree%E2%80%94love%20balloon%20floating_6787317.png"/>
     </div>
     <p id="ket">Di Pegang Balonnya Ya bbyy wkwk :v ❤️</p>

     <div class="kumpulanstiker">
         
         <img src="https://feeldreams.github.io/pusn.gif" id="stiker1"/>
         <img src="https://feeldreams.github.io/bunga.gif" id="stiker2"/>
         <img src="https://feeldreams.github.io/mndkat.gif" id="stiker3"/>
         <img src="https://feeldreams.github.io/smprt.gif" id="stiker4"/>
         <img src="https://feeldreams.github.io/ngumpet.gif" id="stiker5"/>
       
         <img src="https://raw.githubusercontent.com/moon/pmoy/main/A453277C-1D0C-47BA-A7E5-C7F796DD89B1.gif" id="stiker"/>
     </div>
     <p id="halo">16 Mei 2023</p>

     <script class="sembunyi">
       async function pesanAwal() {
          suratin.style="display:none";ket.style="display:none";
          await swalst.fire({
            title: 'Hai, Hai bbyyy 陈国祥',
            imageUrl: '' + stiker1.src,
         });   	
         await swalst.fire({
            title: 'Aku Cuma Mau Bilang',
            imageUrl: '' + stiker2.src,
         });
         await swalst.fire({
            title: 'Happy Mensive ❤️',
            imageUrl: '' + stiker3.src,
         });
         await swalst.fire({
            title: 'Tencccyyuuu for everything',
            imageUrl: '' + stiker4.src,
         });
         await swalst.fire({
            title: 'Tencyuuu buat Kesabarannya',
            imageUrl: '' + stiker5.src,
         });
         mulaikonten();
       }
     </script>
     <div><blockquote id='bq'>

       <!-- Konten Pembukaan -->
       <p id="kalimat">Happy Mensive</p>
       <p id="kalimat2">maaciii udahh nemani akuuu, sampai jumpa di tangggal 16 berikutnya .</p>
       <p id="kalimatbawah">I Love You ❤️</p> 
       <p id="kalimatbawah2" class="sembunyi">I Miss You ❤️</p> 
       <p id="kalimatbawah3" class="sembunyi">16 Mei 2023 </p> 

     </blockquote></div>

     <!-- Tombol Multifungsi -->
     <div id="Tombol">
       <a onClick="multifungsi()">
         <b id="tmbl">张爱香 x 陈国祥
         </b>
     
     <!-- Pesan yang dikirim ke WhatsApp -->
     <span id="pesanWA" class="sembunyi">bukaa bbbyyy ❤️❤️❤️</span>
     
   </div>

<!-- Jangan Edit Bagian Ini --><script>
  ftom=0;aksift=0;ftganti=0;flag=1;flagg=1;fungsi=0;fungsiAwal=0;fungsitimer=0;vketikhalo=halo.innerHTML;
  halo.innerHTML = "";var ahalo=0,vketikhalo;pesanwhatsapp = pesanWA.innerHTML;
  Content.style = "opacity:1;margin-top:16vh;";
  
  async function menuju(){window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;}

  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2300, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,});
  audio = new Audio('' + linkmp3.src);
  
  function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
</script>
<script src="https://feeldreams.github.io/night/script.js"></script>
<!-- Sampai Sini -->
</body>
</html>
