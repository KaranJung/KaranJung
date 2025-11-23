<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KaranJung://root_access_granted</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap');
    
    body {
      background: #000;
      color: #0f0;
      font-family: 'Orbitron', monospace;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      background-image: 
        radial-gradient(circle at 10% 20%, rgba(0, 255, 0, 0.1) 0%, transparent 20%),
        radial-gradient(circle at 90% 80%, rgba(0, 255, 255, 0.1) 0%, transparent 20%);
    }

    .matrix-rain {
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      pointer-events: none;
      z-index: 1;
      opacity: 0.15;
    }

    .container {
      position: relative;
      z-index: 10;
      padding: 40px;
      min-height: 100vh;
    }

    h1 {
      font-size: 4rem;
      text-align: center;
      text-shadow: 0 0 20px #0f0;
      animation: glow 2s infinite alternate;
      letter-spacing: 8px;
    }

    .terminal {
      background: rgba(0, 20, 0, 0.8);
      border: 2px solid #0f0;
      border-radius: 10px;
      padding: 20px;
      margin: 30px auto;
      max-width: 900px;
      box-shadow: 0 0 30px #0f0;
      animation: flicker 4s infinite;
    }

    .prompt {
      color: #0ff;
    }

    .typing {
      overflow: hidden;
      border-right: 3px solid #0f0;
      white-space: nowrap;
      animation: typing 4s steps(50, end), blink 0.75s step-end infinite;
    }

    @keyframes glow { from { text-shadow: 0 0 10px #0f0; } to { text-shadow: 0 0 40px #0f0, 0 0 60px #0f0; } }
    @keyframes flicker { 0%,100% { opacity: 1; } 50% { opacity: 0.8; } }
    @keyframes typing { from { width: 0 } to { width: 100% } }
    @keyframes blink { from, to { border-color: transparent } 50% { border-color: #0f0 } }

    .glitch {
      color: #0f0;
      position: relative;
      animation: glitch 3s infinite;
    }

    @keyframes glitch {
      0%,100% { text-shadow: 2px 0 #f0f, -2px 0 #0ff; clip-path: inset(0); }
      20% { text-shadow: -2px 0 #f0f, 2px 0 #0ff; clip-path: inset(99% 0 1% 0); }
      40% { text-shadow: 2px 0 #0ff, -2px 0 #f0f; clip-path: inset(1% 0 90% 0); }
    }

    .skills-matrix {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin: 40px 0;
    }

    .skill-node {
      background: rgba(0, 255, 0, 0.1);
      padding: 15px;
      text-align: center;
      border: 1px solid #0f0;
      border-radius: 8px;
      transition: all 0.3s;
    }

    .skill-node:hover {
      background: #0f0;
      color: #000;
      transform: translateY(-10px) scale(1.1);
      box-shadow: 0 0 30px #0f0;
    }

    .snake {
      margin: 50px auto;
      text-align: center;
    }

    .connect-btn {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      background: transparent;
      border: 2px solid #0f0;
      color: #0f0;
      text-decoration: none;
      border-radius: 5px;
      transition: all 0.4s;
    }

    .connect-btn:hover {
      background: #0f0;
      color: #000;
      box-shadow: 0 0 30px #0f0;
      transform: scale(1.2);
    }
  </style>
</head>
<body>

<canvas class="matrix-rain" id="matrix"></canvas>

<div class="container">
  <h1 class="glitch">KARANJUNG://ACCESS_GRANTED</h1>
  
  <div class="terminal">
    <p class="prompt">root@matrix:~# whoami</p>
    <p class="typing">> Full-Stack Reality Bender | Code Alchemist | Digital Ninja from Nepal</p>
    
    <p class="prompt">root@matrix:~# status</p>
    <p>> Currently hacking the simulation with JavaScript, Python & pure chaos<br>
       > Coffee level: Critical<br>
       > Music: Lo-fi + Synthwave<br>
       > Mode: GOD.exe activated</p>

    <p class="prompt">root@matrix:~# scan --skills</p>
    <div class="skills-matrix">
      <div class="skill-node">JAVASCRIPT</div>
      <div class="skill-node">PYTHON</div>
      <div class="skill-node">REACT</div>
      <div class="skill-node">NODE.js</div>
      <div class="skill-node">DJANGO</div>
      <div class="skill-node">DOCKER</div>
      <div class="skill-node">TAILWIND</div>
      <div class="skill-node">FIGMA</div>
      <div class="skill-node">KOTLIN</div>
      <div class="skill-node">C++</div>
    </div>

    <p class="prompt">root@matrix:~# current_mission</p>
    <p>> Building <a href="https://github.com/KaranJung/Student-College-Finder" style="color:#0ff">Student College Finder</a> - Helping souls escape the education matrix<br>
       > Mastering Figma & React like Neo mastered bullet time<br>
       > Learning to bend the DOM to my will</p>

    <p class="prompt">root@matrix:~# connect --protocol=quantum</p>
    <div style="text-align:center; margin:30px 0">
      <a href="https://karanjungbudhathoki.com.np/" class="connect-btn">ENTER PORTFOLIO</a>
      <a href="mailto:underside001@gmail.com" class="connect-btn">SEND SIGNAL</a>
      <a href="https://linkedin.com/in/karan-jung-budhathoki" class="connect-btn">LINKEDIN NODE</a>
      <a href="https://instagram.com/karan_jung_budhathoki" class="connect-btn">INSTA PORTAL</a>
    </div>

    <p class="prompt">root@matrix:~# fun_facts --decrypt</p>
    <p>> I code better when keyboard sounds like rain<br>
       > Coffee = compiler fuel<br>
       > Gaming + music = defrag brain<br>
       > There is no spoon... but there is dark mode</p>
  </div>

  <div class="snake">
    <img src="https://github.com/KaranJung/KaranJung/blob/output/github-contribution-grid-snake-dark.svg?raw=true" alt="My contribution snake eating my contributions">
  </div>

  <div style="text-align:center; margin-top:50px; font-size:1.5rem; animation: glow 3s infinite alternate;">
    <p>> System online. Ready to bend reality.</p>
    <p>> Choose the red pill? You're already here.</p>
  </div>
</div>

<script>
// Matrix Rain Effect
const canvas = document.getElementById('matrix');
const ctx = canvas.getContext('2d');

canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

const letters = '01アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン';
const fontSize = 16;
const columns = canvas.width / fontSize;

const drops = Array(Math.floor(columns)).fill(1);

function draw() {
  ctx.fillStyle = 'rgba(0, 0, 0, 0.05)';
  ctx.fillRect(0, 0, canvas.width, canvas.height);

  ctx.fillStyle = '#0f0';
  ctx.font = fontSize + 'px monospace';

  for (let i = 0; i < drops.length; i++) {
    const text = letters.charAt(Math.floor(Math.random() * letters.length));
    ctx.fillText(text, i * fontSize, drops[i] * fontSize);

    if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
      drops[i] = 0;
    }
    drops[i]++;
  }
}

setInterval(draw, 35);

window.addEventListener('resize', () => {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
});
</script>

</body>
</html>
