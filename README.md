<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Website Romantis untuk Pasangan</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f7f7f7;
        margin: 0;
        padding: 0;
      }
      header {
        background-color: #ff69b4;
        color: #fff;
        text-align: center;
        padding: 20px 0;
        position: relative;
      }
      h1 {
        margin-top: 0;
      }
      .container {
        max-width: 800px;
        margin: 20px auto;
        padding: 0 20px;
      }
      section {
        background-color: #fff;
        padding: 20px;
        margin-bottom: 20px;
        border-radius: 8px;
        position: relative;
      }
      footer {
        background-color: rgba(51, 51, 51, 0.8);
        color: #fff;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        bottom: 0;
        width: 100%;
        z-index: 100;
      }
      .card {
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 10px;
        transition: transform 0.3s ease;
      }
      .card:hover {
        transform: scale(1.05);
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
      }
      .photo {
        transition: transform 0.3s ease;
      }
      .photo:hover {
        transform: scale(1.05);
      }
      @keyframes heartBeat {
        0% {
          transform: scale(1);
        }
        50% {
          transform: scale(1.1);
        }
        100% {
          transform: scale(1);
        }
      }
      .heart {
        display: inline-block;
        animation: heartBeat 1s infinite;
        color: #ff69b4;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>
        <span class="heart">&hearts;</span> Selamat Datang di Website Romantis
        <span class="heart">&hearts;</span>
      </h1>
      <p>Tempat untuk Membuat Kenangan Bersama</p>
    </header>

    <div class="container">
      <section>
        <h2>Kumpulan Foto dan Kenangan Bersama</h2>
        <p>
          Bagikan foto-foto indah dan kenangan spesial dengan pasanganmu di
          sini.
        </p>
        <!-- Tambahkan formulir untuk mengunggah foto-foto -->
        <!-- Gunakan JavaScript untuk menampilkan foto-foto yang diunggah -->
      </section>

      <section>
        <h2>Kartu Ucapan Romantis</h2>
        <p>Pilih kartu ucapan romantis dan bagikan kepada pasanganmu.</p>
        <!-- Tambahkan daftar kartu ucapan -->
        <div class="card">Kartu Ucapan 1</div>
        <div class="card">Kartu Ucapan 2</div>
        <div class="card">Kartu Ucapan 3</div>
      </section>

      <!-- Tambahkan bagian lainnya seperti playlist musik, kuis kecocokan, dll. -->
    </div>

    <footer>
      <p>&copy; 2024 Website Romantis</p>
    </footer>
  </body>
</html>
