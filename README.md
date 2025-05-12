<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tegarrn's GitHub</title>
  <style>
    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
    }
    .header {
      text-align: center;
      padding: 3rem 1rem;
      animation: fadeInDown 2s ease-in-out;
    }
    .header h1 {
      font-size: 3.5rem;
      background: linear-gradient(90deg, #ff758c, #ff7eb3);
      -webkit-background-clip: text;
      color: transparent;
      animation: typing 4s steps(20, end);
    }
    .profile-pic {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 4px solid #00ffff;
      box-shadow: 0 0 20px #00ffff;
      animation: float 3s ease-in-out infinite;
    }
    .section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    .elaina-gif {
      width: 100%;
      max-width: 400px;
      border-radius: 10px;
      animation: rotate 10s linear infinite;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
    }
    .skill-card {
      background: rgba(255, 255, 255, 0.1);
      padding: 1rem 1.5rem;
      border-radius: 15px;
      text-align: center;
      width: 180px;
      transition: transform 0.3s, box-shadow 0.3s;
      border: 1px solid #00ffff88;
    }
    .skill-card:hover {
      transform: scale(1.1);
      box-shadow: 0 0 15px #00ffff;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .project-card {
      background: #1e1e2f;
      border-radius: 15px;
      padding: 1.5rem;
      transition: all 0.3s;
      border-left: 4px solid #00ffff;
    }
    .project-card:hover {
      box-shadow: 0 0 20px #00ffff;
      transform: translateY(-5px);
    }
    .anime-list {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
    }
    .anime-img {
      width: 120px;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
      border: 2px solid #00ffff;
      transition: transform 0.3s;
    }
    .anime-img:hover {
      transform: scale(1.3) rotate(5deg);
    }
    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <div class="header">
    <img src="https://files.catbox.moe/wrgzf5.jpg " alt="Profile Picture" class="profile-pic">
    <h1>Hello! 👋 I'm Tegarrn</h1>
    <p>Web Developer | Cybersecurity Enthusiast | Anime & Game Lover 🎮</p>
  </div>

  <div class="section">
    <h2 style="text-align:center;">About Me</h2>
    <p style="text-align:center; font-size:1.1rem;">
      🌟 Saya seorang <strong>Web Developer</strong> yang mencintai desain responsif dan pengembangan backend. 
      Di sisi lain, saya juga tertarik dengan dunia <strong>Cybersecurity</strong> untuk menjaga data dan sistem tetap aman. 
      Saat senggang, saya menikmati menonton anime dan bermain game! 🎮✨
    </p>
  </div>

  <div class="section">
    <h2 style="text-align:center;">Anime Favorite</h2>
    <img src="https://media.tenor.com/7YNsEtCJnYwAAAAC/elaina-majo-no-tabitabi.gif " alt="Elaina from Majo no Tabi" class="elaina-gif">
    <p style="text-align:center; margin-top:1rem;">
      🧙‍♀️ Elaina dari <strong>Majo no Tabi Tabi</strong> adalah karakter favorit saya! Petualangannya menginspirasi saya untuk terus belajar dan eksplorasi dunia teknologi.
    </p>
  </div>

  <div class="section">
    <h2 style="text-align:center;">Skills & Expertise</h2>
    <div class="skills">
      <div class="skill-card">🌐 Web Development</div>
      <div class="skill-card">🔒 Cybersecurity</div>
      <div class="skill-card">🚀 JavaScript</div>
      <div class="skill-card">🧱 React & Node.js</div>
      <div class="skill-card">🛡️ Ethical Hacking</div>
      <div class="skill-card">🔧 Linux & CLI</div>
    </div>
  </div>

  <div class="section">
    <h2 style="text-align:center;">Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>Website pribadi dengan animasi dan desain responsif.</p>
        <a href="#">View Project →</a>
      </div>
      <div class="project-card">
        <h3>Cybersecurity Lab</h3>
        <p>Simulasi serangan dan pertahanan jaringan.</p>
        <a href="#">View Project →</a>
      </div>
    </div>
  </div>

  <div class="section">
    <h2 style="text-align:center;">Anime Collection</h2>
    <div class="anime-list">
      <img src="https://cdn.myanimelist.net/images/anime/5/82581.jpg " alt="Demon Slayer" class="anime-img">
      <img src="https://cdn.myanimelist.net/images/anime/5/81965.jpg " alt="Attack on Titan" class="anime-img">
      <img src="https://cdn.myanimelist.net/images/anime/5/121218.jpg " alt="Jujutsu Kaisen" class="anime-img">
      <img src="https://cdn.myanimelist.net/images/anime/5/121218.jpg " alt="Majo no Tabi Tabi" class="anime-img">
    </div>
  </div>

  <div class="section">
    <h2 style="text-align:center;">Connect With Me</h2>
    <p style="text-align:center;">
      <a href="https://linkedin.com/in/tegarrn "><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white " alt="LinkedIn"></a>
      <a href="https://discord.gg/tegarrn "><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white " alt="Discord"></a>
      <a href="https://instagram.com/tegarrn "><img src="https://img.shields.io/badge/Instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white " alt="Instagram"></a>
    </p>
  </div>

  <div class="section" style="text-align:center;">
    <p>💬 Terima kasih telah berkunjung! Jangan ragu untuk menghubungi saya jika ingin berdiskusi tentang teknologi atau anime! 🌈</p>
  </div>
</body>
</html>