<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aditya Tiwari — Portfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #080808;
    --surface: #111111;
    --surface2: #181818;
    --border: rgba(255,255,255,0.07);
    --accent: #FF3B3B;
    --accent2: #FF8C42;
    --text: #F0EDE8;
    --muted: #888;
    --glow: rgba(255,59,59,0.18);
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; font-size: 16px; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom Cursor */
  .cursor {
    width: 12px; height: 12px;
    background: var(--accent);
    border-radius: 50%;
    position: fixed; top: 0; left: 0;
    pointer-events: none; z-index: 9999;
    transition: transform 0.15s ease;
    mix-blend-mode: difference;
  }
  .cursor-ring {
    width: 36px; height: 36px;
    border: 1.5px solid rgba(255,59,59,0.5);
    border-radius: 50%;
    position: fixed; top: 0; left: 0;
    pointer-events: none; z-index: 9998;
    transition: transform 0.4s ease, width 0.3s, height 0.3s;
  }

  /* Noise overlay */
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none; z-index: 9000; opacity: 0.5;
  }

  /* ─── NAV ─── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    display: flex; align-items: center; justify-content: space-between;
    padding: 1.4rem 4rem;
    background: rgba(8,8,8,0.85);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid var(--border);
  }
  .nav-logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800; font-size: 1.1rem;
    letter-spacing: 0.12em;
    color: var(--text);
    text-decoration: none;
  }
  .nav-logo span { color: var(--accent); }
  .nav-links { display: flex; gap: 2.5rem; list-style: none; }
  .nav-links a {
    color: var(--muted); font-size: 0.82rem; letter-spacing: 0.08em;
    text-transform: uppercase; text-decoration: none;
    transition: color 0.2s;
    position: relative;
  }
  .nav-links a::after {
    content: ''; position: absolute; bottom: -4px; left: 0;
    width: 0; height: 1px; background: var(--accent);
    transition: width 0.3s;
  }
  .nav-links a:hover { color: var(--text); }
  .nav-links a:hover::after { width: 100%; }
  .nav-social { display: flex; gap: 1rem; align-items: center; }
  .nav-social a {
    color: var(--muted); text-decoration: none;
    font-size: 0.75rem; letter-spacing: 0.05em;
    transition: color 0.2s;
  }
  .nav-social a:hover { color: var(--accent); }

  /* ─── HERO ─── */
  #hero {
    min-height: 100vh;
    display: flex; flex-direction: column; justify-content: center;
    padding: 8rem 4rem 4rem;
    position: relative; overflow: hidden;
  }
  .hero-glow {
    position: absolute;
    width: 600px; height: 600px;
    background: radial-gradient(circle, rgba(255,59,59,0.12) 0%, transparent 70%);
    top: -100px; right: -100px;
    pointer-events: none;
    animation: pulse 6s ease-in-out infinite;
  }
  .hero-glow2 {
    position: absolute;
    width: 400px; height: 400px;
    background: radial-gradient(circle, rgba(255,140,66,0.06) 0%, transparent 70%);
    bottom: 0; left: 0;
    pointer-events: none;
    animation: pulse 8s ease-in-out infinite reverse;
  }
  @keyframes pulse {
    0%, 100% { transform: scale(1); opacity: 1; }
    50% { transform: scale(1.15); opacity: 0.7; }
  }

  .hero-tag {
    font-size: 0.72rem; letter-spacing: 0.25em; text-transform: uppercase;
    color: var(--accent); margin-bottom: 1.5rem;
    display: flex; align-items: center; gap: 0.8rem;
    opacity: 0; animation: fadeUp 0.7s 0.3s forwards;
  }
  .hero-tag::before {
    content: ''; width: 40px; height: 1px; background: var(--accent);
  }

  .hero-name {
    font-family: 'Syne', sans-serif;
    font-size: clamp(3.5rem, 9vw, 8rem);
    font-weight: 800; line-height: 0.95;
    letter-spacing: -0.02em;
    margin-bottom: 1.5rem;
    opacity: 0; animation: fadeUp 0.8s 0.5s forwards;
  }
  .hero-name .line2 {
    display: block;
    -webkit-text-stroke: 1.5px rgba(240,237,232,0.3);
    color: transparent;
  }

  .hero-desc {
    max-width: 480px;
    font-size: 1rem; line-height: 1.75;
    color: var(--muted);
    margin-bottom: 3rem;
    opacity: 0; animation: fadeUp 0.8s 0.7s forwards;
  }

  .hero-btns {
    display: flex; gap: 1rem; flex-wrap: wrap;
    opacity: 0; animation: fadeUp 0.8s 0.9s forwards;
  }
  .btn-primary {
    background: var(--accent);
    color: #fff; font-family: 'Syne', sans-serif;
    font-weight: 700; font-size: 0.85rem; letter-spacing: 0.08em;
    text-transform: uppercase; text-decoration: none;
    padding: 0.9rem 2rem; border-radius: 2px;
    transition: transform 0.2s, box-shadow 0.2s;
    box-shadow: 0 0 30px rgba(255,59,59,0.3);
  }
  .btn-primary:hover {
    transform: translateY(-2px);
    box-shadow: 0 0 50px rgba(255,59,59,0.5);
  }
  .btn-outline {
    border: 1px solid rgba(240,237,232,0.2);
    color: var(--text); font-family: 'Syne', sans-serif;
    font-weight: 600; font-size: 0.85rem; letter-spacing: 0.08em;
    text-transform: uppercase; text-decoration: none;
    padding: 0.9rem 2rem; border-radius: 2px;
    transition: border-color 0.2s, color 0.2s;
  }
  .btn-outline:hover { border-color: var(--accent); color: var(--accent); }

  .hero-scroll {
    position: absolute; bottom: 2.5rem; left: 4rem;
    display: flex; align-items: center; gap: 0.8rem;
    font-size: 0.7rem; letter-spacing: 0.2em; text-transform: uppercase; color: var(--muted);
    opacity: 0; animation: fadeUp 0.8s 1.2s forwards;
  }
  .scroll-line {
    width: 60px; height: 1px; background: var(--muted);
    position: relative; overflow: hidden;
  }
  .scroll-line::after {
    content: ''; position: absolute;
    width: 30px; height: 100%; background: var(--accent);
    animation: scrollAnim 2s ease-in-out infinite;
  }
  @keyframes scrollAnim {
    0% { left: -30px; }
    100% { left: 70px; }
  }

  .hero-counter {
    position: absolute; bottom: 2.5rem; right: 4rem;
    display: flex; gap: 3rem;
    opacity: 0; animation: fadeUp 0.8s 1.1s forwards;
  }
  .counter-item { text-align: center; }
  .counter-num {
    font-family: 'Syne', sans-serif; font-weight: 800;
    font-size: 2rem; color: var(--text); display: block;
    line-height: 1;
  }
  .counter-label { font-size: 0.68rem; letter-spacing: 0.15em; color: var(--muted); text-transform: uppercase; margin-top: 0.3rem; }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* ─── SECTION BASE ─── */
  section {
    padding: 7rem 4rem;
    border-top: 1px solid var(--border);
    position: relative;
  }
  .section-eyebrow {
    font-size: 0.7rem; letter-spacing: 0.28em; text-transform: uppercase;
    color: var(--accent); margin-bottom: 0.8rem;
    display: flex; align-items: center; gap: 0.8rem;
  }
  .section-eyebrow::before { content: ''; width: 30px; height: 1px; background: var(--accent); }
  .section-title {
    font-family: 'Syne', sans-serif; font-weight: 800;
    font-size: clamp(2rem, 4vw, 3.5rem);
    line-height: 1.05; letter-spacing: -0.02em;
    margin-bottom: 1rem;
  }
  .section-subtitle { color: var(--muted); font-size: 0.95rem; line-height: 1.7; max-width: 500px; }

  /* ─── ABOUT ─── */
  #about .about-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 5rem;
    align-items: start; margin-top: 4rem;
  }
  .about-text p {
    color: var(--muted); font-size: 1rem; line-height: 1.85;
    margin-bottom: 1.2rem;
  }
  .about-text p strong { color: var(--text); font-weight: 500; }
  .about-text p .accent { color: var(--accent); }

  .core-skills-label {
    font-size: 0.7rem; letter-spacing: 0.2em; text-transform: uppercase;
    color: var(--accent); margin-bottom: 1.2rem; margin-top: 2rem;
  }
  .skill-tags { display: flex; flex-wrap: wrap; gap: 0.5rem; }
  .skill-tag {
    padding: 0.4rem 0.9rem;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 2px;
    font-size: 0.78rem; color: var(--text); letter-spacing: 0.05em;
    transition: border-color 0.2s, color 0.2s;
  }
  .skill-tag:hover { border-color: var(--accent); color: var(--accent); }

  .about-aside {}
  .stat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    padding: 1.5rem; margin-bottom: 1rem;
    border-radius: 2px;
    position: relative; overflow: hidden;
    transition: border-color 0.3s;
  }
  .stat-card::before {
    content: ''; position: absolute;
    top: 0; left: 0; width: 3px; height: 100%;
    background: var(--accent); transform: scaleY(0);
    transition: transform 0.3s; transform-origin: bottom;
  }
  .stat-card:hover::before { transform: scaleY(1); }
  .stat-card:hover { border-color: rgba(255,59,59,0.2); }
  .stat-icon { font-size: 1.3rem; margin-bottom: 0.8rem; }
  .stat-name { font-size: 0.7rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--muted); margin-bottom: 0.3rem; }
  .stat-val { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 1.1rem; color: var(--text); }

  /* ─── EDUCATION ─── */
  #education .edu-list { margin-top: 4rem; display: flex; flex-direction: column; gap: 1.5rem; }
  .edu-card {
    background: var(--surface);
    border: 1px solid var(--border);
    padding: 2rem 2.5rem;
    border-radius: 2px;
    display: grid; grid-template-columns: auto 1fr auto;
    gap: 1.5rem; align-items: center;
    transition: border-color 0.3s, transform 0.3s;
    position: relative; overflow: hidden;
  }
  .edu-card::after {
    content: ''; position: absolute;
    inset: 0; background: linear-gradient(90deg, transparent, rgba(255,59,59,0.03));
    opacity: 0; transition: opacity 0.3s;
  }
  .edu-card:hover { border-color: rgba(255,59,59,0.25); transform: translateX(4px); }
  .edu-card:hover::after { opacity: 1; }
  .edu-num {
    font-family: 'Syne', sans-serif; font-weight: 800;
    font-size: 2.5rem; color: rgba(255,59,59,0.15);
    line-height: 1; min-width: 2.5rem;
  }
  .edu-title { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 1.05rem; margin-bottom: 0.3rem; }
  .edu-sub { color: var(--muted); font-size: 0.85rem; margin-bottom: 0.2rem; }
  .edu-loc { font-size: 0.75rem; color: rgba(136,136,136,0.6); letter-spacing: 0.05em; }
  .edu-badge {
    padding: 0.4rem 1rem; border-radius: 2px;
    font-size: 0.7rem; letter-spacing: 0.1em; text-transform: uppercase;
    font-family: 'Syne', sans-serif; font-weight: 700;
    white-space: nowrap;
  }
  .badge-ongoing { background: rgba(255,59,59,0.12); color: var(--accent); border: 1px solid rgba(255,59,59,0.2); }
  .badge-done { background: rgba(255,255,255,0.04); color: var(--muted); border: 1px solid var(--border); }

  /* ─── SKILLS ─── */
  #skills .skills-tabs { display: flex; gap: 0; margin: 3rem 0 2rem; border-bottom: 1px solid var(--border); }
  .tab-btn {
    padding: 0.8rem 1.5rem; background: none; border: none;
    color: var(--muted); font-family: 'Syne', sans-serif;
    font-size: 0.82rem; font-weight: 600; letter-spacing: 0.08em; text-transform: uppercase;
    cursor: none; position: relative; transition: color 0.2s;
  }
  .tab-btn::after {
    content: ''; position: absolute; bottom: -1px; left: 0; right: 0;
    height: 2px; background: var(--accent);
    transform: scaleX(0); transition: transform 0.3s;
  }
  .tab-btn.active { color: var(--accent); }
  .tab-btn.active::after { transform: scaleX(1); }
  .tab-btn:hover { color: var(--text); }

  .tab-panel { display: none; }
  .tab-panel.active { display: block; animation: fadeUp 0.4s forwards; }

  .skills-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); gap: 1px; background: var(--border); border: 1px solid var(--border); }
  .skill-item {
    background: var(--surface); padding: 1.5rem 1rem;
    text-align: center; transition: background 0.2s;
    cursor: default;
  }
  .skill-item:hover { background: var(--surface2); }
  .skill-icon { font-size: 1.5rem; margin-bottom: 0.6rem; display: block; }
  .skill-name { font-size: 0.8rem; color: var(--muted); letter-spacing: 0.05em; }

  /* ─── PROJECTS ─── */
  #projects .projects-grid {
    display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1.5rem; margin-top: 3rem;
  }
  .project-card {
    background: var(--surface);
    border: 1px solid var(--border);
    padding: 2rem; border-radius: 2px;
    position: relative; overflow: hidden;
    transition: transform 0.3s, border-color 0.3s;
    cursor: default;
  }
  .project-card::before {
    content: ''; position: absolute;
    inset: 0; background: linear-gradient(135deg, rgba(255,59,59,0.05) 0%, transparent 60%);
    opacity: 0; transition: opacity 0.3s;
  }
  .project-card:hover { transform: translateY(-4px); border-color: rgba(255,59,59,0.2); }
  .project-card:hover::before { opacity: 1; }
  .project-num {
    font-family: 'Syne', sans-serif; font-weight: 800;
    font-size: 0.7rem; letter-spacing: 0.2em;
    color: var(--accent); margin-bottom: 1.2rem;
  }
  .project-title { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 1.15rem; margin-bottom: 0.7rem; }
  .project-desc { color: var(--muted); font-size: 0.88rem; line-height: 1.7; margin-bottom: 1.5rem; }
  .project-tags { display: flex; gap: 0.4rem; flex-wrap: wrap; }
  .ptag {
    font-size: 0.68rem; letter-spacing: 0.08em; text-transform: uppercase;
    color: var(--muted); border: 1px solid var(--border);
    padding: 0.25rem 0.6rem; border-radius: 1px;
  }
  .project-arrow {
    position: absolute; top: 1.5rem; right: 1.5rem;
    color: var(--muted); font-size: 1.1rem;
    transition: transform 0.2s, color 0.2s;
  }
  .project-card:hover .project-arrow { transform: translate(3px,-3px); color: var(--accent); }

  /* ─── CONTACT ─── */
  #contact {
    display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: start;
  }
  .contact-left .big-text {
    font-family: 'Syne', sans-serif; font-weight: 800;
    font-size: clamp(2.5rem, 5vw, 4rem);
    line-height: 1.05; letter-spacing: -0.02em;
    margin: 1.5rem 0;
  }
  .contact-left .big-text em {
    font-style: normal;
    -webkit-text-stroke: 1.5px rgba(240,237,232,0.25);
    color: transparent; display: block;
  }
  .contact-socials { display: flex; flex-direction: column; gap: 0.8rem; margin-top: 2.5rem; }
  .social-link {
    display: flex; align-items: center; gap: 1rem;
    color: var(--muted); text-decoration: none;
    font-size: 0.88rem; letter-spacing: 0.04em;
    padding: 0.9rem 1.2rem;
    border: 1px solid var(--border);
    border-radius: 2px;
    transition: border-color 0.2s, color 0.2s, background 0.2s;
  }
  .social-link:hover { border-color: var(--accent); color: var(--accent); background: rgba(255,59,59,0.04); }
  .social-link .s-icon { font-size: 1rem; min-width: 1.2rem; }
  .social-label { font-family: 'Syne', sans-serif; font-weight: 600; font-size: 0.75rem; letter-spacing: 0.1em; text-transform: uppercase; }
  .social-handle { margin-left: auto; font-size: 0.78rem; opacity: 0.6; }

  .contact-right {}
  .contact-form { display: flex; flex-direction: column; gap: 1.2rem; margin-top: 2rem; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .form-field { display: flex; flex-direction: column; gap: 0.5rem; }
  .form-label { font-size: 0.7rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--muted); }
  .form-input, .form-textarea {
    background: var(--surface); border: 1px solid var(--border);
    color: var(--text); font-family: 'DM Sans', sans-serif; font-size: 0.92rem;
    padding: 0.9rem 1.1rem; border-radius: 2px; outline: none;
    transition: border-color 0.2s; resize: none;
  }
  .form-input:focus, .form-textarea:focus { border-color: var(--accent); }
  .form-textarea { height: 130px; }
  .form-submit {
    background: var(--accent); color: #fff; border: none;
    font-family: 'Syne', sans-serif; font-weight: 700;
    font-size: 0.85rem; letter-spacing: 0.1em; text-transform: uppercase;
    padding: 1rem 2.5rem; border-radius: 2px; cursor: none;
    transition: transform 0.2s, box-shadow 0.2s; align-self: flex-start;
    box-shadow: 0 0 30px rgba(255,59,59,0.25);
  }
  .form-submit:hover { transform: translateY(-2px); box-shadow: 0 0 50px rgba(255,59,59,0.45); }

  /* ─── FOOTER ─── */
  footer {
    padding: 2rem 4rem;
    border-top: 1px solid var(--border);
    display: flex; align-items: center; justify-content: space-between;
  }
  footer .foot-logo {
    font-family: 'Syne', sans-serif; font-weight: 800; font-size: 0.95rem;
    letter-spacing: 0.1em; color: var(--text); text-decoration: none;
  }
  footer .foot-logo span { color: var(--accent); }
  footer p { font-size: 0.75rem; color: var(--muted); }

  /* ─── SCROLL REVEAL ─── */
  .reveal {
    opacity: 0; transform: translateY(40px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* ─── DIVIDER LINE ─── */
  .marquee-wrap {
    overflow: hidden; border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    padding: 1rem 0;
    white-space: nowrap;
  }
  .marquee {
    display: inline-block;
    animation: marquee 18s linear infinite;
    font-family: 'Syne', sans-serif; font-weight: 800;
    font-size: 0.7rem; letter-spacing: 0.3em; text-transform: uppercase;
    color: var(--muted);
  }
  .marquee span { color: var(--accent); margin: 0 1.5rem; }
  @keyframes marquee { from { transform: translateX(0); } to { transform: translateX(-50%); } }

  /* ─── RESPONSIVE ─── */
  @media (max-width: 768px) {
    nav { padding: 1.2rem 1.5rem; }
    .nav-links { display: none; }
    section, #hero { padding: 5rem 1.5rem 3rem; }
    #about .about-grid { grid-template-columns: 1fr; gap: 2rem; }
    .form-row { grid-template-columns: 1fr; }
    #contact { grid-template-columns: 1fr; gap: 3rem; padding: 4rem 1.5rem; }
    footer { padding: 1.5rem; flex-direction: column; gap: 0.5rem; text-align: center; }
    .hero-counter { display: none; }
    .hero-scroll { display: none; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAV -->
<nav>
  <a href="#" class="nav-logo">AT<span>.</span></a>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <div class="nav-social">
    <a href="https://github.com/Aditya1678" target="_blank">GH</a>
    <a href="https://www.linkedin.com/in/aditya-tiwari-61a368406" target="_blank">LI</a>
    <a href="https://instagram.com/adi.tya_tiwari" target="_blank">IG</a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-tag">Hello, I'm</div>
  <h1 class="hero-name">
    ADITYA
    <span class="line2">TIWARI</span>
  </h1>
  <p class="hero-desc">
    Computer Science student at GBU — passionate about building clean, purposeful software & digital experiences. Exploring web development, design, and creative technology.
  </p>
  <div class="hero-btns">
    <a href="#projects" class="btn-primary">View Work ↓</a>
    <a href="#contact" class="btn-outline">Get In Touch →</a>
  </div>
  <div class="hero-scroll">
    <div class="scroll-line"></div>
    Scroll
  </div>
  <div class="hero-counter">
    <div class="counter-item">
      <span class="counter-num">4+</span>
      <div class="counter-label">Languages</div>
    </div>
    <div class="counter-item">
      <span class="counter-num">GBU</span>
      <div class="counter-label">University</div>
    </div>
    <div class="counter-item">
      <span class="counter-num">∞</span>
      <div class="counter-label">Curiosity</div>
    </div>
  </div>
</section>

<!-- MARQUEE -->
<div class="marquee-wrap">
  <div class="marquee">
    ADITYA TIWARI <span>✦</span> GBU CSE <span>✦</span> WEB DEVELOPER <span>✦</span> DIGITAL DESIGNER <span>✦</span> PROBLEM SOLVER <span>✦</span>
    ADITYA TIWARI <span>✦</span> GBU CSE <span>✦</span> WEB DEVELOPER <span>✦</span> DIGITAL DESIGNER <span>✦</span> PROBLEM SOLVER <span>✦</span>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <div class="section-eyebrow">About</div>
  <h2 class="section-title">A little<br>about me.</h2>

  <div class="about-grid reveal">
    <div class="about-text">
      <p>
        I'm <strong>Aditya Tiwari</strong>, a B.Tech student in <span class="accent">Computer Science & Engineering</span> at Gautam Buddha University, Greater Noida.
      </p>
      <p>
        I have a strong interest in <strong>program development</strong>, <strong>web page design</strong>, and <strong>digital content creation</strong>. Over the years I've been learning multiple programming languages and exploring technologies to sharpen my development and problem-solving skills.
      </p>
      <p>
        I thrive at the intersection of creativity and logic — turning ideas into well-crafted, functional products.
      </p>

      <div class="core-skills-label">Core Skills</div>
      <div class="skill-tags">
        <span class="skill-tag">Web Dev</span>
        <span class="skill-tag">Photoshop</span>
        <span class="skill-tag">Digital Design</span>
        <span class="skill-tag">Graphic Design</span>
        <span class="skill-tag">Content Creation</span>
        <span class="skill-tag">Problem Solving</span>
      </div>
    </div>

    <div class="about-aside">
      <div class="stat-card">
        <div class="stat-icon">🎓</div>
        <div class="stat-name">University</div>
        <div class="stat-val">Gautam Buddha University</div>
      </div>
      <div class="stat-card">
        <div class="stat-icon">💻</div>
        <div class="stat-name">Degree</div>
        <div class="stat-val">B.Tech — Computer Science</div>
      </div>
      <div class="stat-card">
        <div class="stat-icon">📍</div>
        <div class="stat-name">Location</div>
        <div class="stat-val">Greater Noida, India</div>
      </div>
      <div class="stat-card">
        <div class="stat-icon">⚡</div>
        <div class="stat-name">Focus</div>
        <div class="stat-val">Dev · Design · Create</div>
      </div>
    </div>
  </div>
</section>

<!-- EDUCATION -->
<section id="education">
  <div class="section-eyebrow">Education</div>
  <h2 class="section-title">Academic<br>Path.</h2>

  <div class="edu-list reveal">
    <div class="edu-card">
      <div class="edu-num">01</div>
      <div>
        <div class="edu-title">Gautam Buddha University</div>
        <div class="edu-sub">Bachelors of Technology — Computer Science & Engineering</div>
        <div class="edu-loc">📍 Greater Noida, India</div>
      </div>
      <span class="edu-badge badge-ongoing">Ongoing</span>
    </div>
    <div class="edu-card">
      <div class="edu-num">02</div>
      <div>
        <div class="edu-title">Shri Ram Global School</div>
        <div class="edu-sub">Higher Secondary School — Mathematics & Computer Science</div>
        <div class="edu-loc">📍 Greater Noida West, India</div>
      </div>
      <span class="edu-badge badge-done">Completed</span>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-eyebrow">Expertise</div>
  <h2 class="section-title">Core<br>Learning.</h2>

  <div class="skills-tabs">
    <button class="tab-btn active" onclick="switchTab(this,'languages')">Languages</button>
    <button class="tab-btn" onclick="switchTab(this,'webdev')">Web Dev</button>
    <button class="tab-btn" onclick="switchTab(this,'tools')">Tools</button>
  </div>

  <div id="languages" class="tab-panel active">
    <div class="skills-grid">
      <div class="skill-item"><span class="skill-icon">◎</span><div class="skill-name">C</div></div>
      <div class="skill-item"><span class="skill-icon">◎</span><div class="skill-name">C++</div></div>
      <div class="skill-item"><span class="skill-icon">◎</span><div class="skill-name">Python</div></div>
      <div class="skill-item"><span class="skill-icon">◎</span><div class="skill-name">Java</div></div>
      <div class="skill-item"><span class="skill-icon">◎</span><div class="skill-name">PHP</div></div>
      <div class="skill-item"><span class="skill-icon">◎</span><div class="skill-name">JavaScript</div></div>
    </div>
  </div>

  <div id="webdev" class="tab-panel">
    <div class="skills-grid">
      <div class="skill-item"><span class="skill-icon">◈</span><div class="skill-name">HTML5</div></div>
      <div class="skill-item"><span class="skill-icon">◈</span><div class="skill-name">CSS3</div></div>
      <div class="skill-item"><span class="skill-icon">◈</span><div class="skill-name">JavaScript</div></div>
      <div class="skill-item"><span class="skill-icon">◈</span><div class="skill-name">Responsive Design</div></div>
    </div>
  </div>

  <div id="tools" class="tab-panel">
    <div class="skills-grid">
      <div class="skill-item"><span class="skill-icon">◇</span><div class="skill-name">Photoshop</div></div>
      <div class="skill-item"><span class="skill-icon">◇</span><div class="skill-name">Graphic Design</div></div>
      <div class="skill-item"><span class="skill-icon">◇</span><div class="skill-name">Video Editing</div></div>
      <div class="skill-item"><span class="skill-icon">◇</span><div class="skill-name">Git / GitHub</div></div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="section-eyebrow">Work</div>
  <h2 class="section-title">Projects &<br>Creations.</h2>

  <div class="projects-grid reveal">
    <div class="project-card">
      <div class="project-num">01 — Featured</div>
      <div class="project-title">Content Creation</div>
      <div class="project-desc">Creative digital content created and shared on Instagram. A blend of design and storytelling for an engaging audience.</div>
      <div class="project-tags">
        <span class="ptag">Design</span>
        <span class="ptag">Social</span>
        <span class="ptag">Creative</span>
      </div>
      <a href="https://instagram.com/adi.tya_tiwari" target="_blank" class="project-arrow">↗</a>
    </div>
    <div class="project-card">
      <div class="project-num">02 — Dev</div>
      <div class="project-title">Web Projects</div>
      <div class="project-desc">A collection of web development experiments, applications, and open-source contributions available on GitHub.</div>
      <div class="project-tags">
        <span class="ptag">HTML/CSS</span>
        <span class="ptag">JS</span>
        <span class="ptag">GitHub</span>
      </div>
      <a href="https://github.com/Aditya1678" target="_blank" class="project-arrow">↗</a>
    </div>
    <div class="project-card">
      <div class="project-num">03 — Design</div>
      <div class="project-title">Graphic & Visual Work</div>
      <div class="project-desc">Explorations in digital design and Photoshop — crafting visuals that communicate with clarity and impact.</div>
      <div class="project-tags">
        <span class="ptag">Photoshop</span>
        <span class="ptag">Visual</span>
        <span class="ptag">Branding</span>
      </div>
      <a href="https://instagram.com/adi.tya_tiwari" target="_blank" class="project-arrow">↗</a>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div>
    <div class="section-eyebrow">Contact</div>
    <div class="big-text reveal">
      Let's<br><em>Connect.</em>
    </div>
    <p class="section-subtitle">Have a project in mind or just want to say hello? I'd love to hear from you.</p>

    <div class="contact-socials reveal">
      <a href="https://github.com/Aditya1678" target="_blank" class="social-link">
        <span class="s-icon">⌥</span>
        <span class="social-label">GitHub</span>
        <span class="social-handle">Aditya1678</span>
      </a>
      <a href="https://www.linkedin.com/in/aditya-tiwari-61a368406" target="_blank" class="social-link">
        <span class="s-icon">◈</span>
        <span class="social-label">LinkedIn</span>
        <span class="social-handle">aditya-tiwari</span>
      </a>
      <a href="https://instagram.com/adi.tya_tiwari" target="_blank" class="social-link">
        <span class="s-icon">◎</span>
        <span class="social-label">Instagram</span>
        <span class="social-handle">adi.tya_tiwari</span>
      </a>
    </div>
  </div>

  <div class="reveal">
    <div class="section-eyebrow" style="margin-top:0">Send a message</div>
    <form class="contact-form" onsubmit="handleSubmit(event)">
      <div class="form-row">
        <div class="form-field">
          <label class="form-label">Your Name</label>
          <input type="text" class="form-input" placeholder="John Doe" required>
        </div>
        <div class="form-field">
          <label class="form-label">Email</label>
          <input type="email" class="form-input" placeholder="john@email.com" required>
        </div>
      </div>
      <div class="form-field">
        <label class="form-label">Message</label>
        <textarea class="form-textarea" placeholder="What's on your mind..." required></textarea>
      </div>
      <button type="submit" class="form-submit">Send Message →</button>
    </form>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <a href="#" class="foot-logo">AT<span>.</span></a>
  <p>© 2024 Aditya Tiwari — GBU, Computer Science</p>
  <p style="font-size:0.7rem; color:var(--muted)">Greater Noida, India</p>
</footer>

<script>
  // Cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.transform = `translate(${mx - 6}px, ${my - 6}px)`;
  });
  function animRing() {
    rx += (mx - rx) * 0.12;
    ry += (my - ry) * 0.12;
    ring.style.transform = `translate(${rx - 18}px, ${ry - 18}px)`;
    requestAnimationFrame(animRing);
  }
  animRing();

  document.querySelectorAll('a, button').forEach(el => {
    el.addEventListener('mouseenter', () => {
      cursor.style.transform += ' scale(1.8)';
      ring.style.width = '52px'; ring.style.height = '52px';
    });
    el.addEventListener('mouseleave', () => {
      ring.style.width = '36px'; ring.style.height = '36px';
    });
  });

  // Tabs
  function switchTab(btn, id) {
    document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
    document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
    btn.classList.add('active');
    document.getElementById(id).classList.add('active');
  }

  // Scroll reveal
  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
  }, { threshold: 0.12 });
  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

  // Form
  function handleSubmit(e) {
    e.preventDefault();
    const btn = e.target.querySelector('.form-submit');
    btn.textContent = 'Message Sent ✓';
    btn.style.background = '#22c55e';
    setTimeout(() => { btn.textContent = 'Send Message →'; btn.style.background = ''; e.target.reset(); }, 3000);
  }
</script>
</body>
</html>
