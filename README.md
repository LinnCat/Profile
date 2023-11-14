{% extends 'core/base.html' %}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{% block title %}SELAMAT DATANG{% endblock %}</title>
    {% block htmlhead %} 
    {% load static %}
    <link rel="stylesheet" href="{% static 'index.css' %}">
    {% endblock htmlhead %}
</head>
<body>
    {% block content %}


    <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://awsimages.detik.net.id/visual/2021/05/21/warga-palestina-bentrok-di-tepi-barat_169.jpeg?w=400&q=90" class="d-block w-100 mx-auto" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://asset-2.tstatic.net/medan/foto/bank/images/Pengertian-dan-macam-macam-teori-konflik.jpg" class="d-block w-100 mx-auto" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://asset.kompas.com/crops/AviqhhqwnWPAFK9mEW0qKXH1P0Q=/0x100:1200x900/750x500/data/photo/2019/09/30/5d9144ad5cb95.jpg" class="d-block w-100 mx-auto" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <a class="weatherwidget-io" href="https://forecast7.com/en/n6d92107d62/bandung/" data-label_1="BANDUNG" data-label_2="CUACA" data-theme="pure" >BANDUNG CUACA</a>

      <script>
        !function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
        </script>

<div class="container text-center">
    <div class="row">
    <div class="col">
      <img src="https://suaraaisyiyah.id/wp-content/uploads/2020/07/palestina.jpg">
    </div>
    <div class="col">
        <br>
    <H6> HAMAS SENDIRIAN MELAWAN ISRAEL DI GAZA</H6>
    <br>    
    <p>Dunia masih terguncang dengan serangan kelompok Hamas terhadap Israel pada tanggal 7 Oktober, rentetan serangan balasan Israel, dan perkiraan invasi darat Israel ke Jalur Gaza.</p>
    <p>Ultimatum ini muncul pada hari Minggu ketika mereka merasa kelompok perlawanan Palestina di Gaza, Hamas, berjuang sendirian melawan militer Zionis Israel.</p>
    <p>Kelompok ini mengaku sebagai anggota kelompok Fatah Palestina yang tergabung dalam berbagai cabang keamanan Otoritas Palestina di Tepi Barat, wilayah yang diduduki Israel.</p>
    <p>“Kami tetap bersabar terhadap kejahatan pendudukan. Kami tetap bersabar dengan kesunyian dan ketidakberdayaan kami..Dengan menjalankan perintah (resmi) sementara kami dicabik-cabik setiap hari dan setiap menit oleh gambar anak-anak dan perempuan yang dimutilasi (di Gaza)," lanjut pernyataan kelompok tersebut.</p>
    </div>
  </div>
</div>

<div class="container text-center">
  <div class="row">
    <div class="col">
      <h5>UPDATED NEWS TODAY</h5>
    </div> <br> <br>
    </div>
  </div>

  <!-- Card updated news -->
<div class="container text-center">
    <div class="row">
      <div class="col">
        <div class="card mb-3" style="max-width: 540px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="https://cdn.24.co.za/files/Cms/General/d/7807/58cd67819e524e838319b037fbe36244.jpg" class="img-fluid rounded-start" alt="...">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">High Engine Smokey Nagata</h5>
                  <p class="card-text">Aksi Smoky yang paling legendaris adalah ketika ia melakukan tes kecepatan maksimum Supra 0-300 yang ia lakukan di jalan tol A1 di Inggris. Rupanya setelah berhasil mencetak angka 318km/h, ia ditangkap oleh polisi setempat, dan sempat divonis penjara serta dilarang mengemudi di Inggris.</p>
                  <p class="card-text"><small class="text-body-secondary">Last updated 3 mins ago</small>
                  </p> <button type="button" class="btn btn-primary btn-sm" onclick="location.href='/isiberita'">Klik untuk melihat</button>
                </div>
              </div>
            </div>
          </div>
      </div>
      <div class="col">
        <div class="card mb-3" style="max-width: 540px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="https://akcdn.detik.net.id/community/media/visual/2020/10/20/ssc-tuatara-8.jpeg?w=700&q=90" class="img-fluid rounded-start" alt="...">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">SSC Tuatara, Inilah Mobil Tercepat Dunia</h5>
                  <p class="card-text">Hypercar tersebut berhasil mencapai kecepatan tertinggi rata-rata dua arah 455,3 km/jam, rekor itu cukup untuk mengalahkan pemegang rekor sebelumnya, Koenigsegg Agera RS, yang mencapai 446,97 km/jam (277,87 mph) pada tahun 2017.</p>
                  <p class="card-text"><small class="text-body-secondary">Last updated 3 mins ago</small></p>
                  <button type="button" class="btn btn-primary btn-sm" onclick="location.href='/isiberita'">Klik untuk melihat</button>
                </div>
              </div>
            </div>
          </div>
        </div>
        </div>
        </div>

        <div class="container text-center">
            <div class="row">
              <div class="col">
                <div class="card" style="width: 15rem;">
                    <img src="https://akcdn.detik.net.id/visual/2023/10/18/presiden-as-joe-biden-menghadiri-pertemuan-dengan-perdana-menteri-israel-benjamin-netanyahu-saat-ia-mengunjungi-israel-di-teng-1_169.jpeg?w=715&q=90" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Menteri Israel Ancam Nuklir Gaza, AS Akhirnya Buka Suara</h5>
                      <p class="card-text">Amerika Serikat mengecam komentar anggota junior kabinet Israel yang menyuarakan keterbukaan terhadap gagasan Israel.</p>
                    </div>
                  </div>
              </div>
              <div class="col">
                <div class="card" style="width: 15rem;">
                    <img src="https://akcdn.detik.net.id/community/media/visual/2023/11/05/kamp-pengungsi-maghazi-di-gaza-diserang-israel-30-orang-tewas-4_169.jpeg?w=700&q=90" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Ratusan Ribu Pekerjaan di Gaza Hilang Buntut Konflik</h5>
                      <p class="card-text">Badan Tenaga Kerja Perserikatan Bangsa-Bangsa (PBB) mencatat 61% pekerjaan hilang di Gaza akibat perang.</p>
                    </div>
                  </div>
              </div>
              <div class="col">
                <div class="card" style="width: 15rem;">
                    <img src="https://akcdn.detik.net.id/visual/2023/11/07/yahya-sinwar-pemimpin-hamas-di-gaza-memimpin-pertemuan-dengan-para-pemimpin-faksi-palestina-di-kantornya-di-kota-gaza-ap-photo_169.jpeg?w=715&q=90" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title"> Siapa Yahya Sinwar, Pentolan Hamas yang Jadi Buronan Israel?</h5>
                      <p class="card-text">Kelompok pejuang Palestina, Hamas, menjadi sorotan dunia internasional. Pada 7 Oktober lalu, dengan persenjataan lengkap.</p>
                    </div>
                  </div>
              </div>
              <div class="col">
                <div class="card" style="width: 15rem;">
                    <img src="https://akcdn.detik.net.id/community/media/visual/2023/11/02/rumah-sakit-indonesia-di-jalur-gaza.jpeg?w=700&q=90" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h5 class="card-title">Bantah Tuduhan Israel Soal Terowongan Hamas</h5>
                      <p class="card-text">Tim pembangunan Rumah Sakit (RS) Indonesia-Palestina membantah tuduhan Israel</p>
                    </div>
                  </div>
              </div>
            </div>
            </div>

             <!-- Site footer -->
    <footer class="site-footer">
        <div class="container">
          <div class="row">
            <div class="col-sm-12 col-md-6">
              <h6>About</h6>
              <p class="text-justify">Scanfcode.com <i>CODE WANTS TO BE SIMPLE </i> is an initiative  to help the upcoming programmers with the code. Scanfcode focuses on providing the most efficient code or snippets as the code wants to be simple. We will help programmers build up concepts in different programming languages that include C, C++, Java, HTML, CSS, Bootstrap, JavaScript, PHP, Android, SQL and Algorithm.</p>
            </div>
  
            <div class="col-xs-6 col-md-3">
              <h6>Categories</h6>
              <ul class="footer-links">
                <li><a href="http://scanfcode.com/category/c-language/">C</a></li>
                <li><a href="http://scanfcode.com/category/front-end-development/">UI Design</a></li>
                <li><a href="http://scanfcode.com/category/back-end-development/">PHP</a></li>
                <li><a href="http://scanfcode.com/category/java-programming-language/">Java</a></li>
                <li><a href="http://scanfcode.com/category/android/">Android</a></li>
                <li><a href="http://scanfcode.com/category/templates/">Templates</a></li>
              </ul>
            </div>
  
            <div class="col-xs-6 col-md-3">
              <h6>Quick Links</h6>
              <ul class="footer-links">
                <li><a href="http://scanfcode.com/about/">About Us</a></li>
                <li><a href="http://scanfcode.com/contact/">Contact Us</a></li>
                <li><a href="http://scanfcode.com/contribute-at-scanfcode/">Contribute</a></li>
                <li><a href="http://scanfcode.com/privacy-policy/">Privacy Policy</a></li>
                <li><a href="http://scanfcode.com/sitemap/">Sitemap</a></li>
              </ul>
            </div>
          </div>
          <hr>
        </div>
        <div class="container">
          <div class="row">
            <div class="col-md-8 col-sm-6 col-xs-12">
              <p class="copyright-text">Copyright &copy; 2017 All Rights Reserved by 
           <a href="#">Scanfcode</a>.
              </p>
            </div>
  
            <div class="col-md-4 col-sm-6 col-xs-12">
              <ul class="social-icons">
                <li><a class="facebook" href="#"><i class="fa fa-facebook"></i></a></li>
                <li><a class="twitter" href="#"><i class="fa fa-twitter"></i></a></li>
                <li><a class="dribbble" href="#"><i class="fa fa-dribbble"></i></a></li>
                <li><a class="linkedin" href="#"><i class="fa fa-linkedin"></i></a></li>   
              </ul>
            </div>
          </div>
        </div>
  </footer>

  
  
    {% endblock %}

</body>
</html>
