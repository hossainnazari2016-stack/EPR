<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Echo PR | Kozmetik İletişim Ajansı</title>
  <style>
    body {font-family: 'Poppins', sans-serif; margin: 0; padding: 0; background-color: #fff; color: #222; overflow-x: hidden;}
    header {position: relative; color: #fff; text-align: center; overflow: hidden;}
    header video {width: 100%; height: 100vh; object-fit: cover; position: absolute; top: 0; left: 0; z-index: -1; filter: brightness(0.4);}
    header h1 {margin-top: 35vh; font-size: 3em; letter-spacing: 2px; animation: fadeIn 2s ease-in-out;}
    header p {font-style: italic; color: #eee; animation: fadeIn 3s ease-in-out;}

    @keyframes fadeIn {from {opacity: 0;} to {opacity: 1;}}
    @keyframes slideUp {from {transform: translateY(40px); opacity: 0;} to {transform: translateY(0); opacity: 1;}}

    .banner {background: linear-gradient(135deg, #ff7aa8, #ffcce0); color: #fff; text-align: center; padding: 60px 20px; animation: slideUp 2s ease-in-out;}
    .banner h2 {font-size: 2em; margin-bottom: 10px;}
    .banner p {font-size: 1.1em; margin-bottom: 20px;}
    .banner button {background-color: #fff; color: #b30059; border: none; padding: 12px 25px; border-radius: 25px; font-weight: bold; cursor: pointer; transition: 0.3s;}
    .banner button:hover {background-color: #b30059; color: #fff;}

    nav {display: flex; justify-content: center; background: #f3f3f3; padding: 12px 0; gap: 20px; border-bottom: 1px solid #ddd; position: sticky; top: 0; z-index: 10;}
    nav a {color: #000; text-decoration: none; font-weight: 600; transition: color 0.3s;}
    nav a:hover {color: #b30059;}

    section {max-width: 1000px; margin: 60px auto; padding: 0 20px; animation: fadeIn 1.5s ease-in-out;}
    h2 {color: #000; border-left: 4px solid #000; padding-left: 10px;}

    .grid {display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px;}
    .card {background: #fafafa; border-radius: 10px; padding: 20px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); transition: transform 0.3s;}
    .card:hover {transform: translateY(-5px);}

    .gallery {display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; margin-top: 20px;}
    .gallery img {width: 300px; border-radius: 10px; transition: transform 0.4s;}
    .gallery img:hover {transform: scale(1.05);}

    .socials {text-align: center; margin: 30px 0;}
    .socials a {margin: 0 10px; text-decoration: none; color: #b30059; font-size: 1.5em; transition: color 0.3s;}
    .socials a:hover {color: #ff7aa8;}

    iframe {width: 100%; height: 700px; border: none; border-radius: 10px; margin-top: 20px;}

    footer {background-color: #000; color: #fff; text-align: center; padding: 30px 10px; margin-top: 50px;}
  </style>
</head>
<body>
  <header>
    <video autoplay muted loop>
      <source src="https://cdn.pixabay.com/video/2022/08/09/126888-740812457_large.mp4" type="video/mp4">
    </video>
    <h1>Echo PR</h1>
    <p>Kozmetik Markalarına İletişim ve Marka Danışmanlığı</p>
  </header>

  <audio autoplay loop>
    <source src="https://cdn.pixabay.com/download/audio/2023/02/28/audio_5eb7350b73.mp3?filename=soft-piano-ambient-14081.mp3" type="audio/mp3">
  </audio>

  <div class="banner">
    <h2>#RujunuTazele Kampanyası 🎀</h2>
    <p>Güzelliğini tazele, markana ışıltı kat! Echo PR, kozmetik markaları için şeffaflık ve güven odaklı yeni dönem kampanyalarını başlatıyor.</p>
    <button>Kampanyayı İncele</button>
  </div>

  <nav>
    <a href="#hakkimizda">Hakkımızda</a>
    <a href="#hizmetler">Hizmetler</a>
    <a href="#projeler">Projeler</a>
    <a href="#galeri">Galeri</a>
    <a href="#iletisim">İletişim</a>
  </nav>

  <section id="hakkimizda">
    <h2>Hakkımızda</h2>
    <p>Echo PR, kozmetik markalarına özel iletişim stratejileri ve marka yönetimi hizmetleri sunan modern bir ajanstır. Hedefimiz, markaların dijital dünyada güçlü, güvenilir ve estetik bir imaj kazanmasını sağlamaktır. PR danışmanlığı, sosyal medya yönetimi, kriz iletişimi ve marka konumlandırma gibi alanlarda hizmet veririz.</p>
  </section>

  <section id="hizmetler">
    <h2>Hizmetlerimiz</h2>
    <div class="grid">
      <div class="card"><h3>PR ve Medya Yönetimi</h3><p>Basın stratejileri, influencer iş birlikleri ve medya görünürlüğü.</p></div>
      <div class="card"><h3>Kriz Yönetimi</h3><p>Şeffaf, hızlı ve stratejik iletişim çözümleriyle marka itibarını koruma.</p></div>
      <div class="card"><h3>Marka Stratejisi</h3><p>Markanızı öne çıkaran kimlik, ton ve görsel dil geliştirme.</p></div>
      <div class="card"><h3>Sosyal Medya Danışmanlığı</h3><p>Marka imajınızı güçlendiren özgün içerik ve kampanyalar.</p></div>
    </div>
  </section>

  <section id="projeler">
    <h2>Projelerimiz</h2>
    <div class="grid">
      <div class="card"><h3>Jaclyn Cosmetics Kriz Yönetimi</h3><p>#RujunuTazele kampanyası ile itibarın yeniden inşası sağlandı.</p></div>
      <div class="card"><h3>GlowUp Lansman Kampanyası</h3><p>Yeni kozmetik markalarına özel influencer tanıtım kampanyaları.</p></div>
      <div class="card"><h3>PureSkin Sosyal Medya Yönetimi</h3><p>Doğal içerikli ürünler için minimalist dijital iletişim dili oluşturuldu.</p></div>
    </div>
  </section>

  <section id="galeri">
    <h2>Galeri</h2>
    <div class="gallery">
      <img src="https://cdn.pixabay.com/photo/2017/03/27/14/56/woman-2179278_1280.jpg" alt="kozmetik 1">
      <img src="https://cdn.pixabay.com/photo/2016/11/29/03/53/adult-1869116_1280.jpg" alt="kozmetik 2">
      <img src="https://cdn.pixabay.com/photo/2016/06/29/09/38/makeup-1480117_1280.jpg" alt="kozmetik 3">
    </div>
  </section>

  <section id="iletisim">
    <h2>Bize Ulaşın</h2>
    <p>Bizimle iletişime geçmek için aşağıdaki formu doldurun. Ekip üyelerimiz en kısa sürede size dönüş yapacaktır.</p>

    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdoOCuRISnPGwQj_nqTiw2se4GbgCy9R1QfzZO-TjJ3GbrCyg/viewform?usp=publish-editor" allowfullscreen></iframe>

    <div class="socials">
      <a href="https://instagram.com" target="_blank">📸</a>
      <a href="https://linkedin.com" target="_blank">💼</a>
      <a href="https://x.com" target="_blank">🐦</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Echo PR | Kozmetik İletişim Ajansı</p>
  </footer>
</body>
</html>
