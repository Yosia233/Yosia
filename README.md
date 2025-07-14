<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy 19th Birthday, Bubub!</title>
  <style>
    body {
      margin: 0; padding: 0;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      color: #333;
      text-align: center;
      overflow-x: hidden;
    }
    .container { padding: 60px 20px; }
    h1 { font-size: 2.8em; margin-bottom: 5px; }
    h2 { font-size: 2.2em; margin-top: 0; }
    p { font-size: 1.2em; max-width: 700px; margin: 20px auto; line-height: 1.5; }
    .gallery { margin: 30px 0; }
    .gallery img {
      width: 180px; border-radius: 10px; margin: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .gallery img:hover { transform: scale(1.05); }
    .surprise-btn {
      display: none; margin-top: 30px;
      padding: 15px 30px;
      background-color: #fff; color: #ff9a9e;
      border: none; border-radius: 25px;
      font-size: 1.1em;
      cursor: pointer;
    }
    .footer { margin-top: 50px; font-size: 0.9em; opacity: 0.7; }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-sweet.mp3" type="audio/mp3">
  </audio>

  <div class="container">
    <h1>🎂 Happy 19th Birthday!</h1>
    <h2>Bubub tercinta 💖</h2>
    <p>
      Selamat ulang tahun yang ke‑19, sayangku!  
      Semoga setiap hari di tahun baru usiamu ini dipenuhi tawa, kebahagiaan, dan impian yang terwujud.  
      Terima kasih sudah menjadi cahaya di hidupku—aku mencintaimu lebih dari kata mampu ungkapkan.
    </p>

    <div class="gallery">
      <img src="https://i.ibb.co/zrSbM4X/photo1.jpg" alt="Foto Bubub 1">
      <img src="https://i.ibb.co/9Yc4fsH/photo2.jpg" alt="Foto Bubub 2">
      <img src="https://i.ibb.co/JKtq5v3/photo3.jpg" alt="Foto Bubub 3">
    </div>

    <button class="surprise-btn" onclick="window.location.href='https://wa.me/?text=Selamat+ulang+tahunnya+Bubub%21+🎁'">
      🎁 Klik di sini untuk hadiah spesial!
    </button>

    <div class="footer">Dari pasanganmu yang selalu sayang, 💌</div>
  </div>

  <script>
    setTimeout(() => {
      document.querySelector('.surprise-btn').style.display = 'inline-block';
    }, 5000);
  </script>
</body>
</html>
