# Solo-un-universo-para-ti-
Para esme❤️‍🩹
index.html<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Galaxia de Amor — Luna Miracle</title>  <style>
    /* ================= RESET ================= */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    /* ================= BASE ================= */
    body {
      font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
      background: radial-gradient(circle at top, #2b0052, #070015, #000);
      color: #ffffff;
      overflow-x: hidden;
      line-height: 1.6;
    }

    /* ================= AURORA ================= */
    .aurora {
      position: fixed;
      inset: -20% -20% auto -20%;
      height: 70vh;
      z-index: -3;
      filter: blur(40px);
      background: linear-gradient(120deg,
        rgba(120,255,210,.25),
        rgba(170,130,255,.25),
        rgba(255,180,220,.25));
      animation: auroraMove 20s ease-in-out infinite alternate;
    }
    @keyframes auroraMove {
      from { transform: translateX(-12%) rotate(0deg); }
      to   { transform: translateX(12%) rotate(2deg); }
    }

    /* ================= STARS ================= */
    .stars {
      position: fixed;
      inset: 0;
      z-index: -2;
      background-image: radial-gradient(#ffffff 1px, transparent 1px);
      background-size: 60px 60px;
      opacity: .35;
      animation: starsMove 160s linear infinite, starsTwinkle 8s ease-in-out infinite;
    }
    @keyframes starsMove {
      from { background-position: 0 0; }
      to   { background-position: -800px 800px; }
    }
    @keyframes starsTwinkle {
      0%,100% { opacity: .30; }
      50%     { opacity: .50; }
    }

    /* ================= CATS ================= */
    .cats { position: fixed; inset: 0; pointer-events: none; z-index: -1; }
    .cat {
      position: absolute;
      font-size: 22px;
      opacity: .6;
      animation: floatCat 26s linear infinite;
    }
    .cat.white { color: #fff; text-shadow: 0 0 10px rgba(255,255,255,.6); }
    .cat.black { color: #111; text-shadow: 0 0 10px rgba(0,0,0,.9); }
    @keyframes floatCat {
      from { transform: translateY(110vh) translateX(0); }
      to   { transform: translateY(-15vh) translateX(40px); }
    }

    /* ================= FADE ================= */
    header, section, footer { animation: fadeUp 1.6s ease both; }
    section { animation-delay: .3s; }
    footer  { animation-delay: .6s; }
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(18px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    /* ================= HEADER ================= */
    header {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 24px;
    }

    .galaxy-center {
      position: relative;
      width: 260px;
      height: 260px;
      margin-bottom: 32px;
    }

    .sun, .moon {
      position: absolute;
      border-radius: 50%;
    }

    .sun {
      width: 140px;
      height: 140px;
      top: 70px;
      left: 0;
      background: radial-gradient(circle, #ffd700, #ff8c00);
      box-shadow: 0 0 50px rgba(255,200,80,.9);
    }

    .moon {
      width: 150px;
      height: 150px;
      top: 40px;
      left: 90px;
      background: radial-gradient(circle, #ffffff, #cfcfd6);
      box-shadow: 0 0 45px rgba(255,255,255,.9);
      mix-blend-mode: screen;
      animation: breathe 7s ease-in-out infinite;
    }
    @keyframes breathe {
      0%,100% { transform: scale(1); }
      50%     { transform: scale(1.04); }
    }

    h1 {
      font-size: clamp(2.2rem, 5vw, 2.8rem);
      margin-bottom: 8px;
      background: linear-gradient(90deg, #ffb6d5, #caa7ff, #ffe28a);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    header p {
      opacity: .9;
      max-width: 520px;
    }

    /* ================= BUTTON ================= */
    button {
      margin-top: 24px;
      padding: 14px 26px;
      border-radius: 30px;
      border: none;
      font-size: 1rem;
      cursor: pointer;
      background: linear-gradient(90deg, #ff9ad5, #b48cff, #ffd36a);
      color: #1a002b;
      box-shadow: 0 0 18px rgba(255,215,0,.4);
      transition: transform .2s ease, box-shadow .2s ease;
    }
    button:hover { transform: scale(1.04); box-shadow: 0 0 26px rgba(255,215,0,.6); }

    /* ================= SECTIONS ================= */
    section {
      padding: 90px 20px;
      text-align: center;
    }

    .card {
      background: rgba(255,255,255,.05);
      border-radius: 22px;
      padding: 32px;
      margin: 26px auto;
      max-width: 620px;
      backdrop-filter: blur(12px);
      box-shadow: 0 0 28px rgba(255,120,200,.25);
    }

    .card h2 {
      color: #ffb6d5;
      margin-bottom: 14px;
    }

    .card p {
      text-align: left;
      line-height: 1.85;
    }

    .icons { font-size: 1.6rem; margin-top: 12px; }

    /* ================= FOOTER ================= */
    footer {
      padding: 60px 20px;
      text-align: center;
      font-size: .9rem;
      color: #ccc;
      opacity: .85;
    }
  </style></head>
<body>  <div class="aurora"></div>
  <div class="stars"></div>  <div class="cats">
    <!-- 24 gatitos a la izquierda (12 blancos, 12 negros) -->
    <div class="cat white" style="left:2%;animation-delay:0s">🐱</div>
    <div class="cat black" style="left:4%;animation-delay:2s">🐱</div>
    <div class="cat white" style="left:6%;animation-delay:4s">🐱</div>
    <div class="cat black" style="left:8%;animation-delay:6s">🐱</div>
    <div class="cat white" style="left:10%;animation-delay:8s">🐱</div>
    <div class="cat black" style="left:12%;animation-delay:10s">🐱</div>
    <div class="cat white" style="left:14%;animation-delay:12s">🐱</div>
    <div class="cat black" style="left:16%;animation-delay:14s">🐱</div>
    <div class="cat white" style="left:18%;animation-delay:16s">🐱</div>
    <div class="cat black" style="left:20%;animation-delay:18s">🐱</div>
    <div class="cat white" style="left:22%;animation-delay:20s">🐱</div>
    <div class="cat black" style="left:24%;animation-delay:22s">🐱</div><div class="cat white" style="left:3%;animation-delay:24s">🐱</div>
<div class="cat black" style="left:5%;animation-delay:26s">🐱</div>
<div class="cat white" style="left:7%;animation-delay:28s">🐱</div>
<div class="cat black" style="left:9%;animation-delay:30s">🐱</div>
<div class="cat white" style="left:11%;animation-delay:32s">🐱</div>
<div class="cat black" style="left:13%;animation-delay:34s">🐱</div>
<div class="cat white" style="left:15%;animation-delay:36s">🐱</div>
<div class="cat black" style="left:17%;animation-delay:38s">🐱</div>
<div class="cat white" style="left:19%;animation-delay:40s">🐱</div>
<div class="cat black" style="left:21%;animation-delay:42s">🐱</div>
<div class="cat white" style="left:23%;animation-delay:44s">🐱</div>
<div class="cat black" style="left:25%;animation-delay:46s">🐱</div>

  </div>
    <div class="cat black" style="left:70%; animation-delay:9s">🐱</div>
  </div><canvas id="galaxyCanvas"></canvas>

  <header>
    <div class="galaxy-center">
      <div class="sun"></div>
      <div class="moon"></div>
    </div><h1>Luna Miracle 🌙</h1>
<p>Mi amor, mi princesita, mi llorona, mi enojoncita 💖</p>

<button id="musicBtn">▶️ Escuchar música</button>

  </header>  <section>
    <div class="card">
      <h2>En este universo frío y hermoso, y en mi mundo, tú eres todo lo que quiero decirte y el amor que quiero que seas ✨</h2>
    </div><div class="card">
  <h2>💌 Carta para mi Luna Miracle</h2>
  <p>
    A veces intento imaginar mi vida sin haberte cruzado, pero mi mente se queda en gris; simplemente no puedo.
    Desde que llegaste, el mundo se ve distinto.
    <br><br>
    No son solo los grandes momentos, sino el refugio que encuentro en tu voz cuando todo es caos o la paz que me da saber que estás ahí.
    Quizás nunca termine de explicarte cuánto significas para mí, pero mi plan es demostrártelo cada día: con palabras,
    con silencios, estando cerca o dándote tu espacio.
    <br><br>
    Gracias por ser tú, incluso por esas partes de ti que aún no sabes que me hacen tan feliz.
    A veces las palabras se me quedan cortas para explicar lo que me haces sentir.
    Lo que vivimos va mucho más allá de lo que puedo escribir en un mensaje.
    <br><br>
    Pero si de algo estoy seguro, es de esto: tu presencia calma mis miedos, tu risa me devuelve la paz y tu amor me hace creer en todo de nuevo.
    Te elijo hoy y te elegiría siempre, sin dudas y sin medidas.
    Si alguna vez olvidas lo increíble que eres, solo vuelve a mí; yo me encargaré de recordártelo el resto de mi vida.
    <br><br>
    Te amo, princesa hermosa.
    Te amaré solo a ti.
  </p>
</div>

<div class="card">
  <h2>🌷 Tulipanes & 🐱 Gatitos</h2>
  <p>Porque sé que amas lo tierno, lo suave y lo real.</p>
  <div class="icons">🌷🌷🐱🐱</div>
</div>

  </section>  <footer>
    Para mi luna Miracle 🌙 — en este universo frío y hermoso ✨<br>
    <small>Todo este universo es para <strong>Esmeralda</strong> 🌙<br>Hecho con amor por <strong>SSJ</strong>.</small>
    <audio id="bgm" loop preload="auto"></audio>
  </footer>  <script>
    const canvas = document.getElementById('galaxyCanvas');
    const ctx = canvas.getContext('2d');

    function resize() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    }
    window.addEventListener('resize', resize);
    resize();

    let t = 0;

    function drawHeart(x, y, size, color) {
      ctx.save();
      ctx.translate(x, y);
      ctx.scale(size, size);
      ctx.beginPath();
      ctx.moveTo(0, -0.3);
      ctx.bezierCurveTo(-0.5, -0.8, -1.2, -0.1, 0, 0.8);
      ctx.bezierCurveTo(1.2, -0.1, 0.5, -0.8, 0, -0.3);
      ctx.closePath();
      ctx.fillStyle = color;
      ctx.shadowColor = color;
      ctx.shadowBlur = 15;
      ctx.fill();
      ctx.restore();
    }

    function animate() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);

      const cx = canvas.width / 2;
      const cy = canvas.height / 2;
      const radius = Math.min(canvas.width, canvas.height) * 0.18;
      const hearts = 24;

      for (let i = 0; i < hearts; i++) {
        const angle = (i / hearts) * Math.PI * 2 + t;
        const x = cx + Math.cos(angle) * radius;
        const y = cy + Math.sin(angle) * radius;
        drawHeart(x, y, 10, 'rgba(255,105,180,0.9)');
      }

      t += 0.003;
      requestAnimationFrame(animate);
    }

    animate();
  </script></body>
</html>
