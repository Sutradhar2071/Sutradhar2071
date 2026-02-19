<h1 align="center">👋 Hi there! I'm Ringku Sutradhar</h1>

<p align="center">
  <b>MERN Stack Developer</b> | Frontend Specialist | Tech Enthusiast from 🇧🇩 Bangladesh
</p>


<p align="center">
  <img src="https://i.ibb.co/mCP4P7fL/Navy-Blue-Geometric-Technology-Linked-In-Banner.png" alt="Profile Banner" width="100%" />
</p>



---

### 🧑‍💻 About Me
- 🔭 I’m a passionate MERN Stack Developer
- 💻 Skilled in: HTML5, CSS3, TailwindCSS, DaisyUI, JavaScript, React, Firebase, Express.js, MongoDB
- 💼 Actively looking for job and freelance opportunities
- 🚀 Goal: Build my own SaaS product and launch a tech startup
- 📍 Based in: Bangladesh

---

### 🛠️ Tech Stack & Tools

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-FF4785?style=flat&logo=styled-components&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---



### 📫 Contact Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ringku-sutradhar-8461002aa/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-0A66C2?style=flat&logo=vercel&logoColor=white)](https://ringku-sd-codesign.vercel.app/)
[![Gmail](https://img.shields.io/badge/-Email-red?style=flat&logo=gmail&logoColor=white)](mailto:sutradharringku@gmail.com)

---

### 🔥 GitHub Streak

![GitHub Streak](https://streak-stats.demolab.com/?user=Sutradhar2071&theme=react)


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Top Languages</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&family=Syne:wght@700;800&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #0a0f1e;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    font-family: 'JetBrains Mono', monospace;
  }

  .card {
    background: linear-gradient(135deg, #0d1224 0%, #111827 100%);
    border: 1px solid rgba(99, 210, 170, 0.2);
    border-radius: 16px;
    padding: 28px 32px;
    width: 420px;
    position: relative;
    overflow: hidden;
    box-shadow: 0 0 60px rgba(99, 210, 170, 0.07), 0 20px 40px rgba(0,0,0,0.5);
  }

  .card::before {
    content: '';
    position: absolute;
    top: -60px; right: -60px;
    width: 200px; height: 200px;
    background: radial-gradient(circle, rgba(99,210,170,0.08) 0%, transparent 70%);
    pointer-events: none;
  }

  .card::after {
    content: '';
    position: absolute;
    bottom: -40px; left: -40px;
    width: 160px; height: 160px;
    background: radial-gradient(circle, rgba(56,189,248,0.06) 0%, transparent 70%);
    pointer-events: none;
  }

  .header {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 22px;
  }

  .header-icon {
    font-size: 18px;
  }

  .title {
    font-family: 'Syne', sans-serif;
    font-size: 14px;
    font-weight: 700;
    color: #63d2aa;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .username {
    margin-left: auto;
    font-size: 11px;
    color: rgba(255,255,255,0.3);
    letter-spacing: 0.05em;
  }

  .progress-track {
    display: flex;
    height: 10px;
    border-radius: 99px;
    overflow: hidden;
    margin-bottom: 24px;
    gap: 2px;
  }

  .progress-seg {
    height: 100%;
    border-radius: 99px;
    transition: flex 1s ease;
  }

  .langs {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px 20px;
  }

  .lang-item {
    display: flex;
    align-items: center;
    gap: 8px;
    animation: fadeUp 0.5s ease both;
  }

  .lang-item:nth-child(1) { animation-delay: 0.05s; }
  .lang-item:nth-child(2) { animation-delay: 0.1s; }
  .lang-item:nth-child(3) { animation-delay: 0.15s; }
  .lang-item:nth-child(4) { animation-delay: 0.2s; }
  .lang-item:nth-child(5) { animation-delay: 0.25s; }
  .lang-item:nth-child(6) { animation-delay: 0.3s; }
  .lang-item:nth-child(7) { animation-delay: 0.35s; }
  .lang-item:nth-child(8) { animation-delay: 0.4s; }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(8px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .dot {
    width: 10px; height: 10px;
    border-radius: 50%;
    flex-shrink: 0;
  }

  .lang-name {
    font-size: 12px;
    color: rgba(255,255,255,0.85);
    font-weight: 600;
    flex: 1;
  }

  .lang-pct {
    font-size: 11px;
    color: rgba(255,255,255,0.4);
    text-align: right;
  }

  .divider {
    height: 1px;
    background: rgba(255,255,255,0.06);
    margin: 20px 0 16px;
  }

  .footer {
    font-size: 10px;
    color: rgba(255,255,255,0.2);
    letter-spacing: 0.04em;
    text-align: center;
  }
</style>
</head>
<body>

<div class="card">
  <div class="header">
    <span class="header-icon">🧠</span>
    <span class="title">Top Languages</span>
    <span class="username">@joshxfi</span>
  </div>

  <div class="progress-track" id="track"></div>

  <div class="langs" id="langs"></div>

  <div class="divider"></div>
  <div class="footer">github-readme-stats · compact layout</div>
</div>

<script>
  const langs = [
    { name: 'React.js',     pct: 28, color: '#61DAFB' },
    { name: 'Node.js',      pct: 18, color: '#6CC24A' },
    { name: 'MongoDB',      pct: 14, color: '#47A248' },
    { name: 'Express',      pct: 12, color: '#868686' },
    { name: 'TailwindCSS',  pct: 11, color: '#38BDF8' },
    { name: 'CSS',          pct: 8,  color: '#2965F1' },
    { name: 'HTML',         pct: 6,  color: '#E44D26' },
    { name: 'JavaScript',   pct: 3,  color: '#F7DF1E' },
  ];

  const track = document.getElementById('track');
  const langsEl = document.getElementById('langs');

  langs.forEach(l => {
    const seg = document.createElement('div');
    seg.className = 'progress-seg';
    seg.style.flex = l.pct;
    seg.style.background = l.color;
    seg.title = `${l.name}: ${l.pct}%`;
    track.appendChild(seg);

    const item = document.createElement('div');
    item.className = 'lang-item';
    item.innerHTML = `
      <div class="dot" style="background:${l.color}"></div>
      <span class="lang-name">${l.name}</span>
      <span class="lang-pct">${l.pct}%</span>
    `;
    langsEl.appendChild(item);
  });
</script>

</body>
</html>



---

### 🚀 Technologies I Work With:

- 💻 Frontend: HTML5, CSS3, TailwindCSS, DaisyUI  
- ⚛️ JavaScript, React.js, React Router  
- 🔥 Firebase (Authentication, Hosting)  
- 🌐 Backend: Node.js, Express.js, MongoDB  
- 🛠️ Tools: Git, GitHub, REST API  
- 📱 Responsive Web Design, SPA

---

### ⚡ Fun Fact
> I love learning something new every single day — especially tech that solves real-world problems!

---

### 👀 Profile Views

![Profile Views](https://komarev.com/ghpvc/?username=RingkuSutradhar&color=blueviolet)

