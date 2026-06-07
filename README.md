# Tigerke5615M.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="monetag" content="070cba092296446121ce0635398925ea">
<meta name="16e2646ef4680cb5e13911ea81e09a93cfd8bcb2" content="16e2646ef4680cb5e13911ea81e09a93cfd8bcb2" />
<title>Riche Tiger — The OS Vault</title>

<script src="https://quge5.com/88/tag.min.js" data-zone="247144" async data-cfasync="false"></script>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-7709827809223128" crossorigin="anonymous"></script>

<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital@0;1&family=Geist:wght@300;400;500;600&family=Geist+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

:root {
  --bg:        #07090f;
  --surface:  #0d1017;
  --border:    rgba(255,255,255,0.07);
  --border-h: rgba(255,255,255,0.14);
  --txt:      #e8eaf0;
  --txt2:     #7a8499;
  --txt3:     #3d4558;
  --accent:    #3b6eff;
  --accent-s: #1a4fff;

  --win:  #4a9eff;
  --ubu:  #e95420;
  --mint: #00c97a;
  --fed:  #4b8fd4;
  --deb:  #c8304a;
  --arch: #1793d1;
  --mnj:  #35bf5c;
  --ele:  #64b4ff;
  --chr:  #4285f4;
  --oth:  #a855f7;

  --font-serif: 'Instrument Serif', Georgia, serif;
  --font-sans:  'Geist', system-ui, sans-serif;
  --font-mono:  'Geist Mono', monospace;
  --r: 10px;
}

html { scroll-behavior: smooth; }

body {
  font-family: var(--font-sans);
  background: var(--bg);
  color: var(--txt);
  min-height: 100vh;
  overflow-x: hidden;
  -webkit-font-smoothing: antialiased;
}

/* ─── SUBTLE BACKGROUND ─── */
body::before {
  content: '';
  position: fixed; inset: 0; pointer-events: none; z-index: 0;
  background:
    radial-gradient(ellipse 80% 50% at 10% -10%, rgba(59,110,255,0.09) 0%, transparent 60%),
    radial-gradient(ellipse 60% 40% at 90% 100%, rgba(59,110,255,0.06) 0%, transparent 55%);
}

/* ─── NAV ─── */
nav {
  position: sticky; top: 0; z-index: 100;
  height: 56px; padding: 0 40px;
  display: flex; align-items: center; justify-content: space-between;
  background: rgba(7,9,15,0.92);
  backdrop-filter: blur(20px);
  border-bottom: 1px solid var(--border);
}

.logo {
  display: flex; align-items: center; gap: 10px;
  font-family: var(--font-sans); font-weight: 600; font-size: 15px;
  letter-spacing: -0.3px; color: var(--txt);
  text-decoration: none;
}
.logo-mark {
  width: 28px; height: 28px; border-radius: 7px;
  background: var(--accent);
  display: flex; align-items: center; justify-content: center;
  font-size: 13px;
}
.logo em {
  font-style: normal; color: var(--txt2); font-weight: 400;
}

.nav-badge {
  font-family: var(--font-mono); font-size: 11px; color: var(--txt2);
  padding: 4px 12px; border: 1px solid var(--border);
  border-radius: 99px; letter-spacing: 0.2px;
  display: flex; align-items: center; gap: 6px;
}
.live-dot {
  width: 5px; height: 5px; border-radius: 50%;
  background: #22d77a;
  box-shadow: 0 0 6px #22d77a;
  animation: blink 2.4s ease infinite;
}
@keyframes blink { 0%,100%{opacity:1} 50%{opacity:.25} }

/* ─── HERO ─── */
.hero {
  position: relative; z-index: 1;
  max-width: 900px; margin: 0 auto;
  padding: 80px 40px 64px;
  border-bottom: 1px solid var(--border);
}

.hero-kicker {
  display: inline-flex; align-items: center; gap: 8px;
  font-family: var(--font-mono); font-size: 11px;
  letter-spacing: 1.5px; text-transform: uppercase;
  color: var(--accent); margin-bottom: 24px;
  opacity: 0; animation: rise 0.6s ease 0.1s forwards;
}
.hero-kicker::before {
  content: '';
  display: block; width: 20px; height: 1px; background: var(--accent);
}

.hero-title {
  font-family: var(--font-serif);
  font-size: clamp(48px, 6vw, 78px);
  font-weight: 400;
  line-height: 1.05;
  letter-spacing: -1px;
  color: var(--txt);
  margin-bottom: 20px;
  opacity: 0; animation: rise 0.6s ease 0.2s forwards;
}
.hero-title em {
  font-style: italic; color: var(--txt2);
}

.hero-sub {
  font-size: 15px; color: var(--txt2); font-weight: 300;
  line-height: 1.75; max-width: 480px;
  margin-bottom: 48px;
  opacity: 0; animation: rise 0.6s ease 0.3s forwards;
}

.hero-metrics {
  display: flex; gap: 0;
  border: 1px solid var(--border); border-radius: var(--r);
  overflow: hidden; width: fit-content;
  opacity: 0; animation: rise 0.6s ease 0.4s forwards;
}
.metric {
  padding: 16px 28px;
  border-right: 1px solid var(--border);
}
.metric:last-child { border-right: none; }
.metric-n {
  font-family: var(--font-serif); font-size: 30px; line-height: 1;
  color: var(--txt); letter-spacing: -1px;
}
.metric-l {
  font-family: var(--font-mono); font-size: 10px;
  color: var(--txt3); letter-spacing: 0.8px;
  text-transform: uppercase; margin-top: 4px;
}

@keyframes rise {
  from { opacity: 0; transform: translateY(16px); }
  to   { opacity: 1; transform: none; }
}

/* ─── MAIN LAYOUT ─── */
.page-body {
  position: relative; z-index: 1;
  max-width: 900px; margin: 0 auto;
  padding: 0 40px 80px;
}

/* ─── FILTER BAR ─── */
.filter-bar {
  display: flex; align-items: center; gap: 8px;
  padding: 28px 0 24px;
  flex-wrap: wrap;
}
.filter-label {
  font-family: var(--font-mono); font-size: 10px;
  letter-spacing: 1px; text-transform: uppercase;
  color: var(--txt3); margin-right: 4px;
}
.filter-btn {
  font-family: var(--font-sans); font-size: 12px; font-weight: 500;
  color: var(--txt2); background: transparent;
  border: 1px solid var(--border); border-radius: 6px;
  padding: 5px 13px; cursor: pointer;
  transition: all 0.15s ease;
  letter-spacing: 0.1px;
}
.filter-btn:hover {
  color: var(--txt); border-color: var(--border-h);
  background: rgba(255,255,255,0.04);
}
.filter-btn.active {
  color: #fff;
  background: var(--accent);
  border-color: var(--accent);
}

/* ─── SECTION HEADING ─── */
.section-head {
  display: flex; align-items: baseline; gap: 12px;
  margin-bottom: 14px; padding-top: 8px;
}
.section-head h2 {
  font-family: var(--font-sans); font-size: 11px; font-weight: 600;
  letter-spacing: 1.8px; text-transform: uppercase;
  color: var(--txt3);
}
.section-head .count {
  font-family: var(--font-mono); font-size: 10px;
  color: var(--txt3);
}
.section-divider {
  flex: 1; height: 1px; background: var(--border);
}

/* ─── CARD GRID ─── */
.cards-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1px;
  background: var(--border);
  border: 1px solid var(--border);
  border-radius: var(--r);
  overflow: hidden;
  margin-bottom: 48px;
}

.os-card {
  display: block; text-decoration: none; color: inherit;
  background: var(--surface);
  padding: 22px 22px 20px;
  transition: background 0.15s ease;
  position: relative;
  overflow: hidden;
}
.os-card::after {
  content: '';
  position: absolute; top: 0; left: 0; right: 0;
  height: 2px;
  background: var(--cat-color, transparent);
  opacity: 0;
  transition: opacity 0.2s ease;
}
.os-card:hover {
  background: #111520;
}
.os-card:hover::after { opacity: 1; }

.card-header {
  display: flex; align-items: flex-start;
  justify-content: space-between; gap: 10px;
  margin-bottom: 14px;
}
.card-icon-wrap {
  width: 36px; height: 36px; border-radius: 8px;
  background: rgba(255,255,255,0.04);
  border: 1px solid var(--border);
  display: flex; align-items: center; justify-content: center;
  font-size: 18px; flex-shrink: 0;
  transition: transform 0.2s ease;
}
.os-card:hover .card-icon-wrap {
  transform: scale(1.08);
}

.card-arrow {
  width: 24px; height: 24px; border-radius: 5px;
  border: 1px solid var(--border);
  display: flex; align-items: center; justify-content: center;
  color: var(--txt3); font-size: 11px;
  transition: all 0.2s ease; flex-shrink: 0;
  margin-top: 2px;
}
.os-card:hover .card-arrow {
  background: var(--cat-color, var(--accent));
  border-color: var(--cat-color, var(--accent));
  color: #fff;
  transform: translate(1px, -1px);
}

.card-name {
  font-family: var(--font-sans); font-weight: 600; font-size: 14px;
  color: var(--txt); letter-spacing: -0.2px;
  margin-bottom: 5px; line-height: 1.3;
}
.card-desc {
  font-size: 12px; color: var(--txt2); font-weight: 300;
  line-height: 1.65;
  display: -webkit-box; -webkit-line-clamp: 2;
  -webkit-box-orient: vertical; overflow: hidden;
}

.card-footer {
  display: flex; align-items: center;
  justify-content: space-between; gap: 8px;
  margin-top: 16px;
  padding-top: 13px;
  border-top: 1px solid var(--border);
}
.card-source {
  font-family: var(--font-mono); font-size: 10px;
  color: var(--txt3); letter-spacing: 0.2px;
  white-space: nowrap; overflow: hidden;
  text-overflow: ellipsis;
}
.card-tag {
  font-family: var(--font-mono); font-size: 9.5px;
  color: var(--cat-color, var(--accent));
  padding: 2px 7px; border-radius: 4px;
  border: 1px solid currentColor;
  opacity: 0.7; flex-shrink: 0;
  letter-spacing: 0.3px;
}

/* Category color custom props */
.win  { --cat-color: var(--win);  }
.ubu  { --cat-color: var(--ubu);  }
.mint { --cat-color: var(--mint); }
.fed  { --cat-color: var(--fed);  }
.deb  { --cat-color: var(--deb);  }
.arch { --cat-color: var(--arch); }
.mnj  { --cat-color: var(--mnj);  }
.ele  { --cat-color: var(--ele);  }
.chr  { --cat-color: var(--chr);  }
.oth  { --cat-color: var(--oth);  }

/* ─── HIDDEN ─── */
.os-card.hidden { display: none; }

/* ─── EMPTY STATE ─── */
.empty-state {
  display: none; text-align: center;
  padding: 64px 24px; color: var(--txt3);
  font-size: 13px; border: 1px solid var(--border);
  border-radius: var(--r);
}
.empty-state.visible { display: block; }

/* ─── FOOTER ─── */
footer {
  position: relative; z-index: 1;
  border-top: 1px solid var(--border);
  max-width: 900px; margin: 0 auto;
  padding: 28px 40px;
  display: flex; align-items: center; justify-content: space-between;
  gap: 20px;
}
.ft-left {
  font-family: var(--font-sans); font-weight: 600;
  font-size: 14px; letter-spacing: -0.2px;
}
.ft-left span {
  color: var(--accent);
}
.ft-right {
  font-family: var(--font-mono); font-size: 10px;
  color: var(--txt3); text-align: right;
  line-height: 1.8; letter-spacing: 0.2px;
}

/* ─── RESPONSIVE ─── */
@media (max-width: 720px) {
  nav { padding: 0 20px; }
  .hero, .page-body { padding-left: 20px; padding-right: 20px; }
  .hero { padding-top: 48px; padding-bottom: 40px; }
  .cards-grid { grid-template-columns: repeat(2, 1fr); }
  .hero-metrics { flex-wrap: wrap; }
  footer { flex-direction: column; align-items: flex-start; padding: 24px 20px; }
  .ft-right { text-align: left; }
}
@media (max-width: 480px) {
  .cards-grid { grid-template-columns: 1fr; }
  .hero-title { font-size: 42px; }
}

/* ─── AD UNITS ─── */
.ad-unit {
  width: 100%; overflow: hidden;
  border: 1px solid var(--border);
  border-radius: var(--r);
  background: var(--surface);
  display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  position: relative; color: var(--txt3);
}
.ad-unit .ad-label {
  position: absolute; top: 7px; left: 10px;
  font-family: var(--font-mono); font-size: 9px;
  letter-spacing: 1px; text-transform: uppercase;
  color: var(--txt3); opacity: 0.5;
}
/* Leaderboard — below hero */
.ad-leaderboard {
  height: 90px; margin-bottom: 0;
}
/* Rectangle — between sections */
.ad-rectangle {
  height: 120px; margin-bottom: 48px;
}
/* Banner — above footer */
.ad-banner {
  height: 90px; margin: 0 auto 0;
  max-width: 900px;
  border-left: none; border-right: none; border-bottom: none;
  border-radius: 0; border-top: 1px solid var(--border);
}
/* Inner adsense slot fills the unit */
.ad-unit ins.adsbygoogle {
  display: block; width: 100%; height: 100%;
}
</style>

</head>
<body>

<nav>
  <a class="logo" href="#">
    <div class="logo-mark">⬡</div>
    Riche Tiger <em>/ OS Vault</em>
  </a>
  <div class="nav-badge">
    <span class="live-dot"></span>
    25 official links
  </div>
</nav>

<header class="hero">
  <div class="hero-kicker">The Complete OS Archive</div>
  <h1 class="hero-title">Every OS.<br><em>One place.</em></h1>
  <p class="hero-sub">
    Direct, verified links to official operating system downloads.
    No mirrors, no trackers, no bloat — just the real thing.
  </p>
  <div class="hero-metrics">
    <div class="metric">
      <div class="metric-n">25</div>
      <div class="metric-l">ISO Links</div>
    </div>
    <div class="metric">
      <div class="metric-n">13</div>
      <div class="metric-l">Distros</div>
    </div>
    <div class="metric">
      <div class="metric-n">100%</div>
      <div class="metric-l">Official</div>
    </div>
    <div class="metric">
      <div class="metric-n">Free*</div>
      <div class="metric-l">(*mostly)</div>
    </div>
  </div>
</header>

<div class="page-body" style="padding-top:24px;padding-bottom:0;">
  <div class="ad-unit ad-leaderboard">
    <span class="ad-label">Advertisement</span>
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-7709827809223128"
         data-ad-slot="6182826622"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
  </div>
</div>

<main class="page-body">

  <div class="filter-bar">
    <span class="filter-label">Filter</span>
    <button class="filter-btn active" data-filter="all">All</button>
    <button class="filter-btn" data-filter="win">Windows</button>
    <button class="filter-btn" data-filter="linux">Linux</button>
    <button class="filter-btn" data-filter="chr">Chrome OS</button>
    <button class="filter-btn" data-filter="oth">Specialty</button>
  </div>

  <div class="section-wrap" data-group="win">
    <div class="section-head">
      <h2>Windows</h2>
      <span class="count"></span>
      <div class="section-divider"></div>
    </div>
    <div class="cards-grid" id="grid-win"></div>
  </div>

  <div class="ad-unit ad-rectangle">
    <span class="ad-label">Advertisement</span>
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-7709827809223128"
         data-ad-slot="6182826622"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
  </div>

  <div class="section-wrap" data-group="linux">
    <div class="section-head">
      <h2>Linux</h2>
      <span class="count"></span>
      <div class="section-divider"></div>
    </div>
    <div class="cards-grid" id="grid-linux"></div>
  </div>

  <div class="ad-unit ad-rectangle">
    <span class="ad-label">Advertisement</span>
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-7709827809223128"
         data-ad-slot="6182826622"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
  </div>

  <div class="section-wrap" data-group="chr">
    <div class="section-head">
      <h2>Chrome OS</h2>
      <span class="count"></span>
      <div class="section-divider"></div>
    </div>
    <div class="cards-grid" id="grid-chr"></div>
  </div>

  <div class="section-wrap" data-group="oth">
    <div class="section-head">
      <h2>Specialty &amp; Experimental</h2>
      <span class="count"></span>
      <div class="section-divider"></div>
    </div>
    <div class="cards-grid" id="grid-oth"></div>
  </div>

  <div class="empty-state" id="emptyState">No results for that filter.</div>

</main>

<div class="ad-unit ad-banner">
  <span class="ad-label">Advertisement</span>
  <ins class="adsbygoogle"
       style="display:block"
       data-ad-client="ca-pub-7709827809223128"
       data-ad-slot="6182826622"
       data-ad-format="auto"
       data-full-width-responsive="true"></ins>
  <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
</div>

<footer>
  <div class="ft-left">Riche <span>Tiger</span></div>
  <div class="ft-right">
    25 ISO links · 13 Distributions<br>
    All links official · No tracking
  </div>
</footer>

<script>
const CARDS = [
  // Windows
  { name:'Windows 10', icon:'🪟', desc:'Official ISO direct from Microsoft. Multi-edition, no third-party tools required.', tag:'Microsoft', src:'microsoft.com', cls:'win', group:'win', href:'https://www.microsoft.com/en-in/software-download/windows10ISO' },
  { name:'Windows 11', icon:'🪟', desc:'Redesigned Start menu, Snap Layouts, Android app support, TPM 2.0 security baseline.', tag:'Latest', src:'microsoft.com', cls:'win', group:'win', href:'https://www.microsoft.com/en-in/software-download/windows11' },
  { name:'Win 7 Pro x64', icon:'📀', desc:'Windows 7 Pro SP1 build 7601.17514. 64-bit for legacy hardware environments.', tag:'Legacy', src:'os.click', cls:'win', group:'win', href:'https://os.click/en/Windows:Windows_7:7601.17514:Professional:en-us:x64' },
  { name:'Win 7 Pro x86', icon:'💾', desc:'Windows 7 Pro SP1 build 7601.17514. 32-bit for maximum legacy compatibility.', tag:'Legacy', src:'os.click', cls:'win', group:'win', href:'https://os.click/en/Windows:Windows_7:7601.17514:Professional:en-us:x86' },
  // Linux
  { name:'Ubuntu Desktop', icon:'🟠', desc:"World's most popular Linux desktop. Polished GNOME shell, LTS release cycle, massive package library.", tag:'LTS', src:'ubuntu.com', cls:'ubu', group:'linux', href:'https://ubuntu.com/download/desktop' },
  { name:'Mint Cinnamon', icon:'🖥️', desc:'Flagship Linux Mint edition. The most approachable desktop for newcomers — familiar and rock-solid.', tag:'Recommended', src:'linuxmint.com', cls:'mint', group:'linux', href:'https://linuxmint.com/edition.php?id=326' },
  { name:'Mint MATE', icon:'🖼️', desc:'Classic MATE desktop on Ubuntu base. Lightweight, stable, and time-tested for older hardware.', tag:'Classic', src:'linuxmint.com', cls:'mint', group:'linux', href:'https://linuxmint.com/edition.php?id=327' },
  { name:'Mint Xfce', icon:'⚡', desc:"Linux Mint's fastest edition. Xfce desktop stays snappy on machines with limited resources.", tag:'Lightweight', src:'linuxmint.com', cls:'mint', group:'linux', href:'https://linuxmint.com/edition.php?id=328' },
  { name:'Fedora', icon:'🔵', desc:"Red Hat's community distro. Cutting-edge GNOME, Wayland-first, built for developers.", tag:'RPM', src:'fedoraproject.org', cls:'fed', group:'linux', href:'https://fedoraproject.org/misc' },
  { name:'Debian', icon:'🌀', desc:'The universal OS. Foundation for Ubuntu and hundreds of derivatives. Unmatched stability and purity.', tag:'Ultra Stable', src:'debian.org', cls:'deb', group:'linux', href:'https://www.debian.org/distrib/' },
  { name:'Arch Linux', icon:'🏔️', desc:'Minimal rolling-release base. Build it your way. Home of the legendary AUR package repository.', tag:'Rolling', src:'archlinux.org', cls:'arch', group:'linux', href:'https://archlinux.org/download/' },
  { name:'Manjaro KDE', icon:'🟢', desc:'KDE Plasma on a friendly Arch base. Polished, customizable, and powerful. v26.0.4.', tag:'KDE Plasma', src:'manjaro.org', cls:'mnj', group:'linux', href:'https://download.manjaro.org/kde/26.0.4/manjaro-kde-26.0.4-260327-linux618.iso' },
  { name:'Manjaro Xfce', icon:'⚡', desc:'Lightweight and snappy. Xfce desktop with Manjaro driver management. v26.0.4.', tag:'Lightweight', src:'manjaro.org', cls:'mnj', group:'linux', href:'https://download.manjaro.org/xfce/26.0.4/manjaro-xfce-26.0.4-260327-linux618.iso' },
  { name:'Manjaro GNOME', icon:'⭕', desc:'Sleek GNOME aesthetics with Manjaro polish. Modern Wayland-first experience. v26.0.4.', tag:'Wayland', src:'manjaro.org', cls:'mnj', group:'linux', href:'https://download.manjaro.org/gnome/26.0.4/manjaro-gnome-26.0.4-260327-linux618.iso' },
  { name:'Manjaro Cinnamon', icon:'🌿', desc:'Cinnamon desktop on Arch/Manjaro base. Rolling releases with a familiar Mint-style feel. v25.0.3.', tag:'Cinnamon', src:'manjaro.org', cls:'mnj', group:'linux', href:'https://download.manjaro.org/cinnamon/25.0.3/manjaro-cinnamon-25.0.3-250609-linux612.iso' },
  { name:'Manjaro i3', icon:'⬜', desc:'Keyboard-driven tiling WM. Pure productivity — infinitely configurable, no mouse required. v25.0.3.', tag:'Tiling WM', src:'manjaro.org', cls:'mnj', group:'linux', href:'https://download.manjaro.org/i3/25.0.3/manjaro-i3-25.0.3-250609-linux612.iso' },
  { name:'Manjaro Sway', icon:'🌊', desc:'Wayland-native i3-compatible tiling compositor. The modern keyboard-first workflow. v25.0.3.', tag:'Wayland', src:'manjaro-sway.download', cls:'mnj', group:'linux', href:'https://manjaro-sway.download/' },
  { name:'elementary OS', icon:'🔷', desc:'macOS-level polish on Linux. Pantheon desktop is arguably the most refined DE available. Pay what you want.', tag:'Pay What You Want', src:'elementary.io', cls:'ele', group:'linux', href:'https://elementary.io/' },
  // Chrome OS
  { name:'Chrome OS', icon:'🌐', desc:"Google's cloud-first Chromebook OS. Fast boot, Android apps, Linux dev environment built in.", tag:'Official', src:'chromeos.google', cls:'chr', group:'chr', href:'https://chromeos.google/#platforms' },
  { name:'Chromium OS', icon:'⚙️', desc:'Open-source foundation of Chrome OS. Runs on standard PC hardware — no Chromebook needed.', tag:'Open Source', src:'chromium.org', cls:'chr', group:'chr', href:'https://www.chromium.org/getting-involved/download-chromium/' },
  // Specialty
  { name:'KolibriOS', icon:'🦋', desc:'A complete GUI OS under 1.5 MB, written in x86 assembly. Boots from a floppy disk.', tag:'< 1.5 MB', src:'kolibrios.org', cls:'oth', group:'oth', href:'https://www.kolibrios.org/en/download' },
  { name:'FreeDOS', icon:'💾', desc:'Free, open-source MS-DOS compatible OS. Run classic games, old software, or flash BIOS chips.', tag:'MS-DOS', src:'freedos.org', cls:'oth', group:'oth', href:'https://www.freedos.org/download/' },
  { name:'ReactOS', icon:'🔬', desc:'Free Windows-compatible OS built from scratch. Runs Windows software without any Microsoft code.', tag:'Windows API', src:'reactos.org', cls:'oth', group:'oth', href:'https://reactos.org/download/' },
  { name:'FreeBSD', icon:'😈', desc:'Legendary Unix powering PlayStation and Netflix. Unparalleled network stack and native ZFS.', tag:'BSD Unix', src:'freebsd.org', cls:'oth', group:'oth', href:'https://www.freebsd.org/where/' },
  { name:'Haiku OS', icon:'🌸', desc:'The spiritual successor to BeOS. Blazing fast, unique architecture, and delightfully responsive.', tag:'Experimental', src:'haiku-os.org', cls:'oth', group:'oth', href:'https://www.haiku-os.org/get-haiku/' },
];

// Map group → grid id
const GROUP_GRID = {
  win:   'grid-win',
  linux: 'grid-linux',
  chr:   'grid-chr',
  oth:   'grid-oth',
};

// Build cards
function buildCard(c) {
  const el = document.createElement('a');
  el.className = `os-card ${c.cls}`;
  el.href = c.href;
  el.target = '_blank';
  el.rel = 'noopener';
  el.dataset.group = c.group;
  el.innerHTML = `
    <div class="card-header">
      <div class="card-icon-wrap">${c.icon}</div>
      <div class="card-arrow">↗</div>
    </div>
    <div class="card-name">${c.name}</div>
    <div class="card-desc">${c.desc}</div>
    <div class="card-footer">
      <span class="card-source">${c.src}</span>
      <span class="card-tag">${c.tag}</span>
    </div>
  `;
  return el;
}

CARDS.forEach(c => {
  const gridEl = document.getElementById(GROUP_GRID[c.group]);
  if (gridEl) gridEl.appendChild(buildCard(c));
});

// Update section counts
document.querySelectorAll('.section-wrap').forEach(section => {
  const group = section.dataset.group;
  const count = section.querySelectorAll('.os-card').length;
  section.querySelector('.count').textContent = `${count} items`;
});

// Filter logic
const filterBtns = document.querySelectorAll('.filter-btn');
const sections = document.querySelectorAll('.section-wrap');
const emptyState = document.getElementById('emptyState');

filterBtns.forEach(btn => {
  btn.addEventListener('click', () => {
    filterBtns.forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    const f = btn.dataset.filter;

    let anyVisible = false;
    sections.forEach(sec => {
      const g = sec.dataset.group;
      const show = f === 'all' || f === g || (f === 'linux' && g === 'linux');
      sec.style.display = show ? '' : 'none';
      if (show) anyVisible = true;
    });

    emptyState.classList.toggle('visible', !anyVisible);
  });
});
</script>
</body>
</html>
