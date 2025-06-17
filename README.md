# Zainab-gull
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>For Zainab Akka 💌</title>
  <style>
    body { display:flex; justify-content:center; align-items:center;
           height:100vh; background:#f0e6f6; margin:0; }
    .card-container { perspective:1000px; }
    .card {
      width:300px; height:400px;
      transform-style:preserve-3d;
      transition: transform 0.8s;
      cursor: pointer;
      position: relative;
    }
    .card.flipped { transform: rotateY(180deg); }
    .side {
      position:absolute; width:100%; height:100%;
      backface-visibility:hidden;
      border:2px solid #ddd; border-radius:10px;
      box-shadow:0 4px 8px rgba(0,0,0,0.1);
      display:flex; flex-direction:column;
      justify-content:center; align-items:center;
      font-family:'Segoe UI', Tahoma, sans-serif;
      padding:20px; box-sizing:border-box;
    }
    .front {
      background: linear-gradient(135deg, #ffd5cd, #e0c3fc);
      color:#4a3c62; font-size:1.3em;
    }
    .front .decor { position:absolute; top:10px; right:10px; font-size:1.5em; }
    .back {
      background:#fff;
      transform: rotateY(180deg);
      color:#333; font-size:1.1em;
      text-align:center;
    }
    .pun { font-style:italic; margin-bottom:10px; }
    .bold { font-weight:bold; margin:15px 0; color:#5a2a83; }
    .signature { margin-top:auto; font-size:0.9em; color:#555; }
  </style>
</head>
<body>
  <div class="card-container">
    <div class="card" onclick="this.classList.toggle('flipped')">
      <div class="side front">
        <div class="decor">💖✨</div>
        <div>To Zainab akka,</div>
        <div>with love &amp; duas</div>
      </div>
      <div class="side back">
        <div class="pun">“You pea‑lieve in yourself? 🌱”</div>
        <div class="bold">Aap se ho jayega</div>
        <div class="bold">YOU GOT THIS</div>
        <div class="signature">No distance can separate us.<br>Yours, Zozo</div>
      </div>
    </div>
  </div>
</body>
</html>
