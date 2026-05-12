# Red-Clay-Wolves-2
RCW Landing Page 2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Red Clay Wolves</title>
  <meta name="description" content="Red Clay Wolves Athletics — Basketball, Track & Field, and youth athlete development." />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #050505;
      color: white;
      line-height: 1.6;
    }
    a { color: inherit; text-decoration: none; }
    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
      background:
        radial-gradient(circle at top right, rgba(0,183,255,.35), transparent 30%),
        radial-gradient(circle at bottom left, rgba(109,40,217,.45), transparent 35%),
        linear-gradient(135deg, #000, #100018 55%, #050505);
      text-align: center;
    }
    .container { max-width: 1100px; margin: 0 auto; }
    .logo {
      width: 220px;
      max-width: 80%;
      margin: 0 auto 28px;
      display: block;
    }
    .eyebrow {
      color: #00b7ff;
      letter-spacing: 4px;
      text-transform: uppercase;
      font-weight: 800;
      font-size: 14px;
      margin-bottom: 12px;
    }
    h1 {
      font-size: clamp(48px, 9vw, 96px);
      line-height: .95;
      text-transform: uppercase;
      font-weight: 900;
    }
    h1 span { color: #8b5cf6; }
    .subtitle {
      max-width: 760px;
      margin: 24px auto 0;
      color: #d4d4d8;
      font-size: clamp(18px, 2vw, 24px);
    }
    .buttons {
      display: flex;
      gap: 16px;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 36px;
    }
    .btn {
      padding: 15px 26px;
      border-radius: 999px;
      font-weight: 800;
      border: 2px solid transparent;
    }
    .btn-primary { background: #00b7ff; color: #000; }
    .btn-secondary { border-color: #8b5cf6; color: white; }
    section { padding: 80px 20px; }
    .section-title {
      font-size: clamp(34px, 5vw, 56px);
      text-align: center;
      margin-bottom: 18px;
      text-transform: uppercase;
    }
    .section-subtitle {
      color: #c4c4c4;
      text-align: center;
      max-width: 760px;
      margin: 0 auto 42px;
      font-size: 18px;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 22px;
    }
    .card {
      background: rgba(255,255,255,.05);
      border: 1px solid rgba(255,255,255,.1);
      border-radius: 24px;
      padding: 28px;
      box-shadow: 0 20px 60px rgba(0,0,0,.35);
    }
    .card h3 {
      color: #00b7ff;
      font-size: 26px;
      margin-bottom: 12px;
      text-transform: uppercase;
    }
    .card p { color: #d4d4d8; }
    .dark { background: #09090b; }
    .culture {
      background: linear-gradient(135deg, #050505, #1a0529, #050505);
    }
    .motto {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }
    .motto div {
      border-left: 5px solid #00b7ff;
      background: rgba(0,0,0,.45);
      padding: 22px;
      border-radius: 18px;
    }
    .motto h3 { color: #8b5cf6; font-size: 26px; }
    .cta {
      text-align: center;
      background: #050505;
    }
    footer {
      border-top: 1px solid rgba(255,255,255,.12);
      padding: 26px 20px;
      text-align: center;
      color: #aaa;
      font-size: 14px;
      background: #000;
    }
  </style>
</head>
<body>
  <main>
    <section class="hero">
      <div class="container">
        <!-- Replace logo.png with your real file name after uploading it to GitHub -->
        <img class="logo" src="logo.png" alt="Red Clay Wolves Logo" onerror="this.style.display='none'" />
        <div class="eyebrow">RTU • Relentless Together Unfinished</div>
        <h1>Red Clay <span>Wolves</span></h1>
        <p class="subtitle">
          A grassroots athletics organization developing athletes through discipline, competition, leadership, and exposure.
        </p>
        <div class="buttons">
          <a class="btn btn-primary" href="mailto:info@redclaywolves.com">Join / Tryout</a>
          <a class="btn btn-secondary" href="mailto:info@redclaywolves.com">Sponsor Us</a>
        </div>
      </div>
    </section>

    <section class="dark">
      <div class="container">
        <h2 class="section-title">Our Mission</h2>
        <p class="section-subtitle">
          Red Clay Wolves exists to build athletes who compete with toughness, carry themselves with character, and grow through structure, accountability, and team culture.
        </p>
        <div class="cards">
          <div class="card">
            <h3>Compete</h3>
            <p>Tournament-ready athletes built for effort, execution, and pressure moments.</p>
          </div>
          <div class="card">
            <h3>Develop</h3>
            <p>Skill development, conditioning, discipline, and growth on and off the court or track.</p>
          </div>
          <div class="card">
            <h3>Expose</h3>
            <p>Creating opportunities through branding, highlights, events, and competitive platforms.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="culture">
      <div class="container">
        <h2 class="section-title">RTU Culture</h2>
        <p class="section-subtitle">
          RTU is the standard: Relentless • Together • Unfinished.
        </p>
        <div class="motto">
          <div>
            <h3>Relentless</h3>
            <p>We compete with maximum effort and a disciplined mindset.</p>
          </div>
          <div>
            <h3>Together</h3>
            <p>We move as one team, one family, and one organization.</p>
          </div>
          <div>
            <h3>Unfinished</h3>
            <p>We are never satisfied. Growth is always the goal.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="dark">
      <div class="container">
        <h2 class="section-title">Programs</h2>
        <div class="cards">
          <div class="card">
            <h3>Basketball</h3>
            <p>AAU and travel basketball development for athletes ready to compete, grow, and represent the brand.</p>
          </div>
          <div class="card">
            <h3>Track & Field</h3>
            <p>Speed, power, performance, and discipline for athletes committed to measurable growth.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="cta">
      <div class="container">
        <h2 class="section-title">Join The Pack</h2>
        <p class="section-subtitle">
          Tryouts, sponsorships, partnerships, and volunteer opportunities are available.
        </p>
        <div class="buttons">
          <a class="btn btn-primary" href="mailto:info@redclaywolves.com">Contact Us</a>
          <a class="btn btn-secondary" href="https://instagram.com" target="_blank" rel="noreferrer">Follow Us</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    © 2026 Red Clay Wolves. RTU — Relentless Together Unfinished.
  </footer>
</body>
</html>
