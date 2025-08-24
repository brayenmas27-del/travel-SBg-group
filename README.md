<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Judul web (muncul di tab browser & Google) -->
  <title>Travel Indramayu - Subang - Jabodetabek | Sbg Santri Babadan Group</title>

  <!-- Deskripsi singkat (muncul di Google Search) -->
  <meta name="description" content="Layanan travel door to door dari Indramayu - Subang - Karawang - Jabodetabek. Bisa antar jemput bandara & wisata. Hubungi via WhatsApp untuk info & pemesanan.">

  <!-- Kata kunci biar mudah dicari -->
  <meta name="keywords" content="travel indramayu, travel subang, travel karawang, travel jabodetabek, door to door travel, sbg santri babadan group">

  <!-- CSS kamu tetap di sini -->
  <style>
    /* CSS yang kemarin */
  </style>
</head>
<body>
  <!-- isi website -->
</body>
</html>
  <head>
  <style>
    /* Background fade-in */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: url('IMG-20250823-WA0005.jpg') no-repeat center center/cover;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* Hero text animation */
    .hero-content h1 {
      font-size: 2.5em;
      color: #fff;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.6);
      animation: slideDown 1.5s ease;
    }

    @keyframes slideDown {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    .hero-content p {
      color: #f8f8f8;
      animation: fadeInText 2s ease;
    }

    @keyframes fadeInText {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* WhatsApp Button Animation */
    .cta-button {
      display: inline-block;
      padding: 12px 24px;
      margin-top: 20px;
      background: #25D366;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.3s;
      animation: bounceIn 2s ease;
    }

    .cta-button:hover {
      background: #1ebe5a;
      transform: scale(1.05);
    }

    @keyframes bounceIn {
      0% { transform: scale(0.8); opacity: 0; }
      50% { transform: scale(1.05); opacity: 1; }
      100% { transform: scale(1); }
    }
  </style>
</head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SBG Transport</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f7f9fc;
      color: #333;
    }
    header {
      background: #0d47a1;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    header p {
      margin: 5px 0 0;
      font-size: 14px;
    }
    .hero {
      background: url('IMG-20250823-WA0005.jpg') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h2 {
      font-size: 32px;
      margin-bottom: 10px;
      text-shadow: 1px 1px 3px black;
    }
    .hero p {
      font-size: 18px;
      margin-bottom: 20px;
      text-shadow: 1px 1px 3px black;
    }
    .cta-button {
      background: #ff9800;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 30px;
      transition: 0.3s;
    }
    .cta-button:hover { background: #e68900; }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #white;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .service {
      flex: 1 1 200px;
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .service h3 { margin-top: 10px; color: #ff9800; }
    .cars {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .car {
      flex: 1 1 250px;
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
      text-align: center;
    }
    .car img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .car h4 { margin: 10px 0; }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 15px;
    }
    table, th, td {
      border: 1px solid #ddd;
      padding: 10px;
    }
    th { background: #0d47a1; color: white; }
    .form-container {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    }
    .form-container input, .form-container textarea {
      width: 100%;
      margin: 8px 0;
      padding: 12px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    .form-container button {
      background: #0d47a1;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      font-size: 16px;
      cursor: pointer;
    }
    .form-container button:hover { background: #08306b; }
    footer {
      background: #0d47a1;
      color: white;
      padding: 20px;
      text-align: center;
      margin-top: 40px;
    }
    /* Floating WhatsApp */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 28px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.3);
      text-decoration: none;
    }
  </style>
</head>
<body>

<header>
  <h1>SBG Transport</h1>
  <p>Santri Babadan Group • Layanan Transportasi Door to Door</p>
</header>

<section class="hero">
  <h2>Selamat Datang di SBG Transport</h2>
  <p>Rute: Indramayu – Subang – Karawang – Jabodetabek & sebaliknya</p>
  <a href="https://wa.me/6283850259833" class="cta-button">Pesan Sekarang via WhatsApp</a>
</section>

<section>
  <h2>Sejarah Kami</h2>
  <p>SBG Transport berdiri dari komunitas santri Babadan, berawal dari usaha kecil untuk membantu mobilitas warga. Kini berkembang menjadi layanan transportasi profesional dengan rute Indramayu, Subang, Karawang hingga Jabodetabek. Fokus kami adalah memberikan layanan door to door yang aman, nyaman, dan tepat waktu.</p>
</section>

<section>
  <h2>Layanan Kami</h2>
  <div class="services">
    <div class="service"><h3>🚖 Door to Door</h3><p>Antar jemput langsung dari rumah ke tujuan.</p></div>
    <div class="service"><h3>✈️ Bandara</h3><p>Antar jemput Soekarno Hatta & Halim.</p></div>
    <div class="service"><h3>🚉 Stasiun</h3><p>Penjemputan Stasiun Gambir, Bekasi, dll.</p></div>
    <div class="service"><h3>🏖 Wisata</h3><p>Transportasi ke destinasi wisata favorit.</p></div>
    <div class="service"><h3>🏢 Acara & Perusahaan</h3><p>Solusi transportasi event & corporate.</p></div>
    <div class="service"><h3>📦 antar Paket & document 24 jam </h3><p>Solusi antar paket cepat.</p></div>
  </div>
</section>

<section>
  <h2>Pilihan Mobil</h2>
  <div class="cars">
    <div class="car"><img src="IMG-20250823-WA0005.jpg" alt="Mobil 1"><h4>cayla /sigra </h4></div>
    <div class="car"><img src="file_00000000f4dc623084a3d6e203229bdb.png" alt="Mobil 1"><h4>Avanza / Xenia</h4></div>
    <div class="car"><img src="file_00000000a8906230adce466bd37a89e0.png" alt="Mobil 2"><h4>Innova</h4></div>
    <div class="car"><img src="hiace.png" alt="Mobil 3"><h4>Hiace / Elf</h4></div>
  </div>
</section>

<section>
  <h2>Rute Utama</h2>
  <table>
    <tr><th>Dari</th><th>Ke</th></tr>
    <tr><td>Indramayu</td><td>Subang</td></tr>
    <tr><td>Subang</td><td>Karawang</td></tr>
    <tr><td>Karawang</td><td>Jabodetabek</td></tr>
    <tr><td>Jabodetabek</td><td>Indramayu</td></tr>
  </table>
</section>

<section>
  <h2>Formulir Pemesanan</h2>
  <div class="form-container">
    <form action="https://wa.me/6283850259833" method="get" target="_blank">
      <input type="text" name="nama" placeholder="Nama Lengkap" required>
      <input type="text" name="penjemputan" placeholder="Lokasi Penjemputan" required>
      <input type="text" name="tujuan" placeholder="Tujuan Perjalanan" required>
      <textarea name="catatan" placeholder="Catatan (opsional)"></textarea>
      <button type="submit">Kirim ke WhatsApp</button>
    </form>
  </div>
</section>

<footer>
  <p>Kontak: 083850259833 | 
      Email: massbrayen@gmail.com</p>
  <p>&copy; 2025 SBG Transport. Semua Hak Dilindungi.</p>
</footer>

<a href="https://wa.me/6283850259833" class="whatsapp-float">💬</a>

</body>
</html>
