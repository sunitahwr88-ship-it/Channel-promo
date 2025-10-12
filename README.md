<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chanel Sahitya — Where Words Find Home</title>
  <meta name="description" content="Chanel Sahitya — poetry, stories, and reflections. Join us for soulful readings, literary talks, and creative inspiration." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0a0a13;
      --card:#101826;
      --accent:#ff6b6b;
      --accent-hover:#ff8787;
      --muted:#9ca3af;
      --text:#e5e7eb;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:Inter,system-ui,sans-serif;
      background:linear-gradient(180deg,#090f1a 0%,#0e1728 60%,#090f1a 100%);
      color:var(--text);
      line-height:1.6;
      -webkit-font-smoothing:antialiased;
      scroll-behavior:smooth;
    }
    .container{max-width:1100px;margin:0 auto;padding:2rem}
    header{display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:1rem}
    .logo{display:flex;align-items:center;gap:0.8rem}
    .logo-badge{width:56px;height:56px;display:grid;place-items:center;border-radius:14px;background:linear-gradient(135deg,var(--accent),#ffd166);color:#111827;font-weight:800;font-size:1.4rem}
    h1{font-size:1.8rem;font-weight:700;letter-spacing:-0.5px}
    p.lead{color:var(--muted);font-size:1rem}
    nav button{background:none;border:1px solid rgba(255,255,255,0.1);color:var(--text);padding:0.6rem 1rem;border-radius:10px;cursor:pointer;transition:all 0.2s ease;font-weight:500}
    nav button:hover{border-color:var(--accent);color:var(--accent)}
    .btn-primary{background:var(--accent);border:none;color:#111827}
    .btn-primary:hover{background:var(--accent-hover)}
    .hero{display:grid;grid-template-columns:1fr 350px;gap:2rem;align-items:center;margin-top:2.5rem}
    .card{background:var(--card);border-radius:16px;padding:1.6rem;box-shadow:0 8px 24px rgba(0,0,0,0.4);border:1px solid rgba(255,255,255,0.05)}
    .hero h2{font-size:1.4rem;margin-bottom:0.8rem}
    .tags{display:flex;flex-wrap:wrap;gap:0.6rem;margin-bottom:1rem}
    .tag{background:rgba(255,255,255,0.08);padding:0.4rem 0.8rem;border-radius:999px;font-size:0.85rem;color:var(--muted)}
    .cta-row{display:flex;gap:0.8rem;margin-top:1.2rem;flex-wrap:wrap}
    input[type="email"]{flex:1;padding:0.6rem 1rem;border-radius:8px;border:none;background:rgba(255,255,255,0.05);color:var(--text)}
    .preview-video{height:250px;display:grid;place-items:center;border-radius:12px;background:radial-gradient(circle at top left,#1f2937,#0f172a);color:var(--muted);font-weight:600;overflow:hidden;}
    iframe{width:100%;height:100%;border:none;border-radius:12px}
    .stats{margin-top:1rem;display:grid;gap:0.6rem}
    .stat strong{font-size:1.25rem}
    #videos{margin-top:3rem}
    h3{margin-bottom:1rem;font-size:1.4rem}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:1rem}
    .video-card{background:rgba(255,255,255,0.03);padding:1rem;border-radius:12px;transition:transform 0.2s ease,box-shadow 0.2s ease}
    .video-card:hover{transform:translateY(-4px);box-shadow:0 6px 18px rgba(0,0,0,0.3)}
    .thumbnail{height:130px;border-radius:10px;display:grid;place-items:center;font-weight:600;color:var(--muted);background:linear-gradient(135deg,#0d1b2a,#1b263b)}
    .video-title{margin-top:0.7rem;font-size:1rem;font-weight:500}
    .meta{font-size:0.8rem;color:var(--muted)}
    footer{margin-top:3rem;text-align:center;color:var(--muted);font-size:0.9rem}
    footer a{color:var(--muted);text-decoration:none;margin:0 0.6rem}
    footer a:hover{color:var(--accent)}
    .floating-subscribe{position:fixed;bottom:20px;right:20px;z-index:1000}
    @media (max-width:850px){.hero{grid-template-columns:1fr}.hero .right{order:-1}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <div class="logo-badge">S</div>
        <div>
          <h1>Chanel Sahitya</h1>
          <p class="lead">Poetry • Stories • Live Readings — where words meet heart</p>
        </div>
      </div>
      <nav>
        <button onclick="scrollToSection('videos')">Latest</button>
        <button onclick="scrollToSection('about')">About</button>
        <a href="https://www.youtube.com/@sahityaastudy" target="_blank"><button class="btn-primary">Subscribe</button></a>
      </nav>
    </header>

    <section class="hero">
      <div class="left card">
        <h2>Discover stories that breathe — listen, feel, and lose yourself in language.</h2>
        <div class="tags">
          <div class="tag">#Poetry</div>
          <div class="tag">#Stories</div>
          <div class="tag">#Hindi</div>
          <div class="tag">#English</div>
          <div class="tag">#SoulfulReads</div>
        </div>
        <p>At <strong>Chanel Sahitya</strong>, we bring literature to life through heartfelt narration and emotion. Join a community of listeners who believe words can heal, move, and inspire.</p>

        <div class="cta-row">
          <a href="https://www.youtube.com/@sahityaastudy" target="_blank"><button class="btn-primary">Subscribe on YouTube</button></a>
          <button onclick="scrollToSection('videos')">Watch Latest</button>
        </div>

        <div style="margin-top:1rem">
          <label for="email" style="font-size:0.85rem;color:var(--muted)">Get weekly reading highlights</label>
          <div style="display:flex;gap:0.6rem;align-items:center;margin-top:0.3rem">
            <input id="email" type="email" placeholder="Your email address">
            <button class="btn-primary" onclick="newsletter()">Join</button>
          </div>
        </div>
      </div>

      <div class="right card">
        <div class="preview-video">
          <iframe src="https://www.youtube.com/embed?listType=user_uploads&list=sahityaastudy" title="Chanel Sahitya Latest Video"></iframe>
        </div>
        <div class="stats">
          <div class="stat"><span>Subscribers</span> <strong>12.4K</strong></div>
          <div class="stat"><span>Avg Watch Time</span> <strong>7m/video</strong></div>
          <div class="stat"><span>Live Events</span> <strong>Every Month</strong></div>
        </div>
      </div>
    </section>

    <section id="videos">
      <h3>Latest Videos</h3>
      <div class="grid">
        <article class="video-card">
          <div class="thumbnail">The Mango Tree 🌳</div>
          <div class="video-title">Poem: The Mango Tree — Words of Nostalgia</div>
          <div class="meta">2 days ago • 9:12</div>
        </article>
        <article class="video-card">
          <div class="thumbnail">Small Town Story</div>
          <div class="video-title">Short Fiction: Life in a Quiet Lane</div>
          <div class="meta">1 week ago • 14:30</div>
        </article>
      </div>
    </section>

    <section id="about" style="margin-top:3rem">
      <div class="card">
        <h3>About Chanel Sahitya</h3>
        <p>Chanel Sahitya is a literary space dedicated to the art of storytelling — across languages, emotions, and genres. We celebrate the blend of sound, silence, and soul in every word we share.</p>
        <ul style="color:var(--muted);margin-top:0.6rem">
          <li>✨ Weekly videos: poems, readings, microfiction</li>
          <li>🎙️ Monthly live readings & creative Q&A sessions</li>
          <li>📘 Free downloadable reading guide for members</li>
        </ul>
      </div>
    </section>

    <footer>
      <p>
        <a href="https://www.youtube.com/@sahityaastudy" target="_blank">YouTube</a> •
        <a href="#">Instagram</a> •
        <a href="#">Twitter/X</a>
      </p>
      <p>© <strong>Chanel Sahitya</strong> — Crafted with love, sound & story.</p>
    </footer>
  </div>

  <div class="floating-subscribe">
    <a href="https://www.youtube.com/@sahityaastudy" target="_blank"><button class="btn-primary">Subscribe</button></a>
  </div>

  <script>
    function scrollToSection(id){const el=document.getElementById(id);if(el) el.scrollIntoView({behavior:'smooth'});}
    function newsletter(){const email=document.getElementById('email


