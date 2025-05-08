<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>🎵 Morat - A Dónde Vamos</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #121212;
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .player-container {
      background: #1db954;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
      text-align: center;
      width: 90%;
      max-width: 400px;
    }

    h2 {
      margin-top: 0;
      font-size: 1.2rem;
      color: #fff;
    }

    audio {
      width: 100%;
      margin-top: 10px;
      outline: none;
    }

    .footer {
      margin-top: 15px;
      font-size: 0.8rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <div class="player-container">
    <h2>🎶 Morat – A Dónde Vamos</h2>
    <audio controls autoplay loop>
      <source src="https://tonyymedina6.github.io/music/Morat%20-%20A%20D%C3%B3nde%20Vamos%20(Video%20Oficial).mp3" type="audio/mpeg">
      Tu navegador no soporta audio.
    </audio>
    <div class="footer">TonyRadio™</div>
  </div>
</body>
</html>
