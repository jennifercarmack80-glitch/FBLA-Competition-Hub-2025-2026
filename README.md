# FBLA-Competition-Hub-2025-2026
FBLA competition help.
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>FBLA Competition Hub — 2025–2026</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;800&family=DM+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet" />
<style>
/* ══════════════════════════════════════════
   RESET & BASE
   ══════════════════════════════════════════ */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
:root {
  --navy: #0B1D35;
  --navy-mid: #1B3A5C;
  --navy-light: #264A6E;
  --gold: #C9A227;
  --gold-light: #D4B94E;
  --cream: #FAF9F6;
  --warm-gray: #F3F1EC;
  --border: #E4E0D8;
  --text-dark: #0B1D35;
  --text-mid: #4B5563;
  --text-light: #9CA3AF;
  --green: #1D7A4E;
  --green-bg: #EDFBF3;
  --magenta: #9B2C5E;
}
body {
  font-family: 'DM Sans', sans-serif;
  background: var(--cream);
  color: var(--text-dark);
  -webkit-font-smoothing: antialiased;
}
a { color: inherit; text-decoration: none; }
button { font-family: inherit; cursor: pointer; }
input { font-family: inherit; }

/* ══════════════════════════════════════════
NAVBAR
══════════════════════════════════════════ */
.navbar {
position: sticky; top: 0; z-index: 100;
background: rgba(250,249,246,0.92);
backdrop-filter: blur(16px);
border-bottom: 1px solid var(–border);
}
.navbar-inner {
max-width: 1120px; margin: 0 auto; padding: 0 24px;
display: flex; align-items: center; justify-content: space-between;
height: 60px;
}
.logo { display: flex; align-items: center; gap: 11px; }
.logo-icon {
width: 34px; height: 34px; border-radius: 8px;
background: linear-gradient(135deg, var(–navy), var(–navy-mid));
display: flex; align-items: center; justify-content: center;
color: var(–gold); font-family: ‘Playfair Display’, serif;
font-weight: 800; font-size: 17px;
}
.logo-text h1 {
font-family: ‘Playfair Display’, serif; font-size: 15px;
font-weight: 700; color: var(–navy); line-height: 1.15;
}
.logo-text span {
font-size: 9px; color: var(–text-light);
letter-spacing: 1.5px; text-transform: uppercase; font-weight: 600;
}
.nav-links { display: flex; gap: 4px; }
.nav-btn {
padding: 7px 14px; border-radius: 8px; border: none;
font-size: 12.5px; font-weight: 600; transition: all 0.2s;
display: flex; align-items: center; gap: 5px;
background: transparent; color: var(–text-mid);
}
.nav-btn.active { background: var(–navy); color: #fff; }
.nav-btn:hover:not(.active) { background: var(–warm-gray); }
@media (max-width: 600px) {
.nav-btn span.lbl { display: none; }
.nav-btn { padding: 7px 10px; }
}

/* ══════════════════════════════════════════
HERO
══════════════════════════════════════════ */
.hero {
background: linear-gradient(160deg, var(–navy) 0%, var(–navy-mid) 100%);
position: relative; overflow: hidden; text-align: center;
}
.hero::before {
content: ‘’; position: absolute; inset: 0;
background: radial-gradient(ellipse at 30% 0%, rgba(201,162,39,0.08) 0%, transparent 55%),
radial-gradient(ellipse at 100% 100%, rgba(201,162,39,0.06) 0%, transparent 50%);
}
.hero::after {
content: ‘’; position: absolute; inset: 0; opacity: 0.03;
background-image: linear-gradient(rgba(255,255,255,0.5) 1px, transparent 1px),
linear-gradient(90deg, rgba(255,255,255,0.5) 1px, transparent 1px);
background-size: 60px 60px;
}
.hero-inner {
position: relative; z-index: 1; max-width: 800px;
margin: 0 auto; padding: 56px 24px 48px;
}
.hero-badge {
display: inline-flex; align-items: center; gap: 8px;
padding: 5px 18px; border-radius: 20px;
border: 1px solid rgba(201,162,39,0.25); margin-bottom: 20px;
color: var(–gold); font-size: 10px; letter-spacing: 3px;
text-transform: uppercase; font-weight: 700;
}
.hero h2 {
font-family: ‘Playfair Display’, serif; font-size: clamp(28px, 5vw, 42px);
font-weight: 800; color: #fff; margin-bottom: 14px; line-height: 1.15;
}
.hero h2 em { font-style: normal; color: var(–gold); }
.hero p {
color: rgba(255,255,255,0.55); font-size: 15px;
line-height: 1.6; max-width: 520px; margin: 0 auto;
}

/* ══════════════════════════════════════════
COUNTDOWN
══════════════════════════════════════════ */
.countdown {
background: linear-gradient(135deg, var(–navy) 0%, var(–navy-mid) 50%, var(–navy) 100%);
position: relative; overflow: hidden;
}
.countdown::before {
content: ‘’; position: absolute; inset: 0; opacity: 0.6;
background: radial-gradient(circle at 20% 40%, rgba(201,162,39,0.08) 0%, transparent 50%),
radial-gradient(circle at 80% 60%, rgba(201,162,39,0.05) 0%, transparent 50%);
}
.countdown-inner {
position: relative; max-width: 880px; margin: 0 auto;
padding: 44px 24px; text-align: center;
}
.countdown-label {
display: inline-block; padding: 4px 18px; border-radius: 20px;
border: 1px solid rgba(201,162,39,0.3); margin-bottom: 14px;
color: var(–gold); font-size: 10px; letter-spacing: 3px;
text-transform: uppercase; font-weight: 700;
}
.countdown h3 {
font-family: ‘Playfair Display’, serif; font-size: 26px;
font-weight: 700; color: #fff; margin-bottom: 6px;
}
.countdown .date-text {
color: rgba(255,255,255,0.45); font-size: 13px; margin-bottom: 28px;
}
.countdown-blocks { display: flex; justify-content: center; gap: 14px; flex-wrap: wrap; }
.countdown-block {
background: rgba(255,255,255,0.04);
border: 1px solid rgba(201,162,39,0.15);
border-radius: 12px; padding: 18px 22px; min-width: 90px;
}
.countdown-block .num {
color: var(–gold); font-family: ‘Playfair Display’, serif;
font-size: 38px; font-weight: 700; line-height: 1;
}
.countdown-block .unit {
color: rgba(255,255,255,0.4); font-size: 10px;
letter-spacing: 2px; text-transform: uppercase; margin-top: 6px;
}

/* ══════════════════════════════════════════
MAIN CONTENT
══════════════════════════════════════════ */
.main { max-width: 1120px; margin: 0 auto; padding: 40px 24px 60px; }
.section-header {
display: flex; align-items: center; gap: 10px; margin-bottom: 20px;
}
.section-header h2 {
font-family: ‘Playfair Display’, serif; font-size: 24px;
font-weight: 700; color: var(–navy);
}

/* ── Dashboard ── */
.dashboard {
background: #fff; border-radius: 14px; border: 1px solid var(–border);
padding: 28px; box-shadow: 0 2px 12px rgba(0,0,0,0.03); margin-bottom: 32px;
}
.stats-grid {
display: grid; grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
gap: 12px; margin: 20px 0;
}
.stat-card {
background: var(–warm-gray); border-radius: 10px; padding: 16px 12px;
text-align: center; border: 1px solid var(–border);
}
.stat-card .val {
font-family: ‘Playfair Display’, serif; font-size: 30px;
font-weight: 700; color: var(–navy-mid);
}
.stat-card .label {
font-size: 11px; font-weight: 700; color: var(–text-mid);
letter-spacing: 0.8px; text-transform: uppercase; margin-top: 2px;
}
.stat-card .sub { font-size: 11px; color: var(–text-light); margin-top: 2px; }
.progress-bar {
height: 8px; background: var(–warm-gray); border-radius: 4px; overflow: hidden;
}
.progress-fill {
height: 100%; border-radius: 4px; transition: width 0.8s cubic-bezier(.4,0,.2,1);
}
.progress-pct { text-align: right; margin-top: 6px; font-size: 12px; font-weight: 700; }

/* ── Search & Filter ── */
.search-wrap { position: relative; margin-bottom: 16px; }
.search-wrap .icon {
position: absolute; left: 14px; top: 50%; transform: translateY(-50%);
font-size: 16px; color: var(–text-light); pointer-events: none;
}
.search-input {
width: 100%; padding: 12px 16px 12px 42px; border-radius: 10px;
border: 1px solid var(–border); font-size: 14px; color: var(–text-dark);
background: #fff; outline: none; transition: border 0.2s;
}
.search-input:focus { border-color: var(–gold); }
.filter-row { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 24px; }
.filter-btn {
padding: 7px 16px; border-radius: 8px; font-size: 12px; font-weight: 600;
transition: all 0.2s; display: flex; align-items: center; gap: 5px;
border: 1px solid var(–border); background: #fff; color: var(–text-mid);
}
.filter-btn.active {
background: var(–navy); color: #fff; border-color: var(–navy);
}
.filter-btn:hover:not(.active) { background: var(–warm-gray); }
.filter-btn .count {
font-size: 10px; opacity: 0.7; margin-left: 2px;
padding: 1px 6px; border-radius: 4px;
}
.filter-btn.active .count { background: rgba(255,255,255,0.15); }
.filter-btn:not(.active) .count { background: var(–warm-gray); }
.results-count {
font-size: 12px; color: var(–text-light); margin-bottom: 16px; font-weight: 600;
}

/* ── Event Cards Grid ── */
.cards-grid {
display: grid; grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
gap: 16px;
}
@media (max-width: 400px) {
.cards-grid { grid-template-columns: 1fr; }
}
.event-card {
background: #fff; border-radius: 14px; border: 1px solid var(–border);
overflow: hidden; transition: all 0.3s ease;
box-shadow: 0 1px 6px rgba(0,0,0,0.03);
}
.event-card.expanded {
box-shadow: 0 12px 40px rgba(11,29,53,0.1); transform: translateY(-2px);
}
.card-body { padding: 20px 22px 14px; }
.card-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 10px; flex-wrap: wrap; gap: 6px; }
.cat-badge {
font-size: 10px; letter-spacing: 1.8px; text-transform: uppercase;
font-weight: 700; padding: 3px 10px; border-radius: 4px;
display: inline-flex; align-items: center; gap: 5px;
}
.done-badge {
font-size: 11px; font-weight: 700; padding: 3px 10px; border-radius: 4px;
color: var(–green); background: var(–green-bg);
}
.card-body h3 {
font-family: ‘Playfair Display’, serif; font-size: 19px;
font-weight: 700; color: var(–navy); margin-bottom: 5px;
}
.card-body .desc { font-size: 13px; color: var(–text-mid); line-height: 1.55; margin-bottom: 12px; }
.card-progress { height: 4px; background: var(–warm-gray); border-radius: 2px; overflow: hidden; }
.card-progress-fill { height: 100%; border-radius: 2px; transition: width 0.5s ease; }
.resource-links { display: flex; gap: 7px; margin-top: 14px; flex-wrap: wrap; }
.resource-link {
display: inline-flex; align-items: center; gap: 4px;
padding: 6px 12px; border-radius: 6px; font-size: 12px; font-weight: 600;
color: var(–navy-mid); background: var(–warm-gray);
border: 1px solid var(–border); transition: all 0.2s;
}
.resource-link:hover { background: var(–navy); color: #fff; border-color: var(–navy); }
.expand-btn {
width: 100%; padding: 10px; border: none;
border-top: 1px solid var(–border);
font-size: 12px; font-weight: 600; color: var(–navy-mid);
background: transparent; transition: background 0.2s;
display: flex; align-items: center; justify-content: center; gap: 6px;
}
.expand-btn.open { background: var(–warm-gray); }

/* ── Expanded Panel ── */
.expanded-panel { padding: 0 22px 22px; background: var(–warm-gray); }
.coach-tip {
background: linear-gradient(135deg, var(–navy), var(–navy-mid));
border-radius: 10px; padding: 16px 20px; margin-bottom: 16px;
position: relative; overflow: hidden;
}
.coach-tip::after {
content: ‘💡’; position: absolute; top: -8px; right: -8px;
font-size: 56px; opacity: 0.06;
}
.coach-tip .tip-label {
display: flex; align-items: center; gap: 8px; margin-bottom: 8px;
font-size: 10px; letter-spacing: 2px; text-transform: uppercase;
color: var(–gold); font-weight: 700;
}
.coach-tip p {
font-size: 13.5px; color: rgba(255,255,255,0.85);
line-height: 1.6; font-style: italic;
}
.checklist-title {
font-size: 11px; letter-spacing: 1.5px; text-transform: uppercase;
color: var(–text-light); font-weight: 700; margin-bottom: 10px;
}
.checklist { display: flex; flex-direction: column; gap: 5px; }
.check-item {
display: flex; align-items: center; gap: 10px;
padding: 8px 12px; border-radius: 8px; cursor: pointer;
background: #fff; border: 1px solid var(–border); transition: all 0.2s;
user-select: none;
}
.check-item.done { background: var(–green-bg); border-color: #BBE5C4; }
.check-box {
width: 20px; height: 20px; border-radius: 5px; flex-shrink: 0;
border: 2px solid #C4BFB4; background: transparent;
display: flex; align-items: center; justify-content: center;
transition: all 0.2s; font-size: 12px; color: #fff;
}
.check-item.done .check-box {
background: var(–green); border: none;
}
.check-label { font-size: 13px; color: var(–text-mid); transition: all 0.2s; }
.check-item.done .check-label {
color: var(–green); text-decoration: line-through; font-weight: 600;
}

/* ── Empty State ── */
.empty-state {
text-align: center; padding: 48px 24px;
background: #fff; border-radius: 14px; border: 1px solid var(–border);
}

/* ── Calendar Timeline ── */
.calendar-card {
background: #fff; border-radius: 14px; border: 1px solid var(–border);
padding: 28px; box-shadow: 0 2px 12px rgba(0,0,0,0.03);
}
.timeline { position: relative; padding-left: 28px; }
.timeline::before {
content: ‘’; position: absolute; left: 9px; top: 8px; bottom: 8px;
width: 2px; background: linear-gradient(to bottom, var(–gold), var(–border));
}
.tl-item { position: relative; margin-bottom: 22px; padding-left: 20px; }
.tl-dot {
position: absolute; left: -22px; top: 6px; width: 12px; height: 12px;
border-radius: 50%; border: 2px solid;
}
.tl-dot.filled { background: var(–navy); border-color: var(–navy); }
.tl-meta { display: flex; align-items: center; gap: 10px; flex-wrap: wrap; margin-bottom: 4px; }
.tl-date { font-size: 12px; font-weight: 700; color: var(–text-light); min-width: 100px; }
.tl-type {
font-size: 10px; font-weight: 700; letter-spacing: 1px;
text-transform: uppercase; padding: 2px 8px; border-radius: 4px;
}
.tl-item h4 {
font-family: ‘Playfair Display’, serif; font-size: 16px;
font-weight: 700; color: var(–navy); margin-bottom: 3px;
}
.tl-item p { font-size: 13px; color: var(–text-mid); line-height: 1.5; }

/* ── Footer ── */
.footer {
background: var(–navy); padding: 32px 24px; text-align: center;
}
.footer h4 {
font-family: ‘Playfair Display’, serif; font-size: 16px;
font-weight: 700; color: #fff; margin-bottom: 6px;
}
.footer p { font-size: 12px; color: rgba(255,255,255,0.35); }

/* Smooth scroll */
html { scroll-behavior: smooth; }
[id] { scroll-margin-top: 80px; }
</style>

</head>
<body>

<!-- ══════════════════════════════════════════
     NAVBAR
     ══════════════════════════════════════════ -->

<header class="navbar">
  <div class="navbar-inner">
    <div class="logo">
      <div class="logo-icon">F</div>
      <div class="logo-text">
        <h1>FBLA Competition Hub</h1>
        <span>2025–2026 Season</span>
      </div>
    </div>
    <nav class="nav-links">
      <button class="nav-btn active" onclick="scrollTo('study-vault')" id="nav-vault">
        <span>📚</span><span class="lbl">Study Vault</span>
      </button>
      <button class="nav-btn" onclick="scrollTo('event-finder')" id="nav-finder">
        <span>🔍</span><span class="lbl">Event Finder</span>
      </button>
      <button class="nav-btn" onclick="scrollTo('calendar')" id="nav-calendar">
        <span>📅</span><span class="lbl">Calendar</span>
      </button>
    </nav>
  </div>
</header>

<!-- ══════════════════════════════════════════
     HERO
     ══════════════════════════════════════════ -->

<section class="hero">
  <div class="hero-inner">
    <div class="hero-badge">
      <span>✦</span>
      Future Business Leaders of America
      <span>✦</span>
    </div>
    <h2>Your Competition<br><em>Command Center</em></h2>
    <p>Study resources, practice tests, coach tips, and progress tracking — everything you need to compete at your best this season.</p>
  </div>
</section>

<!-- ══════════════════════════════════════════
     COUNTDOWN
     ══════════════════════════════════════════ -->

<section class="countdown">
  <div class="countdown-inner">
    <div class="countdown-label">Countdown To</div>
    <h3>State Leadership Conference</h3>
    <p class="date-text" id="comp-date"></p>
    <div class="countdown-blocks">
      <div class="countdown-block"><div class="num" id="cd-days">--</div><div class="unit">Days</div></div>
      <div class="countdown-block"><div class="num" id="cd-hours">--</div><div class="unit">Hours</div></div>
      <div class="countdown-block"><div class="num" id="cd-mins">--</div><div class="unit">Minutes</div></div>
      <div class="countdown-block"><div class="num" id="cd-secs">--</div><div class="unit">Seconds</div></div>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════════
     MAIN CONTENT
     ══════════════════════════════════════════ -->

<div class="main">

  <!-- ── STUDY VAULT / DASHBOARD ── -->

  <div id="study-vault">
    <div class="dashboard">
      <div class="section-header">
        <span style="font-size:20px">📊</span>
        <h2>Your Study Dashboard</h2>
      </div>
      <div class="stats-grid">
        <div class="stat-card"><div class="val" id="stat-tasks">0</div><div class="label">Tasks Done</div><div class="sub" id="stat-tasks-total">of 0</div></div>
        <div class="stat-card"><div class="val" id="stat-started">0</div><div class="label">Events Started</div><div class="sub" id="stat-started-total">of 0</div></div>
        <div class="stat-card"><div class="val" id="stat-mastered">0</div><div class="label">Events Mastered</div><div class="sub" id="stat-mastered-sub">Keep going!</div></div>
      </div>
      <div class="progress-bar"><div class="progress-fill" id="dash-fill" style="width:0%;background:linear-gradient(90deg,var(--gold),var(--gold-light))"></div></div>
      <div class="progress-pct" id="dash-pct" style="color:var(--gold)">0% Complete</div>
    </div>
  </div>

  <!-- ── EVENT FINDER ── -->

  <div id="event-finder" style="margin-bottom:48px">
    <div class="section-header">
      <span style="font-size:22px">🔍</span>
      <h2>Event Finder</h2>
    </div>
    <div class="search-wrap">
      <span class="icon">🔎</span>
      <input class="search-input" id="search-input" placeholder="Search events... (e.g. Accounting, Public Speaking, AI)" oninput="renderCards()" />
    </div>
    <div class="filter-row" id="filter-row"></div>
    <p class="results-count" id="results-count"></p>
    <div class="cards-grid" id="cards-grid"></div>
  </div>

  <!-- ── COMPETITIVE CALENDAR ── -->

  <div id="calendar">
    <div class="section-header">
      <span style="font-size:22px">📅</span>
      <h2>Competitive Calendar</h2>
    </div>
    <div class="calendar-card">
      <div class="timeline" id="timeline"></div>
    </div>
  </div>
</div>

<!-- ══════════════════════════════════════════
     FOOTER
     ══════════════════════════════════════════ -->

<footer class="footer">
  <h4>FBLA Competition Hub</h4>
  <p>FBLA Chapter · 2025–2026 Season · Built with ♥ for future leaders</p>
</footer>

<script>
// ════════════════════════════════════════════════════════════
//  CONFIGURATION — UPDATE THESE WITH YOUR URLS!
//  Replace every "#" with your Google Drive / Quizlet links.
// ════════════════════════════════════════════════════════════
const COMP_DATE = new Date("2026-03-15T08:00:00");
const COMP_NAME = "State Leadership Conference";

const EVENTS = [
  // ── Objective Tests ──
  {id:1, name:"Accounting I", cat:"objective", desc:"Financial statements, journals, ledgers, and core accounting concepts.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Focus on adjusting entries and the accounting equation — tested every single year."},
  {id:2, name:"Accounting II", cat:"objective", desc:"Advanced topics: partnerships, corporations, and managerial accounting.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Know your depreciation methods cold. Practice journal entries for bonds payable."},
  {id:3, name:"Business Law", cat:"objective", desc:"Contracts, torts, property law, employment law, and ethics.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Memorize the elements of a valid contract. Past tests repeat key concepts."},
  {id:4, name:"Economics", cat:"objective", desc:"Micro and macroeconomic principles, supply & demand, monetary policy.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Draw supply and demand curves from memory. Understand shifts vs. movements."},
  {id:5, name:"Insurance & Risk Mgmt", cat:"objective", desc:"Types of insurance, risk assessment, and industry regulations.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Know the difference between term and whole life insurance inside and out."},
  {id:6, name:"Personal Finance", cat:"objective", desc:"Budgeting, credit, investments, taxes, and financial planning.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Compound interest formula is a must-know. Practice Rule of 72 calculations."},
  {id:7, name:"Securities & Investments", cat:"objective", desc:"Stock markets, mutual funds, bonds, portfolio management.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Understand P/E ratios, read stock tables, and know your bond terminology."},
  {id:8, name:"Cyber Security", cat:"objective", desc:"Network security, encryption, threat analysis, and security protocols.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Study the CIA triad and common attack vectors. Know your port numbers."},
  // ── Performance Events ──
  {id:9, name:"Public Speaking", cat:"performance", desc:"Deliver a 4-minute speech on a business topic with Q&A.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Structure: Hook → 3 Points → Strong Close. Practice your timing religiously."},
  {id:10, name:"Impromptu Speaking", cat:"performance", desc:"Prepare and deliver a speech on a random business topic in limited time.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Use the PREP method: Point, Reason, Example, Point. Read business news daily."},
  {id:11, name:"Client Service", cat:"performance", desc:"Role-play resolving customer complaints and providing excellent service.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Always acknowledge the customer's feelings first before solving the problem."},
  {id:12, name:"Job Interview", cat:"performance", desc:"Professional interview simulation with resume and follow-up letter.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Use the STAR method for every behavioral question. Prepare 5 versatile stories."},
  {id:13, name:"Elevator Speech", cat:"performance", desc:"Deliver a compelling 30-second pitch for a business idea or product.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Open with the problem, not the solution. Make them feel the pain point first."},
  {id:14, name:"Social Media Strategies", cat:"performance", desc:"Develop and present social media marketing campaigns.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Include real metrics and KPIs. Judges love when you quantify your strategy."},
  // ── Production Events ──
  {id:15, name:"Website Design", cat:"production", desc:"Design and code a website for a fictional or real business.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Accessibility and mobile responsiveness are judged. Don't just make it pretty."},
  {id:16, name:"Graphic Design", cat:"production", desc:"Create promotional materials, logos, and branding packages.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Consistency is key — use a style guide. Judges notice mismatched fonts instantly."},
  {id:17, name:"Video Production", cat:"production", desc:"Produce a professional-quality video on a given business topic.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Audio quality matters more than video quality. Invest time in good sound."},
  {id:18, name:"Computer Game & Sim", cat:"production", desc:"Design and develop an interactive game or business simulation.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"A simple, polished game beats an ambitious broken one. Scope small, execute big."},
  // ── New 2026 Events ──
  {id:19, name:"Data Science & AI", cat:"new2026", desc:"Apply data science methodologies and AI concepts to solve business problems.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Brand new event — study the official guidelines carefully. Focus on ethics in AI."},
  {id:20, name:"E-Commerce", cat:"new2026", desc:"Develop and present an e-commerce business strategy and storefront.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Know your conversion funnel metrics. Customer acquisition cost is a hot topic."},
  {id:21, name:"UX Design", cat:"new2026", desc:"Research, wireframe, and present user experience solutions.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Always start with user research. Show your process, not just the final mockup."},
  {id:22, name:"Entrepreneurship Exploration", cat:"new2026", desc:"Develop and pitch an original business concept with financial projections.", guidelines:"#", practiceTest:"#", quizlet:"#", tip:"Judges want to see market validation. Talk to real potential customers beforehand."},
];

const CATEGORIES = [
  {id:"all", label:"All Events", icon:"✦"},
  {id:"objective", label:"Objective Tests", icon:"📝", accent:"#C9A227"},
  {id:"performance", label:"Performance", icon:"🎤", accent:"#1B3A5C"},
  {id:"production", label:"Production", icon:"💻", accent:"#2D6A4F"},
  {id:"new2026", label:"New 2026", icon:"🚀", accent:"#9B2C5E"},
];

const TASKS = [
  {id:"read", label:"Read Guidelines", icon:"📋"},
  {id:"test", label:"Take Practice Test", icon:"✏️"},
  {id:"flash", label:"Review Flashcards", icon:"🃏"},
  {id:"notes", label:"Compile Study Notes", icon:"📓"},
  {id:"mock", label:"Mock Presentation / Drill", icon:"🎯"},
  {id:"review", label:"Final Review & Confidence Check", icon:"✅"},
];

const CAL_EVENTS = [
  {date:"Sep 2025", title:"Season Kickoff & Event Selection", type:"chapter", desc:"Choose your competitive events and form teams."},
  {date:"Oct 2025", title:"Study Phase Begins", type:"prep", desc:"Start reading guidelines and taking practice tests."},
  {date:"Nov 2025", title:"Practice Competition #1", type:"practice", desc:"Internal mock competition to gauge readiness."},
  {date:"Dec 2025", title:"Mid-Season Review", type:"chapter", desc:"Coach check-ins. Adjust strategies and event choices."},
  {date:"Jan 2026", title:"District / Regional Qualifier", type:"competition", desc:"First official qualifying competition."},
  {date:"Feb 2026", title:"Intensive Prep Month", type:"prep", desc:"Daily drills, mock interviews, and final production polish."},
  {date:"Mar 15, 2026", title:COMP_NAME, type:"competition", desc:"The big day. Leave it all on the stage."},
  {date:"Apr 2026", title:"National Qualifier Results", type:"competition", desc:"Top performers advance to NLC."},
  {date:"Jun 2026", title:"National Leadership Conference", type:"competition", desc:"Compete on the national stage."},
];

// ════════════════════════════════════════════════════════════
//  STATE
// ════════════════════════════════════════════════════════════
let checkedItems = JSON.parse(localStorage.getItem('fbla-progress') || '{}');
let activeCat = 'all';
let expandedCards = {};

function saveProgress() {
  localStorage.setItem('fbla-progress', JSON.stringify(checkedItems));
}

// ════════════════════════════════════════════════════════════
//  COUNTDOWN
// ════════════════════════════════════════════════════════════
document.getElementById('comp-date').textContent = COMP_DATE.toLocaleDateString('en-US', {weekday:'long', year:'numeric', month:'long', day:'numeric'});

function updateCountdown() {
  const diff = COMP_DATE - new Date();
  if (diff <= 0) { document.getElementById('cd-days').textContent = '00'; document.getElementById('cd-hours').textContent = '00'; document.getElementById('cd-mins').textContent = '00'; document.getElementById('cd-secs').textContent = '00'; return; }
  document.getElementById('cd-days').textContent = String(Math.floor(diff / 864e5)).padStart(2,'0');
  document.getElementById('cd-hours').textContent = String(Math.floor((diff/36e5)%24)).padStart(2,'0');
  document.getElementById('cd-mins').textContent = String(Math.floor((diff/6e4)%60)).padStart(2,'0');
  document.getElementById('cd-secs').textContent = String(Math.floor((diff/1e3)%60)).padStart(2,'0');
}
updateCountdown();
setInterval(updateCountdown, 1000);

// ════════════════════════════════════════════════════════════
//  NAVIGATION
// ════════════════════════════════════════════════════════════
function scrollTo(id) {
  document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
  document.getElementById('nav-' + {
    'study-vault':'vault','event-finder':'finder','calendar':'calendar'
  }[id]).classList.add('active');
  document.getElementById(id).scrollIntoView({behavior:'smooth', block:'start'});
}

// ════════════════════════════════════════════════════════════
//  FILTER BUTTONS
// ════════════════════════════════════════════════════════════
function renderFilters() {
  const row = document.getElementById('filter-row');
  row.innerHTML = CATEGORIES.map(c => {
    const count = c.id === 'all' ? '' : `<span class="count">${EVENTS.filter(e=>e.cat===c.id).length}</span>`;
    return `<button class="filter-btn ${activeCat===c.id?'active':''}" onclick="setFilter('${c.id}')"><span>${c.icon}</span>${c.label}${count}</button>`;
  }).join('');
}

function setFilter(id) { activeCat = id; renderFilters(); renderCards(); }

// ════════════════════════════════════════════════════════════
//  DASHBOARD
// ════════════════════════════════════════════════════════════
function updateDashboard() {
  let done = 0;
  const total = EVENTS.length * TASKS.length;
  Object.values(checkedItems).forEach(ev => Object.values(ev).forEach(v => { if(v) done++; }));
  const pct = total > 0 ? Math.round((done/total)*100) : 0;
  const started = Object.keys(checkedItems).filter(k => Object.values(checkedItems[k]).some(Boolean)).length;
  const mastered = Object.keys(checkedItems).filter(k => TASKS.every(t => checkedItems[k]?.[t.id])).length;

  document.getElementById('stat-tasks').textContent = done;
  document.getElementById('stat-tasks-total').textContent = `of ${total}`;
  document.getElementById('stat-started').textContent = started;
  document.getElementById('stat-started-total').textContent = `of ${EVENTS.length}`;
  document.getElementById('stat-mastered').textContent = mastered;
  document.getElementById('stat-mastered-sub').textContent = mastered > 0 ? '🏆' : 'Keep going!';

  const fill = document.getElementById('dash-fill');
  fill.style.width = pct + '%';
  fill.style.background = pct === 100 ? 'linear-gradient(90deg,var(--green),#3DA06A)' : 'linear-gradient(90deg,var(--gold),var(--gold-light))';

  const pctEl = document.getElementById('dash-pct');
  pctEl.textContent = pct + '% Complete';
  pctEl.style.color = pct === 100 ? 'var(--green)' : 'var(--gold)';
}

// ════════════════════════════════════════════════════════════
//  EVENT CARDS
// ════════════════════════════════════════════════════════════
function toggleCheck(eventId, taskId) {
  if (!checkedItems[eventId]) checkedItems[eventId] = {};
  checkedItems[eventId][taskId] = !checkedItems[eventId][taskId];
  saveProgress();
  renderCards();
  updateDashboard();
}

function toggleExpand(eventId) {
  expandedCards[eventId] = !expandedCards[eventId];
  renderCards();
}

function renderCards() {
  const query = document.getElementById('search-input').value.toLowerCase();
  const filtered = EVENTS.filter(e => {
    const catOk = activeCat === 'all' || e.cat === activeCat;
    const searchOk = e.name.toLowerCase().includes(query) || e.desc.toLowerCase().includes(query);
    return catOk && searchOk;
  });

  document.getElementById('results-count').textContent =
    `Showing ${filtered.length} event${filtered.length !== 1 ? 's' : ''}${query ? ` matching "${query}"` : ''}`;

  const grid = document.getElementById('cards-grid');
  if (filtered.length === 0) {
    grid.innerHTML = '<div class="empty-state"><span style="font-size:40px;display:block;margin-bottom:12px">🔍</span><p style="font-size:15px;color:var(--text-mid)">No events match your search. Try a different keyword or category.</p></div>';
    return;
  }

  grid.innerHTML = filtered.map(ev => {
    const cat = CATEGORIES.find(c => c.id === ev.cat);
    const evChecked = checkedItems[ev.id] || {};
    const count = TASKS.filter(t => evChecked[t.id]).length;
    const pct = Math.round((count / TASKS.length) * 100);
    const isOpen = expandedCards[ev.id];

    const progressColor = pct === 100 ? 'var(--green)' : 'linear-gradient(90deg,var(--gold),var(--gold-light))';
    const doneBadge = count > 0 ? `<span class="done-badge">${count}/${TASKS.length}</span>` : '';

    const checklistHTML = TASKS.map(t => {
      const done = !!evChecked[t.id];
      return `<div class="check-item ${done?'done':''}" onclick="toggleCheck(${ev.id},'${t.id}')">
        <div class="check-box">${done?'✓':''}</div>
        <span style="font-size:12px;margin-right:4px">${t.icon}</span>
        <span class="check-label">${t.label}</span>
      </div>`;
    }).join('');

    const expandedHTML = isOpen ? `
      <div class="expanded-panel">
        <div class="coach-tip">
          <div class="tip-label"><span style="font-size:15px">💡</span> Coach's Tip</div>
          <p>"${ev.tip}"</p>
        </div>
        <h4 class="checklist-title">Study Progress</h4>
        <div class="checklist">${checklistHTML}</div>
      </div>` : '';

    return `<div class="event-card ${isOpen?'expanded':''}">
      <div class="card-body">
        <div class="card-top">
          <span class="cat-badge" style="color:${cat.accent||'var(--gold)'};background:${cat.accent||'var(--gold)'}11">
            <span style="font-size:13px">${cat.icon}</span>${cat.label}
          </span>
          ${doneBadge}
        </div>
        <h3>${ev.name}</h3>
        <p class="desc">${ev.desc}</p>
        <div class="card-progress"><div class="card-progress-fill" style="width:${pct}%;background:${progressColor}"></div></div>
        <div class="resource-links">
          <a href="${ev.guidelines}" target="_blank" rel="noopener noreferrer" class="resource-link"><span>📋</span> Guidelines</a>
          <a href="${ev.practiceTest}" target="_blank" rel="noopener noreferrer" class="resource-link"><span>✏️</span> Practice Test</a>
          <a href="${ev.quizlet}" target="_blank" rel="noopener noreferrer" class="resource-link"><span>🃏</span> Quizlet</a>
        </div>
      </div>
      <button class="expand-btn ${isOpen?'open':''}" onclick="toggleExpand(${ev.id})">${isOpen ? 'Hide Details ▲' : 'Checklist & Coach\'s Tip ▼'}</button>
      ${expandedHTML}
    </div>`;
  }).join('');
}

// ════════════════════════════════════════════════════════════
//  CALENDAR TIMELINE
// ════════════════════════════════════════════════════════════
function renderTimeline() {
  const typeStyles = {
    chapter: {bg:'#EEF2FF', color:'#4338CA', label:'Chapter'},
    prep: {bg:'rgba(201,162,39,0.08)', color:'var(--gold)', label:'Prep'},
    practice: {bg:'#FEF3C7', color:'#B45309', label:'Practice'},
    competition: {bg:'rgba(11,29,53,0.06)', color:'var(--navy)', label:'Competition'},
  };

  document.getElementById('timeline').innerHTML = CAL_EVENTS.map(ev => {
    const st = typeStyles[ev.type];
    const filled = ev.type === 'competition' ? 'filled' : '';
    return `<div class="tl-item">
      <div class="tl-dot ${filled}" style="border-color:${st.color};${filled?'background:'+st.color:''}"></div>
      <div class="tl-meta">
        <span class="tl-date">${ev.date}</span>
        <span class="tl-type" style="color:${st.color};background:${st.bg}">${st.label}</span>
      </div>
      <h4>${ev.title}</h4>
      <p>${ev.desc}</p>
    </div>`;
  }).join('');
}

// ════════════════════════════════════════════════════════════
//  INIT
// ════════════════════════════════════════════════════════════
renderFilters();
renderCards();
updateDashboard();
renderTimeline();
</script>

</body>
</html>