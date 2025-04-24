<!DOCTYPE html><html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Florélle</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #fffaf5;
      color: #3e3e3e;
    }
    header {
      background: linear-gradient(to right, #f3e6e3, #fef1e7);
      padding: 2rem;
      text-align: center;
      border-bottom: 2px solid #e5c2b3;
    }
    header h1 {
      font-size: 2.5rem;
      color: #a66b5a;
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 1rem;
    }
    nav a {
      text-decoration: none;
      color: #a66b5a;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .gallery img, .products img {
      width: 200px;
      height: auto;
      border-radius: 12px;
      margin: 1rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #f3e6e3;
      border-top: 1px solid #e5c2b3;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Florélle</h1>
    <nav>
      <a href="#hakkimizda">Hakkımızda</a>
      <a href="#urunler">Ürünler</a>
      <a href="#galeri">Galeri</a>
      <a href="#siparis">Sipariş</a>
      <a href="#iletisim">İletişim</a>
    </nav>
  </header>  <section id="hakkimizda">
    <h2>Hakkımızda</h2>
    <p>Florélle, lüks çiçek tasarımlarını zarif çantalarla buluşturarak özel anlarınızı unutulmaz kılar. Her aranjman, estetik ve duygu yüklü bir deneyim sunar.</p>
  </section>  <section id="urunler" class="products">
    <h2>Ürünler</h2>
    <p>En beğenilen çantalı çiçek tasarımlarımız burada!</p>
    <!-- Örnek ürün görselleri eklenecek -->
    <img src="https://via.placeholder.com/200x250?text=Ürün+1" alt="Ürün 1">
    <img src="https://via.placeholder.com/200x250?text=Ürün+2" alt="Ürün 2">
  </section>  <section id="galeri" class="gallery">
    <h2>Galeri</h2>
    <p>Florélle anlarından ilham alın.</p>
    <img src="https://via.placeholder.com/200x250?text=Galeri+1" alt="Galeri 1">
    <img src="https://via.placeholder.com/200x250?text=Galeri+2" alt="Galeri 2">
  </section>  <section id="siparis">
    <h2>Sipariş</h2>
    <p>WhatsApp ya da e-posta ile sipariş vermek için bizimle iletişime geçin.</p>
  </section>  <section id="iletisim">
    <h2>İletişim</h2>
    <p>E-posta: <a href="mailto:florelle@example.com">florelle@example.com</a></p>
  </section>  <footer>
    <p>&copy; 2025 Florélle. Tüm hakları saklıdır.</p>
  </footer>
</body>
</html>
