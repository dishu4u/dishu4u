<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dishu Portfolio</title>

<style>
/* ===== GLOBAL ===== */
body{
  margin:0;
  font-family:Arial, sans-serif;
  background:#0d0d0d;
  color:white;
}

/* ===== HEADER ===== */
header{
  text-align:center;
  padding:60px 20px;
}

/* NAME HOVER EFFECT */
.name{
  font-size:2.8rem;
  font-weight:bold;
  display:inline-block;
  transition:0.3s ease;
  cursor:pointer;
}

.name:hover{
  color:cyan;
  text-shadow:0 0 15px cyan, 0 0 30px blue;
  transform:scale(1.05);
}

/* SUBTITLE */
.subtitle{
  color:#aaa;
  margin-top:10px;
}

/* ===== SECTION ===== */
section{
  padding:40px 20px;
  max-width:900px;
  margin:auto;
}

/* HEADINGS */
h2{
  color:cyan;
  margin-bottom:15px;
}

/* LIST CLEAN */
ul{
  line-height:1.8;
  color:#ddd;
}

/* ===== PROJECT CARD ===== */
.card{
  background:#151515;
  padding:20px;
  border-radius:12px;
  border:1px solid #222;
  transition:0.3s;
}

.card:hover{
  transform:translateY(-5px);
  border-color:cyan;
  box-shadow:0 0 15px rgba(0,255,255,0.2);
}

/* ===== FOOTER ===== */
footer{
  text-align:center;
  padding:20px;
  color:#666;
  border-top:1px solid #222;
}
</style>
</head>

<body>

<header>
  <div class="name">Hi 👋, I'm Dishu</div>
  <div class="subtitle">
    Java Developer | Open Source Enthusiast | GSSoC Project Admin Applicant
  </div>
</header>

<section>
  <h2>🚀 About Me</h2>
  <ul>
    <li>Aspiring Software Developer focused on Java & Web Technologies</li>
    <li>Currently strengthening skills in Full Stack Development</li>
    <li>Building projects like The-Pacman-Game to enhance problem-solving</li>
    <li>Passionate about Open Source contribution and collaboration</li>
    <li>Exploring GitHub workflows, version control, and project management</li>
    <li>Continuously learning, building, and improving development skills</li>
  </ul>
</section>

<section>
  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li>Java, JavaScript, HTML, CSS</li>
    <li>Git & GitHub, VS Code, IntelliJ IDEA, Android Studio</li>
    <li>Figma, Canva</li>
    <li>Swing / AWT</li>
    <li>React (Learning)</li>
  </ul>
</section>

<section>
  <h2>🎮 Featured Project</h2>

  <div class="card">
    <h3>The-Pacman-Game</h3>
    <p>Classic Pac-Man Game built using Java Swing/AWT with open-source collaboration support.</p>
    <p><b>⭐ Open for Contributions</b></p>
  </div>
</section>

<section>
  <h2>📫 Connect With Me</h2>
  <p>GitHub: <a href="https://github.com/dishu4u" style="color:cyan;">@dishu4u</a></p>
</section>

<footer>
  © 2026 Dishu | Built with clean UI ✨
</footer>

</body>
</html>
