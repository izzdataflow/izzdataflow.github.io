<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Naufal Izzudin — Data Analyst Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=DM+Mono:wght@300;400;500&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg:       #0e0e0e;
    --surface:  #161616;
    --card:     #1a1a1a;
    --border:   #2a2a2a;
    --amber:    #f0a500;
    --amber-dim:#7a5200;
    --text:     #e8e2d9;
    --muted:    #6b6560;
    --light:    #b0a99e;
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    font-weight: 300;
    line-height: 1.6;
    cursor: none;
  }

  /* Custom cursor */
  .cursor {
    position: fixed;
    width: 10px; height: 10px;
    background: var(--amber);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transform: translate(-50%, -50%);
    transition: transform 0.1s, width 0.2s, height 0.2s;
  }
  .cursor-ring {
    position: fixed;
    width: 36px; height: 36px;
    border: 1px solid rgba(240,165,0,0.4);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transform: translate(-50%, -50%);
    transition: transform 0.15s ease, width 0.3s, height 0.3s, border-color 0.3s;
  }
  body:has(a:hover) .cursor-ring,
  body:has(button:hover) .cursor-ring { width: 56px; height: 56px; border-color: var(--amber); }

  /* Grain overlay */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
    opacity: 0.5;
  }

  /* Nav */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 48px;
    background: rgba(14,14,14,0.85);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
  }

  .nav-logo {
    font-family: 'DM Mono', monospace;
    font-size: 13px;
    color: var(--amber);
    letter-spacing: 0.15em;
    text-decoration: none;
  }

  .nav-links {
    display: flex;
    gap: 36px;
    list-style: none;
  }

  .nav-links a {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    text-decoration: none;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--text); }

  /* Hero */
  .hero {
    position: relative;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 120px 48px 80px;
    overflow: hidden;
  }

  .hero-bg-line {
    position: absolute;
    right: -100px;
    top: 50%;
    transform: translateY(-50%);
    font-family: 'Playfair Display', serif;
    font-size: clamp(200px, 22vw, 340px);
    font-weight: 900;
    color: transparent;
    -webkit-text-stroke: 1px rgba(240,165,0,0.06);
    line-height: 1;
    pointer-events: none;
    user-select: none;
    white-space: nowrap;
  }

  .hero-tag {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--amber);
    margin-bottom: 24px;
    display: flex;
    align-items: center;
    gap: 12px;
    animation: fadeUp 0.8s ease both;
  }
  .hero-tag::before {
    content: '';
    width: 32px;
    height: 1px;
    background: var(--amber);
  }

  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(52px, 8vw, 110px);
    font-weight: 900;
    line-height: 0.95;
    letter-spacing: -0.02em;
    margin-bottom: 32px;
    animation: fadeUp 0.8s 0.1s ease both;
  }

  .hero h1 span { color: var(--amber); }

  .hero-desc {
    max-width: 520px;
    font-size: 16px;
    color: var(--light);
    line-height: 1.8;
    margin-bottom: 48px;
    animation: fadeUp 0.8s 0.2s ease both;
  }

  .hero-stats {
    display: flex;
    gap: 48px;
    margin-bottom: 48px;
    animation: fadeUp 0.8s 0.3s ease both;
  }

  .stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 36px;
    font-weight: 700;
    color: var(--amber);
    line-height: 1;
  }
  .stat-label {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    margin-top: 4px;
  }

  .hero-actions {
    display: flex;
    gap: 16px;
    animation: fadeUp 0.8s 0.4s ease both;
  }

  .btn-primary {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 14px 28px;
    background: var(--amber);
    color: #0e0e0e;
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    text-decoration: none;
    border: none;
    cursor: none;
    transition: background 0.2s, transform 0.2s;
  }
  .btn-primary:hover { background: #ffc130; transform: translateY(-2px); }

  .btn-ghost {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 14px 28px;
    background: transparent;
    color: var(--light);
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    text-decoration: none;
    border: 1px solid var(--border);
    cursor: none;
    transition: border-color 0.2s, color 0.2s, transform 0.2s;
  }
  .btn-ghost:hover { border-color: var(--amber); color: var(--amber); transform: translateY(-2px); }

  /* Skills bar */
  .skills-bar {
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    padding: 20px 48px;
    display: flex;
    gap: 40px;
    overflow-x: auto;
    scrollbar-width: none;
  }
  .skills-bar::-webkit-scrollbar { display: none; }

  .skill-pill {
    display: flex;
    align-items: center;
    gap: 8px;
    white-space: nowrap;
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--muted);
  }
  .skill-dot {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--amber);
    opacity: 0.6;
  }

  /* Section */
  section {
    position: relative;
    z-index: 1;
    padding: 100px 48px;
  }

  .section-header {
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    margin-bottom: 60px;
    gap: 24px;
    flex-wrap: wrap;
  }

  .section-label {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--amber);
    margin-bottom: 12px;
  }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(32px, 4vw, 52px);
    font-weight: 700;
    line-height: 1.1;
    letter-spacing: -0.02em;
  }

  /* Filter tabs */
  .filter-tabs {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .filter-btn {
    padding: 8px 18px;
    background: transparent;
    border: 1px solid var(--border);
    color: var(--muted);
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    cursor: none;
    transition: all 0.2s;
  }
  .filter-btn:hover { border-color: var(--amber-dim); color: var(--light); }
  .filter-btn.active { background: var(--amber); border-color: var(--amber); color: #0e0e0e; }

  /* Project grid */
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
    gap: 2px;
  }

  .project-card {
    background: var(--card);
    border: 1px solid var(--border);
    padding: 32px;
    text-decoration: none;
    color: inherit;
    display: flex;
    flex-direction: column;
    gap: 16px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
    animation: fadeIn 0.5s ease both;
  }

  .project-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: var(--amber);
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.3s ease;
  }

  .project-card:hover { border-color: rgba(240,165,0,0.3); transform: translateY(-4px); }
  .project-card:hover::before { transform: scaleX(1); }

  .card-top {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 12px;
  }

  .card-icon {
    width: 40px; height: 40px;
    border: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    flex-shrink: 0;
    background: var(--surface);
  }

  .card-arrow {
    font-size: 18px;
    color: var(--muted);
    transition: color 0.2s, transform 0.2s;
    flex-shrink: 0;
  }
  .project-card:hover .card-arrow { color: var(--amber); transform: translate(3px, -3px); }

  .card-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }

  .tag {
    font-family: 'DM Mono', monospace;
    font-size: 9px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 3px 8px;
    border: 1px solid var(--border);
    color: var(--muted);
  }

  .tag.highlight {
    border-color: var(--amber-dim);
    color: var(--amber);
  }

  .card-title {
    font-family: 'Playfair Display', serif;
    font-size: 20px;
    font-weight: 700;
    line-height: 1.3;
    color: var(--text);
  }

  .card-desc {
    font-size: 13px;
    color: var(--muted);
    line-height: 1.7;
    flex: 1;
  }

  .card-meta {
    display: flex;
    align-items: center;
    gap: 12px;
    padding-top: 16px;
    border-top: 1px solid var(--border);
  }

  .meta-cat {
    font-family: 'DM Mono', monospace;
    font-size: 9px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
  }

  /* hidden class */
  .project-card.hidden { display: none; }

  /* About section */
  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: start;
  }

  .about-text p {
    font-size: 15px;
    color: var(--light);
    line-height: 1.9;
    margin-bottom: 20px;
  }

  .about-text p strong { color: var(--amber); font-weight: 500; }

  .about-stack h3 {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--amber);
    margin-bottom: 24px;
  }

  .stack-group {
    margin-bottom: 28px;
  }

  .stack-group-label {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 10px;
  }

  .stack-items {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .stack-item {
    padding: 6px 14px;
    border: 1px solid var(--border);
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    color: var(--light);
    letter-spacing: 0.05em;
  }

  /* Contact */
  .contact-section {
    background: var(--surface);
    border-top: 1px solid var(--border);
    text-align: center;
  }

  .contact-section .section-title { margin-bottom: 16px; }

  .contact-desc {
    font-size: 15px;
    color: var(--muted);
    margin-bottom: 40px;
    max-width: 480px;
    margin-left: auto;
    margin-right: auto;
  }

  .contact-links {
    display: flex;
    justify-content: center;
    gap: 16px;
    flex-wrap: wrap;
  }

  /* Footer */
  footer {
    padding: 28px 48px;
    border-top: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 12px;
  }

  footer p {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.1em;
    color: var(--muted);
  }

  footer span { color: var(--amber); }

  /* Divider */
  .divider {
    height: 1px;
    background: var(--border);
    margin: 0 48px;
  }

  /* Animations */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  @keyframes fadeIn {
    from { opacity: 0; }
    to   { opacity: 1; }
  }

  /* Scroll reveal */
  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* Responsive */
  @media (max-width: 768px) {
    nav { padding: 16px 24px; }
    .hero { padding: 100px 24px 60px; }
    section { padding: 70px 24px; }
    .skills-bar { padding: 20px 24px; }
    .about-grid { grid-template-columns: 1fr; gap: 48px; }
    .hero-stats { gap: 28px; }
    .hero-bg-line { font-size: 120px; }
    .project-grid { grid-template-columns: 1fr; }
    footer { padding: 24px; }
    .divider { margin: 0 24px; }
    .nav-links { display: none; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- Nav -->
<nav>
  <a href="#" class="nav-logo">izzdataflow</a>
  <ul class="nav-links">
    <li><a href="#projects">Projects</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- Hero -->
<section class="hero">
  <div class="hero-bg-line">DATA</div>
  <div class="hero-tag">Available for opportunities</div>
  <h1>Naufal<br><span>Izzudin</span></h1>
  <p class="hero-desc">
    Data Analyst specializing in turning raw, messy data into clear decisions. 
    Working across SQL, Python, Excel, and BI tools to build end-to-end pipelines — 
    from database migrations to live dashboards.
  </p>
  <div class="hero-stats">
    <div>
      <div class="stat-num">16</div>
      <div class="stat-label">Projects</div>
    </div>
    <div>
      <div class="stat-num">6</div>
      <div class="stat-label">Tools</div>
    </div>
    <div>
      <div class="stat-num">4</div>
      <div class="stat-label">Domains</div>
    </div>
  </div>
  <div class="hero-actions">
    <a href="#projects" class="btn-primary">View Projects ↓</a>
    <a href="https://github.com/izzdataflow" target="_blank" class="btn-ghost">GitHub →</a>
  </div>
</section>

<!-- Skills bar -->
<div class="skills-bar">
  <div class="skill-pill"><span class="skill-dot"></span>SQL Server & PostgreSQL</div>
  <div class="skill-pill"><span class="skill-dot"></span>Python & Pandas</div>
  <div class="skill-pill"><span class="skill-dot"></span>Power BI</div>
  <div class="skill-pill"><span class="skill-dot"></span>Tableau</div>
  <div class="skill-pill"><span class="skill-dot"></span>Microsoft Excel</div>
  <div class="skill-pill"><span class="skill-dot"></span>REST APIs</div>
  <div class="skill-pill"><span class="skill-dot"></span>Web Scraping</div>
  <div class="skill-pill"><span class="skill-dot"></span>Data Cleaning & EDA</div>
  <div class="skill-pill"><span class="skill-dot"></span>ETL Pipelines</div>
</div>

<!-- Projects -->
<section id="projects">
  <div class="section-header reveal">
    <div>
      <div class="section-label">// work</div>
      <h2 class="section-title">Projects</h2>
    </div>
    <div class="filter-tabs">
      <button class="filter-btn active" data-filter="all">All</button>
      <button class="filter-btn" data-filter="sql">SQL</button>
      <button class="filter-btn" data-filter="python">Python</button>
      <button class="filter-btn" data-filter="excel">Excel</button>
      <button class="filter-btn" data-filter="bi">BI Tools</button>
    </div>
  </div>

  <div class="project-grid" id="projectGrid">

    <!-- SQL -->
    <a href="https://github.com/izzdataflow/sql-server-to-postgres-migration" target="_blank"
       class="project-card" data-cat="sql">
      <div class="card-top">
        <div class="card-icon">🗄️</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">SQL Server</span>
        <span class="tag highlight">PostgreSQL</span>
        <span class="tag">Migration</span>
        <span class="tag">ETL</span>
      </div>
      <div class="card-title">SQL Server → PostgreSQL Migration</div>
      <div class="card-desc">Full database migration pipeline — schema conversion, data type mapping, and validation between SQL Server and PostgreSQL environments.</div>
      <div class="card-meta"><span class="meta-cat">SQL · Database Engineering</span></div>
    </a>

    <a href="https://github.com/izzdataflow/mysql-datacleaning-eda" target="_blank"
       class="project-card" data-cat="sql">
      <div class="card-top">
        <div class="card-icon">🔍</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">MySQL</span>
        <span class="tag">Data Cleaning</span>
        <span class="tag">EDA</span>
      </div>
      <div class="card-title">MySQL Data Cleaning & EDA</div>
      <div class="card-desc">End-to-end data cleaning and exploratory analysis in MySQL — handling nulls, deduplication, standardization, and trend discovery through SQL queries.</div>
      <div class="card-meta"><span class="meta-cat">SQL · Data Cleaning</span></div>
    </a>

    <a href="https://github.com/izzdataflow/EPL-Standings-2024-25" target="_blank"
       class="project-card" data-cat="sql">
      <div class="card-top">
        <div class="card-icon">⚽</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">REST API</span>
        <span class="tag highlight">MySQL</span>
        <span class="tag">Sports Data</span>
      </div>
      <div class="card-title">EPL Standings 2024–25</div>
      <div class="card-desc">Live Premier League standings pulled from a REST API and stored in MySQL. Automated data ingestion pipeline with structured querying for match statistics.</div>
      <div class="card-meta"><span class="meta-cat">SQL · API Integration</span></div>
    </a>

    <!-- Python -->
    <a href="https://github.com/izzdataflow/python-learning-journey" target="_blank"
       class="project-card" data-cat="python">
      <div class="card-top">
        <div class="card-icon">🐍</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Python</span>
        <span class="tag">Fundamentals</span>
        <span class="tag">Reference</span>
      </div>
      <div class="card-title">Python Learning Journey</div>
      <div class="card-desc">Structured Python reference from variables to web scraping — covering data types, loops, functions, file automation, BeautifulSoup, and requests with working examples throughout.</div>
      <div class="card-meta"><span class="meta-cat">Python · Self-Learning</span></div>
    </a>

    <a href="https://github.com/izzdataflow/pandas-learning-journey" target="_blank"
       class="project-card" data-cat="python">
      <div class="card-top">
        <div class="card-icon">🐼</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Python</span>
        <span class="tag highlight">Pandas</span>
        <span class="tag">EDA</span>
        <span class="tag">Visualization</span>
      </div>
      <div class="card-title">Pandas Learning Journey</div>
      <div class="card-desc">Complete Pandas reference — reading files, filtering, indexing, groupby, merging, data cleaning, EDA, and visualization with Matplotlib and Seaborn.</div>
      <div class="card-meta"><span class="meta-cat">Python · Data Analysis</span></div>
    </a>

    <a href="https://github.com/izzdataflow/python-webscraping-wikipedia" target="_blank"
       class="project-card" data-cat="python">
      <div class="card-top">
        <div class="card-icon">🌐</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">BeautifulSoup</span>
        <span class="tag highlight">Requests</span>
        <span class="tag">Web Scraping</span>
        <span class="tag">CSV</span>
      </div>
      <div class="card-title">Web Scraping — Wikipedia</div>
      <div class="card-desc">Scrapes the largest US companies by revenue from Wikipedia, parses HTML tables using BeautifulSoup, and exports structured data to CSV via Pandas.</div>
      <div class="card-meta"><span class="meta-cat">Python · Web Scraping</span></div>
    </a>

    <a href="https://github.com/izzdataflow/python-webscraping-amazon" target="_blank"
       class="project-card" data-cat="python">
      <div class="card-top">
        <div class="card-icon">📦</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">BeautifulSoup</span>
        <span class="tag">Automation</span>
        <span class="tag">Email Alert</span>
        <span class="tag">CSV</span>
      </div>
      <div class="card-title">Amazon Price Tracker</div>
      <div class="card-desc">Automated price tracker that scrapes Amazon product pages on a schedule, logs readings with timestamps to CSV, and triggers an email alert when the price drops below a threshold.</div>
      <div class="card-meta"><span class="meta-cat">Python · Automation</span></div>
    </a>

    <!-- Excel -->
    <a href="https://github.com/izzdataflow/excel-formula-mastery" target="_blank"
       class="project-card" data-cat="excel">
      <div class="card-top">
        <div class="card-icon">📐</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Excel</span>
        <span class="tag">XLOOKUP</span>
        <span class="tag">SUMPRODUCT</span>
        <span class="tag">Reference</span>
      </div>
      <div class="card-title">Excel Formula Mastery</div>
      <div class="card-desc">Progressive formula reference from basic to expert level — covering XLOOKUP, INDEX/MATCH, SUMIFS, dynamic arrays, proration logic, and SUMPRODUCT revenue modeling.</div>
      <div class="card-meta"><span class="meta-cat">Excel · Formulas</span></div>
    </a>

    <a href="https://github.com/izzdataflow/excel-bikebuyers-report" target="_blank"
       class="project-card" data-cat="excel">
      <div class="card-top">
        <div class="card-icon">🚲</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Excel</span>
        <span class="tag">Dashboard</span>
        <span class="tag">Pivot Tables</span>
      </div>
      <div class="card-title">Bike Buyers Report</div>
      <div class="card-desc">Interactive Excel dashboard analyzing bike purchasing behavior across demographics — built with pivot tables, slicers, and dynamic charts for drill-down exploration.</div>
      <div class="card-meta"><span class="meta-cat">Excel · Dashboard</span></div>
    </a>

    <a href="https://github.com/izzdataflow/excel-event-report" target="_blank"
       class="project-card" data-cat="excel">
      <div class="card-top">
        <div class="card-icon">📅</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Excel</span>
        <span class="tag">Reporting</span>
        <span class="tag">Data Cleaning</span>
      </div>
      <div class="card-title">Event Report</div>
      <div class="card-desc">Event performance report built in Excel — data cleaned, summarized, and formatted for stakeholder-ready presentation with key attendance and revenue metrics.</div>
      <div class="card-meta"><span class="meta-cat">Excel · Reporting</span></div>
    </a>

    <a href="https://github.com/izzdataflow/excel-campaign-report" target="_blank"
       class="project-card" data-cat="excel">
      <div class="card-top">
        <div class="card-icon">📢</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Excel</span>
        <span class="tag">Marketing</span>
        <span class="tag">KPI Tracking</span>
      </div>
      <div class="card-title">Campaign Report</div>
      <div class="card-desc">Marketing campaign performance tracker in Excel — measuring reach, conversions, and ROI across channels with automated KPI calculations and visual summaries.</div>
      <div class="card-meta"><span class="meta-cat">Excel · Marketing Analytics</span></div>
    </a>

    <a href="https://github.com/izzdataflow/excel-powerpivot-dashboard" target="_blank"
       class="project-card" data-cat="excel">
      <div class="card-top">
        <div class="card-icon">⚡</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Excel</span>
        <span class="tag highlight">Power Pivot</span>
        <span class="tag">DAX</span>
        <span class="tag">Data Model</span>
      </div>
      <div class="card-title">Power Pivot Dashboard</div>
      <div class="card-desc">Multi-table data model built with Power Pivot and DAX measures — enabling cross-table analysis and calculated KPIs that go beyond standard pivot table capabilities.</div>
      <div class="card-meta"><span class="meta-cat">Excel · Power Pivot</span></div>
    </a>

    <!-- BI Tools -->
    <a href="https://github.com/izzdataflow/top-10-uk-youtubers-2025" target="_blank"
       class="project-card" data-cat="bi">
      <div class="card-top">
        <div class="card-icon">📊</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Excel</span>
        <span class="tag highlight">SQL Server</span>
        <span class="tag highlight">Power BI</span>
        <span class="tag">YouTube Data</span>
      </div>
      <div class="card-title">Top 10 UK YouTubers 2025</div>
      <div class="card-desc">End-to-end analytics project — data sourced via API, cleaned in Excel, stored in SQL Server, and visualized in Power BI to surface top UK creators by engagement metrics.</div>
      <div class="card-meta"><span class="meta-cat">Power BI · Full Pipeline</span></div>
    </a>

    <a href="https://github.com/izzdataflow/powerbi-survey-report" target="_blank"
       class="project-card" data-cat="bi">
      <div class="card-top">
        <div class="card-icon">📋</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Power BI</span>
        <span class="tag">Power Query</span>
        <span class="tag">Survey Data</span>
      </div>
      <div class="card-title">Data Professional Survey Report</div>
      <div class="card-desc">Power BI dashboard analyzing a 630-person data professional survey — covering salary by role, favorite languages, work-life balance scores, and difficulty breaking into data.</div>
      <div class="card-meta"><span class="meta-cat">Power BI · Survey Analytics</span></div>
    </a>

    <a href="https://github.com/izzdataflow/tableau-excel-deloitte" target="_blank"
       class="project-card" data-cat="bi">
      <div class="card-top">
        <div class="card-icon">🏢</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Tableau</span>
        <span class="tag highlight">Excel</span>
        <span class="tag">Case Study</span>
      </div>
      <div class="card-title">Deloitte Case Study — Tableau & Excel</div>
      <div class="card-desc">Deloitte-style business case study with Excel analysis and Tableau visualization — presenting findings on operational data with consultant-grade dashboard design.</div>
      <div class="card-meta"><span class="meta-cat">Tableau · Business Analytics</span></div>
    </a>

    <a href="https://github.com/izzdataflow/tableau-airbnb" target="_blank"
       class="project-card" data-cat="bi">
      <div class="card-top">
        <div class="card-icon">🏠</div>
        <span class="card-arrow">↗</span>
      </div>
      <div class="card-tags">
        <span class="tag highlight">Tableau</span>
        <span class="tag">Real Estate</span>
        <span class="tag">Geospatial</span>
        <span class="tag">Pricing</span>
      </div>
      <div class="card-title">Airbnb Market Analysis — Tableau</div>
      <div class="card-desc">Tableau dashboard exploring Airbnb listing prices, availability, and revenue trends across neighborhoods — with geospatial maps and seasonal trend breakdowns.</div>
      <div class="card-meta"><span class="meta-cat">Tableau · Market Analysis</span></div>
    </a>

  </div>
</section>

<div class="divider"></div>

<!-- About -->
<section id="about">
  <div class="section-header reveal">
    <div>
      <div class="section-label">// about</div>
      <h2 class="section-title">Background</h2>
    </div>
  </div>
  <div class="about-grid">
    <div class="about-text reveal">
      <p>I'm a <strong>Data Analyst</strong> who builds things end-to-end — from writing the SQL that cleans and structures raw data, to the Power BI dashboard a manager actually uses to make decisions.</p>
      <p>My work spans the full data stack: <strong>database engineering</strong> (migrations, schema design, ETL), <strong>Python automation</strong> (scraping, API pipelines, scheduled jobs), <strong>Excel modeling</strong> (advanced formulas, Power Pivot, DAX), and <strong>BI visualization</strong> (Tableau, Power BI).</p>
      <p>Every project in this portfolio was built from scratch as part of a self-directed learning journey — no shortcuts, no templates. Each one taught a specific skill that I carry into the next.</p>
    </div>
    <div class="about-stack reveal">
      <h3>// Tech Stack</h3>
      <div class="stack-group">
        <div class="stack-group-label">Databases</div>
        <div class="stack-items">
          <span class="stack-item">SQL Server</span>
          <span class="stack-item">PostgreSQL</span>
          <span class="stack-item">MySQL</span>
        </div>
      </div>
      <div class="stack-group">
        <div class="stack-group-label">Python</div>
        <div class="stack-items">
          <span class="stack-item">Pandas</span>
          <span class="stack-item">BeautifulSoup</span>
          <span class="stack-item">Requests</span>
          <span class="stack-item">Seaborn</span>
          <span class="stack-item">Matplotlib</span>
        </div>
      </div>
      <div class="stack-group">
        <div class="stack-group-label">BI & Visualization</div>
        <div class="stack-items">
          <span class="stack-item">Power BI</span>
          <span class="stack-item">Tableau</span>
          <span class="stack-item">Power Query</span>
          <span class="stack-item">DAX</span>
        </div>
      </div>
      <div class="stack-group">
        <div class="stack-group-label">Excel</div>
        <div class="stack-items">
          <span class="stack-item">XLOOKUP</span>
          <span class="stack-item">Power Pivot</span>
          <span class="stack-item">Advanced Formulas</span>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- Contact -->
<section id="contact" class="contact-section">
  <div class="section-label">// contact</div>
  <h2 class="section-title reveal">Let's Work Together</h2>
  <p class="contact-desc reveal">Open to data analyst roles, freelance projects, and collaborations. Feel free to reach out.</p>
  <div class="contact-links reveal">
    <a href="https://github.com/izzdataflow" target="_blank" class="btn-primary">GitHub →</a>
    <a href="mailto:naufalizzudin36@gmail.com" class="btn-ghost">Email ↗</a>
  </div>
</section>

<!-- Footer -->
<footer>
  <p>© 2025 <span>Naufal Izzudin</span> — izzdataflow</p>
  <p>Built with <span>♥</span> and raw HTML</p>
</footer>

<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;

  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.left = mx + 'px';
    cursor.style.top  = my + 'px';
  });

  function animateRing() {
    rx += (mx - rx) * 0.12;
    ry += (my - ry) * 0.12;
    ring.style.left = rx + 'px';
    ring.style.top  = ry + 'px';
    requestAnimationFrame(animateRing);
  }
  animateRing();

  // Filter
  const filterBtns = document.querySelectorAll('.filter-btn');
  const cards = document.querySelectorAll('.project-card');

  filterBtns.forEach(btn => {
    btn.addEventListener('click', () => {
      filterBtns.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      const filter = btn.dataset.filter;
      cards.forEach((card, i) => {
        const show = filter === 'all' || card.dataset.cat === filter;
        card.classList.toggle('hidden', !show);
        if (show) {
          card.style.animationDelay = (i * 0.04) + 's';
          card.style.animation = 'none';
          card.offsetHeight;
          card.style.animation = '';
        }
      });
    });
  });

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.classList.add('visible');
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));
</script>
</body>
</html>
