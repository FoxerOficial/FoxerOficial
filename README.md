<!-- 
🎨 Creative & Animated "About Me" Section for Juan 
This file uses custom HTML/CSS for animation and creative formatting within markdown.
Note: On GitHub, some advanced styling/animation may not fully render, but this provides a visually engaging layout!
-->

<style>
@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap');
.about-title {
  font-size: 3em;
  font-family: 'Orbitron', Arial, sans-serif;
  color: #00ffe7;
  text-shadow: 0 0 15px #000, 0 0 10px #00ffe7;
  animation: neon-glow 1.5s infinite alternate;
  letter-spacing: 0.05em;
}

@keyframes neon-glow {
  from { text-shadow: 0 0 15px #000, 0 0 10px #00ffe7; color: #00ffe7;}
  to   { text-shadow: 0 0 30px #00ffe7, 0 0 40px #00ffe7; color: #fff;}
}

.section-header {
  font-size: 1.5em;
  color: #ffae00;
  margin-top: 2em;
  letter-spacing: 0.04em;
  text-shadow: 0 0 3px #000;
  animation: slide-in 1s;
}
@keyframes slide-in {
  0% { opacity: 0; transform: translateX(-30px);}
  100% { opacity: 1; transform: translateX(0);}
}

.highlight {
  color: #00bfff;
  font-weight: bold;
}

.games-list {
  background: linear-gradient(90deg, #222 60%, #00ffe7 100%);
  border-radius: 15px;
  padding: 1em;
  color: #fff;
  box-shadow: 0 4px 24px #00ffe750;
  margin: 1em 0;
  animation: fadein 2s;
}
@keyframes fadein {
  from { opacity: 0;}
  to   { opacity: 1;}
}

.emoji {
  font-size: 1.3em;
  margin-right: 0.3em;
  vertical-align: middle;
}

.car-emoji {
  animation: car-move 5s linear infinite;
  display: inline-block;
  font-size: 2em;
}
@keyframes car-move {
  0% { transform: translateX(0);}
  15% { transform: translateX(40px);}
  25% { transform: translateX(30px);}
  40% { transform: translateX(60px);}
  60% { transform: translateX(90px);}
  80% { transform: translateX(120px);}
  100% { transform: translateX(0);}
}
</style>

<div align="center">
  <div class="about-title">🚀 <span style="color:#ffae00;">JUAN</span> — Mechatronics Dreamer</div>
  <div style="font-size:1.2em; color:#aaa;">Turning imagination into <span class="highlight">technology</span></div>
</div>

---

<div class="section-header">🔑 Key Skills</div>

- <span class="emoji">🐍</span> <b>Python</b> & <b>Django</b> for web apps and creative automation
- <span class="emoji">🤖</span> Exploring <b>robotics</b> & <b>mechatronic systems</b>
- <span class="emoji">🛠️</span> <b>Problem solver</b> & project builder
- <span class="emoji">🚗</span> <b>Car design</b> fan — from mechanics to futuristic ideas

---

<div class="section-header">🎯 Current Focus</div>
<ul>
  <li>Deepening my programming & robotics knowledge for Mechatronics Engineering at <b>UAO</b></li>
  <li>Experimenting with new tools and building small robots & automations</li>
</ul>

---

<div class="section-header">🎮 <span style="color:#00ffe7;">Games & Simulations I Love</span></div>
<div class="games-list">
  <span class="emoji">🕹️</span>
  <b>Valve Games:</b> TF2, Half-Life, Half-Life 2, Portal 1 & 2 <br>
  <span class="emoji">🏁</span>
  <b>Need for Speed</b> (all my life, all the time!) <br>
  <span class="emoji">🛻</span>
  <b>BeamNG.drive</b> — for realistic car physics <br>
  <span class="emoji">✈️</span>
  <b>Flight Simulators</b> — the sky isn’t the limit!
</div>

---

<div class="section-header">🤩 Fun Facts & Hobbies</div>

- <span class="car-emoji">🚗💨</span> <b>Obsessed with cars</b> — design, mechanics, racing, and the future of mobility!
- <span class="emoji">🧩</span> Constantly exploring new programming tools and applying them to <b>innovative projects</b>
- <span class="emoji">🛸</span> Always learning about <b>autonomous systems</b> & <b>automation</b>
- <span class="emoji">🥽</span> Dream: Build my own robot (or maybe a self-driving car!)

---

<div align="center" style="margin:2em 0;">
  <span style="font-size:1.7em; color:#00ffe7; font-weight:bold; border-bottom:2px dashed #ffae00;">Let’s build the future, one crazy idea at a time!</span>
</div>
