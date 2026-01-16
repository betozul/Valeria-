<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Invitación Frozen</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(180deg, #a7d8ff, #ffffff);
      color: #03396c;
      overflow-x: hidden;
    }

    .container {
      max-width: 420px;
      margin: auto;
      text-align: center;
      padding: 20px;
      animation: fadeIn 1.5s ease;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 48px;
      margin-bottom: 10px;
      animation: slideDown 1.2s ease;
    }

    h2 {
      font-size: 22px;
      margin: 10px 0;
    }

    .snow {
      position: fixed;
      top: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      background-image: radial-gradient(#fff 1px, transparent 1px);
      background-size: 20px 20px;
      animation: snow 10s linear infinite;
      opacity: 0.4;
    }

    .card {
      background: rgba(255,255,255,0.9);
      border-radius: 20px;
      padding: 25px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);
      animation: fadeUp 1.5s ease;
    }

    .name {
      font-size: 32px;
      font-weight: 700;
      color: #005b96;
    }

    .info {
      font-size: 16px;
      margin: 10px 0;
    }

    .buttons a {
      display: block;
      margin: 12px 0;
      padding: 14px;
      border-radius: 30px;
      text-decoration: none;
      color: white;
      font-weight: 600;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .btn-confirm {
      background: linear-gradient(90deg, #00b4d8, #0077b6);
    }

    .btn-map {
      background: linear-gradient(90deg, #90dbf4, #48cae4);
    }

    .buttons a:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }

    footer {
      font-size: 12px;
      margin-top: 20px;
      color: #555;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideDown {
      from { transform: translateY(-40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeUp {
      from { transform: translateY(40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes snow {
      from { background-position: 0 0; }
      to { background-position: 0 100vh; }
    }
  </style>
</head>
<body>

<div class="snow"></div>

<div class="container">
  <h1>¡Estás invitado!</h1>

  <div class="card">
    <h2>Celebramos los</h2>
    <div class="name">3 años de Valeria</div>

    <p class="info">❄️ Una aventura congelada ❄️</p>

    <p class="info">📅 <strong>31 de enero</strong></p>
    <p class="info">📍 Calle los Lagos #9<br>Pinoltepec, Veracruz</p>

    <div class="buttons">
      <a class="btn-confirm" href="https://wa.me/522284825861?text=Hola,%20confirmo%20mi%20asistencia%20a%20la%20fiesta%20de%20Valeria%20❄️🎉" target="_blank">
        ✅ Confirmar asistencia
      </a>

      <a class="btn-map" href="https://maps.app.goo.gl/u8yeBMkGuKxLDeCW8?g_st=ic" target="_blank">
        📍 Ver ubicación en Google Maps
      </a>
    </div>
  </div>

  <footer>
    ¡Acompáñanos a celebrar con magia y diversión! ❄️✨
  </footer>
</div>

</body>
</html>
