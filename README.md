<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tarjeta Cursiva Elegante</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      background: #fff0f8; /* un fondo suave para que resalte la tarjeta */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: 'Arial', sans-serif;
    }
    .tarjeta {
      background: linear-gradient(135deg, #ffd6e8, #ffc2f0);
      padding: 40px;
      border-radius: 25px;
      box-shadow: 0 10px 30px rgba(255,182,193,0.4);
      display: inline-block;
      text-align: center;
    }
    .cursiva {
      font-family: 'Great Vibes', cursive; /* fuente cursiva elegante */
      font-style: italic;
      font-size: 28px;
      color: #d63384;
      margin: 0;
    }
    table {
      margin: 0 auto;
    }
    td {
      padding: 20px;
      vertical-align: middle;
    }
    img.tarjeta-img {
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      max-width: 100%;
      height: auto;
    }
    a img {
      margin-top: 20px;
      border-radius: 15px;
    }
  </style>
</head>
<body>
  <div class="tarjeta">
    <table>
      <tr>
        <td>
          <p class="cursiva">Este texto también está en cursiva elegante.</p>
        </td>
        <td>
          <img src="oshi-no-ko-ai-hoshino.gif" class="tarjeta-img" alt="Oshi no Ko Hoshino">
        </td>
      </tr>
    </table>
    <a href="https://git.io/streak-stats">
      <img src="https://streak-stats.demolab.com?user=val12121&theme=sakura-x&ring=EB3FBC&fire=EB94CD&sideNums=FF77DAF0&currStreakLabel=FF5FDE&dates=FFFFFFF6&stroke=E3DDEB&border=FF10BE&sideLabels=D792EB" 
           alt="GitHub Streak" />
    </a>
  </div>
</body>
</html>
