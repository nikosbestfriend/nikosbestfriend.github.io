<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Christen Black</title>
  <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,600;1,400&family=Source+Sans+3:wght@300;400;600&display=swap" rel="stylesheet"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    :root {
      --navy: #1a2744;
      --gold: #b8903a;
      --cream: #faf8f4;
      --text: #2c2c2c;
      --muted: #6b6b6b;
      --border: #ddd8ce;
      --sidebar-w: 260px;
    }
    body { font-family: 'Source Sans 3', sans-serif; background: var(--cream); color: var(--text); min-height: 100vh; }
    nav { background: var(--navy); display: flex; align-items: center; padding: 0 2rem; position: sticky; top: 0; z-index: 100; box-shadow: 0 2px 12px rgba(0,0,0,0.18); flex-wrap: wrap; }
    nav .brand { font-family: 'Lora', serif; font-size: 1.1rem; color: #fff; text-decoration: none; padding: 1rem 1.5rem 1rem 0; margin-right: 1rem; border-right: 1px solid rgba(255,255,255,0.15); white-space: nowrap; }
    nav a { color: rgba(255,255,255,0.75); text-decoration: none; font-size: 0.88rem; font-weight: 400; letter-spacing: 0.03em; padding: 1.1rem 0.9rem; transition: color 0.2s; text-transform: uppercase; }
    nav a:hover { color: var(--gold); }
    .page { display: flex; max-width: 1000px; margin: 0 auto; padding: 3rem 1.5rem; gap: 3rem; align-items: flex-start; }
    aside { width: var(--sidebar-w); flex-shrink: 0; position: sticky; top: 80px; text-align: center; }
    .photo-wrap { width: 180px; height: 180px; border-radius: 50%; overflow: hidden; margin: 0 auto 1.25rem; border: 3px solid var(--gold); background: #c8bfb0; display: flex; align-items: center; justify-content: center; }
    .photo-wrap img { width: 100%; height: 100%; object-fit: cover; }
    .photo-placeholder { font-size: 3.5rem; color: rgba(255,255,255,0.6); }
    aside .contact-list { list-style: none; margin-top: 1rem; text-align: left; }
    aside .contact-list li { display: flex; align-items: center; gap: 0.5rem; font-size: 0.85rem; color: var(--muted); margin-bottom: 0.6rem; }
    aside .contact-list a { color: var(--navy); text-decoration: none; font-weight: 600; transition: color 0.2s; }
    aside .contact-list a:hover { color: var(--gold); }
    .icon { width: 16px; height: 16px; flex-shrink: 0; opacity: 0.55; }
    main { flex: 1; min-width: 0; }
    main h1 { font-family: 'Lora', serif; font-size: 2.2rem; font-weight: 600; color: var(--navy); margin-bottom: 0.3rem; line-height: 1.2; }
    .subtitle { font-size: 1rem; color: var(--gold); font-weight: 600; letter-spacing: 0.02em; margin-bottom: 1.75rem; }
    .divider { width: 48px; height: 3px; background: var(--gold); margin-bottom: 1.75rem; border-radius: 2px; }
    .bio { font-size: 1rem; line-height: 1.8; color: var(--text); margin-bottom: 2rem; }
    .section { margin-bottom: 2.5rem; }
    .section h2 { font-family: 'Lora', serif; font-size: 1.15rem; color: var(--navy); margin-bottom: 1rem; padding-bottom: 0.4rem; border-bottom: 1px solid var(--border); }
    .bullet-list { list-style: none; padding: 0; }
    .bullet-list li { font-size: 0.95rem; color: var(--text); line-height: 1.7; padding: 0.35rem 0 0.35rem 1.1rem; position: relative; }
    .bullet-list li::before { content: '▸'; position: absolute; left: 0; color: var(--gold); font-size: 0.75rem; top: 0.55rem; }
    .research-item { margin-bottom: 1.4rem; padding-bottom: 1.4rem; border-bottom: 1px solid var(--border); }
    .research-item:last-child { border-bottom: none; margin-bottom: 0; padding-bottom: 0; }
    .research-item h3 { font-family: 'Lora', serif; font-style: italic; font-size: 1rem; color: var(--navy); margin-bottom: 0.4rem; }
    .research-item p { font-size: 0.9rem; color: var(--muted); line-height: 1.65; }
    .cv-btn { display: inline-flex; align-items: center; gap: 0.4rem; background: var(--navy); color: #fff; text-decoration: none; font-size: 0.85rem; font-weight: 600; padding: 0.55rem 1.1rem; border-radius: 4px; transition: background 0.2s; margin-top: 0.5rem; }
    .cv-btn:hover { background: var(--gold); }
    footer { text-align: center; padding: 1.5rem; font-size: 0.8rem; color: var(--muted); border-top: 1px solid var(--border); margin-top: 2rem; }
    @media (max-width: 680px) { .page { flex-direction: column; align-items: center; } aside { position: static; width: 100%; } }
  </style>
</head>
<body>
  <nav>
    <a class="brand" href="index.html">Christen Black</a>
    <a href="index.html">Home</a>
    <a href="PhD_CV__6_.pdf" target="_blank">CV</a>
    <a href="#research">Research</a>
    <a href="#teaching">Teaching</a>
  </nav>

  <div class="page">
    <aside>
      <div class="photo-wrap">
        <!-- Replace with: <img src="headshot.jpg" alt="Christen Black"> -->
        <img src="IMG_5678.jpeg" alt="Christen Black">
      </div>
      <ul class="contact-list">
        <li>
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
          Washington, D.C.
        </li>
        <li>
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 01-2.06 0L2 7"/></svg>
          <a href="mailto:christen.black@bison.howard.edu">University Email</a>
        </li>
        <li>
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4l11.733 16H20L8.267 4z"/><path d="M4 20l6.768-6.768M20 4l-6.768 6.768"/></svg>
          <a href="https://twitter.com/thesouplovers" target="_blank">@thesouplovers</a>
        </li>
        <li>
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="12" y1="18" x2="12" y2="12"/><line x1="9" y1="15" x2="15" y2="15"/></svg>
          <a href="PhD_CV__6_.pdf" target="_blank">Download CV</a>
        </li>
      </ul>
    </aside>

    <main>
      <h1>Christen Black</h1>
      <p class="subtitle">Ph.D. Candidate in Economics &nbsp;|&nbsp; Howard University &nbsp;|&nbsp; christen.black@bison.howard.edu</p>
      <div class="divider"></div>

      <p class="bio">
        Welcome! I am a Ph.D. Candidate in Economics at Howard University in Washington, D.C.
        My research sits at the intersection of labor and urban economics, with a focus on
        racial wage disparities, unionization, and the economic role of Historically Black
        Colleges and Universities (HBCUs). I use large-scale datasets and econometric methods —
        primarily in R — to study how policy shapes opportunity and inequality.
      </p>

      <a class="cv-btn" href="PhD_CV__6_.pdf" target="_blank">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="12" y1="18" x2="12" y2="12"/><line x1="9" y1="15" x2="15" y2="15"/></svg>
        View Full CV
      </a>

      <div class="section" style="margin-top:2.5rem;">
        <h2>Education</h2>
        <ul class="bullet-list">
          <li><strong>Ph.D. Economics</strong> — Howard University, Washington, D.C. &nbsp;(2023–2026 exp.)</li>
          <li><strong>M.A. Economics</strong> — Old Dominion University, Norfolk, VA &nbsp;(2021–2023)</li>
          <li><strong>B.S. Economics</strong> — Hampton University, Hampton, VA &nbsp;(2015–2020) &nbsp;· Dean's List 2019–2020</li>
        </ul>
      </div>

      <div class="section" id="research">
        <h2>Research</h2>
        <div class="research-item">
          <h3>Earnings Differentials of HBCU Graduates</h3>
          <p>Examines earnings differentials between high school graduates who attended HBCUs and those who did not, analyzing their likelihood of earning more than peers who never attended college. Uses restricted-access survey data and regression models to control for selection bias and family background effects.</p>
        </div>
        <div class="research-item">
          <h3>What Impact Does Right to Work Have on Strikes?</h3>
          <p>Uses Difference-in-Differences to study the relationship between right-to-work laws and the relative frequency of strikes across U.S. states.</p>
        </div>
        <div class="research-item">
          <h3>Do Unions Really Help Reduce Inequality?</h3>
          <p>Focuses on OECD countries to study the relationship between union density and income inequality as measured by the GINI index.</p>
        </div>
      </div>

      <div class="section" id="teaching">
        <h2>Teaching &amp; Experience</h2>
        <ul class="bullet-list">
          <li><strong>Fellow, AEA Summer Program (AEASP)</strong> — Howard University / Federal Reserve Board (Summer 2025). Competitively selected; helped students conduct econometrics research and presented findings to Federal Reserve economists and institutions across D.C.</li>
          <li><strong>Adjunct Instructor of Economics</strong> — Hampton University (Summer 2024). Taught Principles of Microeconomics and Macroeconomics; designed course materials and provided academic mentoring.</li>
          <li><strong>Graduate Researcher</strong> — Howard University (2023–Present). Conducts research in labor and urban economics; collaborates with faculty on empirical projects using R for econometric modeling and visualization.</li>
          <li><strong>Board Secretary &amp; Events Coordinator</strong> — Lorton Volunteer Fire Department (2024–Present). Serves on Board of Directors; supports governance, documentation, and community outreach events.</li>
        </ul>
      </div>

      <div class="section">
        <h2>Skills</h2>
        <ul class="bullet-list">
          <li>R / RStudio — 5+ years</li>
          <li>LaTeX — 4+ years</li>
          <li>Econometric modeling, difference-in-differences, regression analysis</li>
          <li>Large-scale restricted-access dataset analysis</li>
          <li>Academic tutoring &amp; instruction — 3+ years</li>
        </ul>
      </div>
    </main>
  </div>

  <footer>
    &copy; 2025 Christen Black &nbsp;·&nbsp; Ph.D. Candidate in Economics, Howard University
  </footer>
</body>
</html>
