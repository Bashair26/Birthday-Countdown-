<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Ramiyah Birthday Countdown</title>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    height: 100vh;
    background: linear-gradient(135deg, #c471ed, #f64f59);
    font-family: 'Segoe UI', sans-serif;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    text-align: center;
    color: #fff;
    z-index: 2;
  }

  h1 {
    font-size: 3rem;
    margin-bottom: 10px;
  }

  .love {
    color: #ff1e56;
    text-shadow: 0 0 10px #ff1e56, 0 0 20px #ff4d6d;
    animation: pulse 1.5s infinite;
  }

  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.08); }
    100% { transform: scale(1); }
  }

  p {
    font-size: 1.3rem;
    margin-bottom: 25px;
    opacity: 0.9;
  }

  #countdown {
    font-size: 2.2rem;
    letter-spacing: 2px;
  }

  /* 💖 Floating Hearts */
  .heart {
    position: absolute;
    bottom: -20px;
    font-size: 20px;
    color: rgba(255,255,255,0.6);
    animation: floatUp linear infinite;
  }

  @keyframes floatUp {
    0% {
      transform: translateY(0) scale(1);
      opacity: 1;
    }
    100% {
      transform: translateY(-110vh) scale(1.5);
      opacity: 0;
    }
  }

  canvas {
    position: fixed;
    top: 0;
    left: 0;
    pointer-events: none;
  }
</style>
</head>

<body>

<div class="container">
  <h1 id="title">🎂 Ramiyah’s Birthday Countdown 🎂</h1>
  <p id="subtitle">✨ Get ready for the surprise… ✨</p>
  <div id="countdown"></div>
</div>

<canvas id="confetti"></canvas>

<script>
  /* 🎯 TARGET DATE */
  const targetDate = new Date("January 15, 2026 00:00:00").getTime();

  const countdownEl = document.getElementById("countdown");
  const titleEl = document.getElementById("title");
  const subtitleEl = document.getElementById("subtitle");

  const timer = setInterval(() => {
    const now = new Date().getTime();
    const distance = targetDate - now;

    if (distance <= 0) {
      clearInterval(timer);
      countdownEl.style.display = "none";
      subtitleEl.style.display = "none";
      titleEl.innerHTML =
        '❤️ <span class="love">HAPPY BIRTHDAY LOVE, RAMIYAH</span> ❤️';
      startConfetti();
      return;
    }

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    countdownEl.innerHTML =
      `${days}d ${hours}h ${minutes}m ${seconds}s`;
  }, 1000);

  /* 💖 Floating hearts */
  function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (4 + Math.random() * 4) + "s";
    document.body.appendChild(heart);

    setTimeout(() => {
      heart.remove();
    }, 8000);
  }

  setInterval(createHeart, 300);

  /* 🎊 Confetti */
  const canvas = document.getElementById("confetti");
  const ctx = canvas.getContext("2d");

  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;

  const pieces = [];
  for (let i = 0; i < 180; i++) {
    pieces.push({
      x: Math.random() * canvas.width,
      y: Math.random() * canvas.height,
      r: Math.random() * 6 + 4,
      d: Math.random() * 5 + 2,
      color: `hsl(${Math.random() * 360},100%,60%)`
    });
  }

  function startConfetti() {
    setInterval(drawConfetti, 20);
  }

  function drawConfetti() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    pieces.forEach(p => {
      ctx.beginPath();
      ctx.fillStyle = p.color;
      ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2);
      ctx.fill();
      p.y += p.d;
      if (p.y > canvas.height) p.y = 0;
    });
  }
</script>

</body>
</html>
