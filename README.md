<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>manassarsenov – GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Syne:wght@400;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d1117;
    --card: #161b22;
    --border: #30363d;
    --text: #c9d1d9;
    --muted: #8b949e;
    --accent: #58a6ff;
    --green: #3fb950;
    --pink: #f78166;
    --yellow: #d29922;
    --purple: #bc8cff;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    padding: 40px 20px;
    max-width: 860px;
    margin: 0 auto;
  }
  h1 { font-family: 'Syne', sans-serif; font-size: 1.6rem; margin-bottom: 8px; color: #fff; }
  h2 { font-family: 'Syne', sans-serif; font-size: 1.1rem; color: var(--accent); margin: 32px 0 12px; border-bottom: 1px solid var(--border); padding-bottom: 6px; }
  h3 { font-family: 'Syne', sans-serif; font-size: 0.95rem; color: var(--purple); margin: 24px 0 10px; }
  p { color: var(--muted); font-size: 0.85rem; line-height: 1.7; }

  /* About */
  .about-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 20px 24px;
    margin-bottom: 8px;
  }
  .about-card .role {
    display: inline-block;
    background: linear-gradient(135deg, #1f6feb, #388bfd);
    color: #fff;
    font-size: 0.7rem;
    font-weight: 700;
    padding: 3px 10px;
    border-radius: 20px;
    margin-bottom: 10px;
    letter-spacing: 1px;
    text-transform: uppercase;
  }

  /* Badges */
  .badges { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px; }
  .badge {
    display: inline-flex; align-items: center; gap: 6px;
    padding: 5px 12px; border-radius: 6px;
    font-size: 0.72rem; font-weight: 700; letter-spacing: 0.5px;
    border: 1px solid rgba(255,255,255,0.08);
    transition: transform 0.15s, box-shadow 0.15s;
    cursor: default;
  }
  .badge:hover { transform: translateY(-2px); box-shadow: 0 4px 12px rgba(0,0,0,0.4); }
  .badge .dot { width: 7px; height: 7px; border-radius: 50%; flex-shrink: 0; }

  /* Socials */
  .socials { display: flex; flex-wrap: wrap; gap: 10px; }
  .social-btn {
    display: inline-flex; align-items: center; gap: 7px;
    padding: 6px 14px; border-radius: 8px;
    font-size: 0.75rem; font-weight: 700; text-decoration: none;
    border: 1px solid var(--border);
    transition: all 0.2s;
    color: #fff;
  }
  .social-btn:hover { filter: brightness(1.2); transform: translateY(-1px); }
  .social-btn.fb { background: #1877F2; }
  .social-btn.ig { background: linear-gradient(135deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888); }
  .social-btn.li { background: #0077B5; }
  .social-btn.em { background: #D14836; }

  /* Stats cards */
  .stats-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  .stats-grid.single { grid-template-columns: 1fr; }
  .stat-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }
  .stat-card img { width: 100%; display: block; }
  .stat-card.full { grid-column: 1 / -1; }

  /* Trophy */
  .trophy-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }
  .trophy-card img { width: 100%; display: block; }

  /* Quote */
  .quote-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }
  .quote-card img { width: 100%; display: block; }

  /* Contrib */
  .contrib-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }
  .contrib-card img { width: 100%; display: block; }

  /* Visitor */
  .visitor { margin-top: 24px; text-align: center; }
  .visitor img { border-radius: 6px; }

  /* Section fade-in */
  section { animation: fadeUp 0.5s ease both; }
  @keyframes fadeUp {
    from { opacity:0; transform: translateY(16px); }
    to   { opacity:1; transform: translateY(0); }
  }
  section:nth-child(1) { animation-delay: 0.05s; }
  section:nth-child(2) { animation-delay: 0.1s; }
  section:nth-child(3) { animation-delay: 0.15s; }
  section:nth-child(4) { animation-delay: 0.2s; }
  section:nth-child(5) { animation-delay: 0.25s; }
  section:nth-child(6) { animation-delay: 0.3s; }
  section:nth-child(7) { animation-delay: 0.35s; }
  section:nth-child(8) { animation-delay: 0.4s; }
</style>
</head>
<body>

<!-- About -->
<section>
  <div class="about-card">
    <span class="role">💫 About Me</span>
    <h1>Junior Python Backend Developer</h1>
    <p>Backend developer specializing in Django & Django REST Framework.<br>
    I enjoy building RESTful services, designing databases, and solving real-world problems through clean and maintainable code.</p>
  </div>
</section>

<!-- Socials -->
<section>
  <h2>🌐 Socials</h2>
  <div class="socials">
    <a class="social-btn fb" href="https://facebook.com/manas.sarsenov" target="_blank">📘 Facebook</a>
    <a class="social-btn ig" href="https://instagram.com/manas.sarsenov" target="_blank">📸 Instagram</a>
    <a class="social-btn li" href="https://linkedin.com/in/manassarsem" target="_blank">💼 LinkedIn</a>
    <a class="social-btn em" href="mailto:sarsenovmanas186@gmail.com">✉️ Email</a>
  </div>
</section>

<!-- Currently Learning -->
<section>
  <h2>🌱 I'm Currently Learning</h2>
  <div class="badges">
    <span class="badge" style="background:#003d4f;color:#00c5a0"><span class="dot" style="background:#00c5a0"></span>FastAPI</span>
    <span class="badge" style="background:#1a3a12;color:#6CC24A"><span class="dot" style="background:#6CC24A"></span>System Design</span>
    <span class="badge" style="background:#3d2800;color:#FFA500"><span class="dot" style="background:#FFA500"></span>Server Deployment</span>
    <span class="badge" style="background:#001f4d;color:#0088FF"><span class="dot" style="background:#0088FF"></span>WebSocket</span>
    <span class="badge" style="background:#3d1a17;color:#FF6F61"><span class="dot" style="background:#FF6F61"></span>API Security</span>
  </div>
</section>

<!-- Tech Stack -->
<section>
  <h2>💻 Tech Stack</h2>
  <div class="badges">
    <span class="badge" style="background:#1a2e45;color:#4b9fdb"><span class="dot" style="background:#ffdd54"></span>Python</span>
    <span class="badge" style="background:#0a1a0f;color:#44b78b"><span class="dot" style="background:#44b78b"></span>Django</span>
    <span class="badge" style="background:#2a0a0a;color:#ff1709"><span class="dot" style="background:#ff1709"></span>Django REST</span>
    <span class="badge" style="background:#111;color:#fff"><span class="dot" style="background:#fff"></span>JWT</span>
    <span class="badge" style="background:#002614;color:#009639"><span class="dot" style="background:#009639"></span>Nginx</span>
    <span class="badge" style="background:#0a1929;color:#336791"><span class="dot" style="background:#336791"></span>PostgreSQL</span>
    <span class="badge" style="background:#2a0505;color:#DD0031"><span class="dot" style="background:#DD0031"></span>Redis</span>
    <span class="badge" style="background:#07131f;color:#0f7c9c"><span class="dot" style="background:#0f7c9c"></span>SQLite</span>
    <span class="badge" style="background:#2a1005;color:#F05033"><span class="dot" style="background:#F05033"></span>Git</span>
    <span class="badge" style="background:#0d1117;color:#fff"><span class="dot" style="background:#fff"></span>GitHub</span>
    <span class="badge" style="background:#01253a;color:#0db7ed"><span class="dot" style="background:#0db7ed"></span>Docker</span>
    <span class="badge" style="background:#1a2a00;color:#85ea2d"><span class="dot" style="background:#85ea2d"></span>Swagger</span>
    <span class="badge" style="background:#001e3c;color:#026AA7"><span class="dot" style="background:#026AA7"></span>Trello</span>
    <span class="badge" style="background:#1a1a1a;color:#ccc"><span class="dot" style="background:#ccc"></span>Jinja</span>
    <span class="badge" style="background:#001a3d;color:#1572B6"><span class="dot" style="background:#1572B6"></span>CSS3</span>
    <span class="badge" style="background:#3d1200;color:#E34F26"><span class="dot" style="background:#E34F26"></span>HTML5</span>
  </div>
</section>

<!-- GitHub Stats -->
<section>
  <h2>📊 GitHub Stats</h2>
  <div class="stats-grid">
    <div class="stat-card">
      <img src="https://github-readme-stats.vercel.app/api?username=manassarsenov&theme=dark&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats" loading="lazy"/>
    </div>
    <div class="stat-card">
      <img src="https://nirzak-streak-stats.vercel.app/?user=manassarsenov&theme=dark&hide_border=false" alt="Streak Stats" loading="lazy"/>
    </div>
    <div class="stat-card full">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=manassarsenov&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages" loading="lazy"/>
    </div>
  </div>
</section>

<!-- Trophies -->
<section>
  <h2>🏆 GitHub Trophies</h2>
  <div class="trophy-card">
    <img src="https://github-profile-trophy.vercel.app/?username=manassarsenov&theme=onedark&column=7&margin-w=15&margin-h=15" alt="Trophies" loading="lazy"/>
  </div>
</section>

<!-- Dev Quote -->
<section>
  <h3>✍️ Random Dev Quote</h3>
  <div class="quote-card">
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="Dev Quote" loading="lazy"/>
  </div>
</section>

<!-- Top Contributed Repo -->
<section>
  <h3>🔝 Top Contributed Repo</h3>
  <div class="contrib-card">
    <img src="https://github-contributor-stats.vercel.app/api?username=manassarsenov&limit=5&theme=transparent&combine_all_yearly_contributions=true" alt="Top Contributed" loading="lazy"/>
  </div>
</section>

<!-- Visitor -->
<div class="visitor">
  <img src="https://visitcount.itsvg.in/api?id=manassarsenov&icon=0&color=0" alt="Visitor Count"/>
</div>

</body>
</html>
