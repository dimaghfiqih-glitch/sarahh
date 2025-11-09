[Uploading Perfect x Line Without a Hook ( JepzzLyrics) viral tiktok - Jepzz Lyrics.mp3…]()
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Woi Sarah 💘</title>
  <style>
    body {
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      font-family: "Comic Sans MS", cursive;
      text-align: center;
      overflow: hidden;
      height: 100vh;
      color: #333;
    }

    h1 {
      margin-top: 60px;
      color: #ff2e63;
      font-size: 2.5em;
      animation: bounce 1.5s infinite alternate;
    }

    p {
      font-size: 18px;
      color: #444;
    }

    button {
      margin-top: 20px;
      padding: 12px 25px;
      font-size: 16px;
      border: none;
      background-color: #ff2e63;
      color: white;
      border-radius: 20px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: #ff6685;
      transform: scale(1.1);
    }

    .heart {
      position: absolute;
      color: red;
      font-size: 20px;
      animation: floatUp 5s linear infinite;
    }

    @keyframes floatUp {
      0% {transform: translateY(0) scale(1); opacity: 1;}
      100% {transform: translateY(-600px) scale(1.5); opacity: 0;}
    }

    @keyframes bounce {
      from {transform: translateY(0);}
      to {transform: translateY(-10px);}
    }

    footer {
      position: absolute;
      bottom: 15px;
      width: 100%;
      font-size: 14px;
      color: #fff;
      text-shadow: 1px 1px 2px #ff2e63;
    }

    /* Pop-up gaya rahasia */
    .popup {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background-color: white;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(255, 0, 102, 0.4);
      padding: 30px;
      width: 300px;
      text-align: center;
      animation: fadeIn 0.5s ease-in-out;
      z-index: 10;
    }

    .popup h2 {
      color: #ff2e63;
    }

    .popup button {
      background-color: #ff2e63;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 10px;
      margin-top: 15px;
      cursor: pointer;
      transition: 0.3s;
    }

    .popup button:hover {
      background-color: #ff6685;
      transform: scale(1.1);
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>
  <h1>WOI SARAH 😆</h1>
  <p>Kalau HTML aja bisa bikin tampilan secantik ini,<br>
  berarti gue juga bisa bikin lu senyum dong 😜</p>

  <button onclick="showSecret()">Klik kalau lu senyum 😁</button>

  <footer>dibuat oleh: Dimagh si tampan 💕 | dengan 100% CSS cinta</footer>

  <!-- Pop-up rahasia -->
  <div id="secretPopup" class="popup">
    <h2>Pesan Rahasia 💌</h2>
    <p>SEMANGAT KERJAIN MENTARINYA<br>
    jangan lupa fotbar sabtu 😍</p>
    <button onclick="closeSecret()">Tutup 😅</button>
  </div>

  <script>
    // Efek hati beterbangan 💖
    function createHeart() {
      const heart = document.createElement("div");
      heart.classList.add("heart");
      heart.innerHTML = "❤️";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
      document.body.appendChild(heart);

      setTimeout(() => heart.remove(), 5000);
    }
    setInterval(createHeart, 300);

    // Pop-up rahasia 😳
    function showSecret() {
      document.getElementById("secretPopup").style.display = "block";
    }
    function closeSecret() {
      document.getElementById("secretPopup").style.display = "none";
    }
  </script>

  
    <audio id="music" controls autoplayloop>
    <source src="Perfect x Line Without a Hook ( JepzzLyrics) viral tiktok - Jepzz Lyrics.mp3" type="audio/mpeg">
    Browser kamu gak support audio, Sarah 😢
  </audio>

</body>
</html>
