<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INIZIO - Pewangi Kenderaan Anda</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #fef9ff, #e0f7fa);
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #00c6ff, #0072ff);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    header p {
      font-size: 1.3rem;
      font-weight: 300;
    }

    .section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
    }

    .price-box {
      background-color: #ffebee;
      color: #d32f2f;
      font-size: 1.8rem;
      text-align: center;
      padding: 20px;
      margin-bottom: 30px;
      border-radius: 12px;
      font-weight: bold;
      box-shadow: 0 8px 16px rgba(0,0,0,0.05);
    }

    .highlight {
      background: #e8f5e9;
      border-left: 8px solid #43a047;
      padding: 15px 25px;
      border-radius: 8px;
      font-size: 1.1rem;
      margin-bottom: 40px;
    }

    h2 {
      font-size: 1.8rem;
      color: #00796b;
      margin-bottom: 15px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 15px;
      margin-bottom: 30px;
    }

    .grid div {
      background: #ffffff;
      padding: 12px 18px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.07);
      text-align: center;
      font-weight: 500;
      transition: transform 0.2s ease;
    }

    .grid div:hover {
      transform: translateY(-4px);
      background: #f1f8ff;
    }

    .cta {
      text-align: center;
      margin: 50px 0;
    }

    .cta button {
      background-color: #ff4081;
      color: white;
      padding: 16px 30px;
      font-size: 1.2rem;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background 0.3s ease;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .cta button:hover {
      background-color: #f50057;
    }

    footer {
      background-color: #212121;
      color: #bbb;
      padding: 30px 20px;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>INIZIO</h1>
    <p>Pewangi Kenderaan & Ruangan Anda – Harum, Segar & Memikat!</p>
  </header>

  <div class="section">

    <div class="price-box">
      💰 HANYA RM2.50! 💰
    </div>

    <div class="highlight">
      Wangian tahan lama selama <strong>7 hingga 14 hari</strong> bergantung kepada penggunaan.  
      Saiz kompak – mudah digantung atau diletakkan di mana-mana!
    </div>

    <h2>🌸 17 Pilihan Bauan Menggoda</h2>
    <div class="grid">
      <div>Bubble Gum</div>
      <div>Honeydew</div>
      <div>Strawberry</div>
      <div>Tutty Fruity</div>
      <div>Rose</div>
      <div>Lemon</div>
      <div>Apple Blossom</div>
      <div>Mango</div>
      <div>Lavender</div>
      <div>Pandan</div>
      <div>Nenas</div>
      <div>Vanilla</div>
      <div>Love Spell</div>
      <div>Sakura</div>
      <div>Coffee</div>
      <div>Aqua</div>
      <div>New Car</div>
    </div>

    <h2>🚗 Sesuai Untuk:</h2>
    <div class="grid">
      <div>Kenderaan</div>
      <div>Bilik Tidur</div>
      <div>Pejabat</div>
      <div>Almari Pakaian</div>
      <div>Tandas</div>
    </div>

    <div class="cta">
      <p style="font-size: 1.2rem; margin-bottom: 20px;">Klik di bawah untuk buat tempahan sekarang:</p>
      <button onclick="orderNow()">Tempah Melalui WhatsApp</button>
    </div>

  </div>

  <footer>
    © 2025 INIZIO • Wangian Premium pada Harga Mampu Milik.
  </footer>

  <script>
    function orderNow() {
      window.open("https://wa.me/60189579103?text=(JAIbapak) Hi!%20Saya%20berminat%20dengan%20pewangi%20INIZIO.%20Boleh%20saya%20dapatkan%20bauan%20dan%20tempahan?", "_blank");
    }
  </script>

</body>
</html>
