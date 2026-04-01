<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Galeria — 114 Metropolitan Division</title>
<link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav id="nav">
  <div class="nav-left">
    <div class="nav-badge">114</div>
    <div class="nav-brand-text">
      <strong>Metropolitan Division</strong>
      <span>Los Santos Police Department</span>
    </div>
  </div>
  <ul class="nav-links">
    <li><a href="index.html">Start</a></li>
    <li><a href="operacje.html">Operacje</a></li>
    <li><a href="mapa.html">Mapa</a></li>
    <li><a href="galeria.html">Galeria</a></li>
    <li><a href="rekrutacja.html">Rekrutacja</a></li>
  </ul>
  <a href="https://forms.gle/yK4qGYhWCVDvAfTV6" target="_blank" class="nav-apply">▶ Aplikuj</a>
</nav>

<div id="alert-bar">
  🔴 REKRUTACJA OTWARTA — Termin: 06.03.2026 &nbsp;|&nbsp;
  <a href="https://forms.gle/yK4qGYhWCVDvAfTV6" target="_blank">Złóż aplikację →</a>
</div>

<div class="ticker">
  <div class="ticker-inner">
    <span class="ticker-item"><strong>114 MD</strong> · Metropolitan Division · LSPD · EST. 1933</span>
    <span class="ticker-item">Commander: <strong>Mark Clakson</strong> · 114 Station</span>
    <span class="ticker-item"><strong>REKRUTACJA OTWARTA</strong> · Termin: 06.03.2026</span>
    <span class="ticker-item">To Protect and To Serve · <strong>Los Santos</strong></span>
    <span class="ticker-item"><strong>114 MD</strong> · Metropolitan Division · LSPD · EST. 1933</span>
    <span class="ticker-item">Commander: <strong>Mark Clakson</strong> · 114 Station</span>
    <span class="ticker-item"><strong>REKRUTACJA OTWARTA</strong> · Termin: 06.03.2026</span>
    <span class="ticker-item">To Protect and To Serve · <strong>Los Santos</strong></span>
  </div>
</div>

<div class="page-wrap">
  <div class="gallery-header">
    <div class="label">// Dokumentacja wizualna</div>
    <h2 class="section-h">Galeria <em>Jednostki</em></h2>
    <p style="color:var(--dim); font-size:0.9rem; margin-top:0.5rem;">Materiały z działań, szkoleń i codziennej służby Metropolitan Division. Kliknij zdjęcie, aby powiększyć.</p>
  </div>

  <div class="gallery-grid">
    <div class="gallery-cell wide tall">
      <img src="assets/img/team.jpg" alt="Drużyna MD">
      <div class="gallery-cell-cap">Drużyna Metropolitan Division · Elysian Island</div>
    </div>
    <div class="gallery-cell">
      <img src="assets/img/swat-night.jpg" alt="SWAT noc">
      <div class="gallery-cell-cap">Nocna operacja SWAT</div>
    </div>
    <div class="gallery-cell">
      <img src="assets/img/cockpit.jpg" alt="Cockpit">
      <div class="gallery-cell-cap">Air Support · Baza nocna LSPD</div>
    </div>
    <div class="gallery-cell">
      <img src="assets/img/port1.jpg" alt="Port 1">
      <div class="gallery-cell-cap">Operacja portowa · Elysian Island</div>
    </div>
    <div class="gallery-cell">
      <img src="assets/img/port2.jpg" alt="Port 2">
      <div class="gallery-cell-cap">Detective Bureau · Port LS</div>
    </div>
    <div class="gallery-cell wide">
      <img src="assets/img/crime-scene.jpg" alt="Zabezpieczenie terenu">
      <div class="gallery-cell-cap">Zabezpieczenie miejsca zdarzenia · Sandy Shores</div>
    </div>
    <div class="gallery-cell tall">
      <img src="assets/img/van.jpg" alt="Metro Van">
      <div class="gallery-cell-cap">Metro Van · Operacja nocna · Port</div>
    </div>
    <div class="gallery-cell wide">
      <img src="assets/img/logo.jpg" alt="Godło 114" style="object-fit:contain; background:#0b0d12;">
      <div class="gallery-cell-cap">Godło Metropolitan Division · EST. 1933</div>
    </div>
  </div>
</div>

<!-- LIGHTBOX -->
<div id="lightbox" onclick="closeLightbox()">
  <img id="lbImg" src="" alt="Podgląd zdjęcia">
</div>

<footer>
  <div class="footer-inner">
    <div class="footer-logo"><span>114</span> Metropolitan Division</div>
    <div class="footer-text">© 2026 Los Santos Police Department · EST. 1933 · To Protect and To Serve</div>
    <div class="footer-text">FiveM Roleplay · Los Santos</div>
  </div>
</footer>

<script src="js/main.js"></script>
</body>
</html>
