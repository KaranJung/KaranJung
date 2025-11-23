<div align="center">

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40"/>
<br>
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=40&duration=4000&pause=1000&color=00FF00&center=true&vCenter=true&lines=WELCOME+TO+THE+MATRIX;KARANJUNG//ACCESS_GRANTED;There+is+no+spoon...;Wake+up%2C+Neo...;Follow+the+white+rabbit." alt="Matrix Typing SVG" />

</div>

<style>
  .matrix { 
    position:fixed; top:0; left:0; width:100%; height:100%; pointer-events:none; z-index:-1; opacity:0.15;
  }
  .terminal {
    background: rgba(0,15,0,0.95);
    border: 2px solid #0f0;
    border-radius: 12px;
    padding: 20px;
    margin: 30px auto;
    max-width: 920px;
    box-shadow: 0 0 30px #0f0;
    font-family: 'Courier New', monospace;
    color: #0f0;
    animation: flicker 4s infinite;
    text-align: left;
  }
  @keyframes flicker { 0%,100% {opacity:1} 50% {opacity:0.85} }
  .glitch { 
    animation: glitch 3s infinite;
    font-weight: bold;
    font-size: 1.6em;
  }
  @keyframes glitch {
    0% { text-shadow: 2px 0 #0ff, -2px 0 #f0f; }
    20% { text-shadow: -3px 0 #0ff, 3px 0 #f0f; }
    100% { text-shadow: 2px 0 #0ff, -2px 0 #f0f; }
  }
  .btn {
    display: inline-block;
    margin: 8px;
    padding: 12px 28px;
    background: transparent;
    border: 2px solid #0f0;
    color: #0f0;
    text-decoration: none;
    border-radius: 6px;
    transition: all 0.4s;
  }
  .btn:hover {
    background: #0f0;
    color: #000;
    box-shadow: 0 0 25px #0f0;
    transform: scale(1.15);
  }
</style>

<canvas class="matrix" id="matrix"></canvas>

<br>

<div class="terminal">
  <pre>
<span style="color:#0ff">root@neo</span>:<span style="color:#0f0">~</span>$ whoami
<span class="glitch">KARAN JUNG // FULL-STACK REALITY BENDER</span>

<span style="color:#0ff">root@neo</span>:<span style="color:#0f0">~</span>$ status
> Location: Nepal Matrix Node
> Fuel: 98% Coffee | 2% Sleep
> Currently: Bending spoons with JavaScript
> Mission: Free minds with code

<span style="color:#0ff">root@neo</span>:<span style="color:#0f0">~</span>$ skills --list
<span style="color:#0f0">▸ JavaScript │ Python │ React │ Node.js │ Django │ Laravel
▸ Tailwind │ Docker │ Kotlin │ C++ │ Figma │ Photoshop</span>

<span style="color:#0ff">root@neo</span>:<span style="color:#0f0">~</span>$ projects --top-secret
<span style="color:#0f0">→ <a href="https://github.com/KaranJung/Student-College-Finder" style="color:#0ff">Student College Finder</a> - Breaking the education illusion
→ Learning Figma & React like I learned Kung-Fu</span>

<span style="color:#0ff">root@neo</span>:<span style="color:#0f0">~</span>$ connect --quantum
  </pre>

  <div align="center">
    <a href="https://karanjungbudhathoki.com.np" class="btn">ENTER PORTAL</a>
    <a href="mailto:underside001@gmail.com" class="btn">SEND SIGNAL</a>
    <a href="https://linkedin.com/in/karan-jung-budhathoki" class="btn">LINKEDIN NODE</a>
    <a href="https://instagram.com/karan_jung_budhathoki" class="btn">INSTA PORT</a>
  </div>

  <pre>
<span style="color:#0ff">root@neo</span>:<span style="color:#0f0">~</span>$ fun_facts --decrypt
> I code when the keyboard rains
> Coffee = my Morpheus
> Gaming + Synthwave = bullet-time mode
> There is no bug, only features you haven't understood yet
  </pre>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=karanjung&theme=react-dark&hide_border=true&fire=00ff00&ring=0f0&currStreakLabel=0f0" />
  <br><br>
  <img src="https://github.com/KaranJung/KaranJung/blob/output/github-contribution-grid-snake-dark.svg?raw=true" />
</div>

<script>
// Minimal Matrix rain that works on GitHub (no canvas blocking)
const canvas = document.getElementById('matrix');
if (canvas) {
  const ctx = canvas.getContext('2d');
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
  const chars = '01アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン';
  const fontSize = 14;
  const columns = canvas.width/fontSize;
  const drops = Array(Math.floor(columns)).fill(1);

  function draw() {
    ctx.fillStyle = 'rgba(0,0,0,0.05)';
    ctx.fillRect(0,0,canvas.width,canvas.height);
    ctx.fillStyle = '#0f0';
    ctx.font = fontSize + 'px monospace';
    for(let i = 0; i < drops.length; i++) {
      const text = chars[Math.floor(Math.random()*chars.length)];
      ctx.fillText(text, i*fontSize, drops[i]*fontSize);
      if(drops[i]*fontSize > canvas.height && Math.random() > 0.975) drops[i] = 0;
      drops[i]++;
    }
  }
  setInterval(draw, 40);
}
</script>

<div align="center" style="margin-top:50px; font-size:1.8em; animation: glow 2s infinite alternate;">
  <b>Choose the red pill. You're already in.</b>
</div>

<style>
@keyframes glow {
  from { text-shadow: 0 0 10px #0f0; }
  to { text-shadow: 0 0 40px #0f0, 0 0 60px #0f0; }
}
</style>
