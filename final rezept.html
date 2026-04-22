
<!DOCTYPE html>

<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>健康レシピ · Gesundes Rezeptbuch</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@300;400;700&family=Shippori+Mincho:wght@400;600;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #1a1410;
    --paper: #f5f0e8;
    --rice: #faf7f0;
    --matcha: #5a7a4a;
    --matcha-light: #8aaa72;
    --gochujang: #c8402a;
    --gochujang-light: #e8705a;
    --miso: #c8922a;
    --miso-light: #e8b85a;
    --accent: #2a5a6a;
    --border: rgba(26,20,16,0.12);
  }

- { margin: 0; padding: 0; box-sizing: border-box; }

body {
background: var(–paper);
color: var(–ink);
font-family: ‘DM Sans’, sans-serif;
min-height: 100vh;
}

/* TEXTURE OVERLAY */
body::before {
content: ‘’;
position: fixed;
inset: 0;
background-image: url(“data:image/svg+xml,%3Csvg xmlns=‘http://www.w3.org/2000/svg’ width=‘300’ height=‘300’%3E%3Cfilter id=‘noise’%3E%3CfeTurbulence type=‘fractalNoise’ baseFrequency=‘0.75’ numOctaves=‘4’ stitchTiles=‘stitch’/%3E%3CfeColorMatrix type=‘saturate’ values=‘0’/%3E%3C/filter%3E%3Crect width=‘300’ height=‘300’ filter=‘url(%23noise)’ opacity=‘0.04’/%3E%3C/svg%3E”);
pointer-events: none;
z-index: 1000;
}

/* HEADER */
header {
padding: 60px 40px 40px;
max-width: 900px;
margin: 0 auto;
position: relative;
}

.header-kana {
font-family: ‘Noto Serif JP’, serif;
font-size: 13px;
font-weight: 300;
letter-spacing: 0.3em;
color: var(–matcha);
text-transform: uppercase;
margin-bottom: 12px;
}

h1 {
font-family: ‘Shippori Mincho’, serif;
font-size: clamp(2.4rem, 5vw, 4rem);
font-weight: 800;
line-height: 1.1;
color: var(–ink);
margin-bottom: 16px;
}

h1 span {
color: var(–matcha);
}

.header-sub {
font-size: 15px;
font-weight: 300;
color: rgba(26,20,16,0.55);
max-width: 460px;
line-height: 1.6;
}

.header-divider {
width: 60px;
height: 2px;
background: linear-gradient(90deg, var(–matcha), transparent);
margin: 28px 0;
}

/* NAV TABS */
.nav-wrap {
padding: 0 40px 0;
max-width: 900px;
margin: 0 auto 40px;
}

.nav-tabs {
display: flex;
gap: 8px;
flex-wrap: wrap;
}

.tab-btn {
display: flex;
align-items: center;
gap: 8px;
padding: 10px 20px;
border: 1.5px solid var(–border);
background: var(–rice);
border-radius: 2px;
cursor: pointer;
font-family: ‘DM Sans’, sans-serif;
font-size: 13.5px;
font-weight: 500;
color: rgba(26,20,16,0.55);
transition: all 0.2s;
letter-spacing: 0.01em;
}

.tab-btn:hover {
color: var(–ink);
border-color: rgba(26,20,16,0.3);
}

.tab-btn.active {
background: var(–ink);
color: var(–paper);
border-color: var(–ink);
}

.tab-btn.active.korean { background: var(–gochujang); border-color: var(–gochujang); }
.tab-btn.active.japanese { background: var(–matcha); border-color: var(–matcha); }
.tab-btn.active.brotbox { background: var(–miso); border-color: var(–miso); }

.tab-emoji { font-size: 16px; }

/* CATEGORY SECTION */
.category-section {
display: none;
max-width: 900px;
margin: 0 auto;
padding: 0 40px 80px;
animation: fadeUp 0.35s ease forwards;
}

.category-section.visible { display: block; }

@keyframes fadeUp {
from { opacity: 0; transform: translateY(14px); }
to { opacity: 1; transform: translateY(0); }
}

.section-header {
display: flex;
align-items: flex-end;
gap: 20px;
margin-bottom: 36px;
padding-bottom: 20px;
border-bottom: 1.5px solid var(–border);
}

.section-kanji {
font-family: ‘Noto Serif JP’, serif;
font-size: 52px;
font-weight: 700;
line-height: 1;
opacity: 0.08;
}

.section-title-wrap h2 {
font-family: ‘Shippori Mincho’, serif;
font-size: 1.7rem;
font-weight: 600;
color: var(–ink);
}

.section-title-wrap p {
font-size: 13px;
color: rgba(26,20,16,0.5);
margin-top: 4px;
font-weight: 300;
}

/* RECIPE GRID */
.recipe-grid {
display: grid;
grid-template-columns: repeat(auto-fill, minmax(380px, 1fr));
gap: 24px;
}

/* RECIPE CARD */
.recipe-card {
background: var(–rice);
border: 1.5px solid var(–border);
border-radius: 3px;
overflow: hidden;
cursor: pointer;
transition: transform 0.2s, box-shadow 0.2s;
}

.recipe-card:hover {
transform: translateY(-3px);
box-shadow: 0 12px 40px rgba(26,20,16,0.1);
}

.card-header {
padding: 22px 24px 16px;
display: flex;
justify-content: space-between;
align-items: flex-start;
gap: 12px;
}

.card-title-group {}

.card-kana {
font-family: ‘Noto Serif JP’, serif;
font-size: 11px;
letter-spacing: 0.15em;
color: rgba(26,20,16,0.4);
margin-bottom: 5px;
}

.card-title {
font-family: ‘Shippori Mincho’, serif;
font-size: 1.2rem;
font-weight: 600;
color: var(–ink);
line-height: 1.3;
}

.card-badges {
display: flex;
flex-direction: column;
gap: 5px;
align-items: flex-end;
flex-shrink: 0;
}

.badge {
font-size: 10.5px;
font-weight: 500;
padding: 3px 9px;
border-radius: 1px;
letter-spacing: 0.04em;
}

.badge-time { background: rgba(26,20,16,0.07); color: rgba(26,20,16,0.6); }
.badge-kcal { background: rgba(90,122,74,0.12); color: var(–matcha); }
.badge-cost { background: rgba(200,146,42,0.12); color: var(–miso); }

.card-desc {
padding: 0 24px 16px;
font-size: 13.5px;
color: rgba(26,20,16,0.6);
line-height: 1.65;
font-weight: 300;
}

/* EXPANDABLE */
.card-details {
display: none;
padding: 0 24px 24px;
border-top: 1px solid var(–border);
margin-top: 4px;
padding-top: 20px;
}

.card-details.open { display: block; }

.details-col-wrap {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 20px;
margin-bottom: 16px;
}

.details-label {
font-size: 10.5px;
font-weight: 500;
letter-spacing: 0.12em;
text-transform: uppercase;
color: rgba(26,20,16,0.4);
margin-bottom: 8px;
}

.ingredient-list {
list-style: none;
}

.ingredient-list li {
font-size: 13px;
font-weight: 300;
color: var(–ink);
padding: 4px 0;
border-bottom: 1px dashed rgba(26,20,16,0.08);
display: flex;
justify-content: space-between;
}

.ingredient-list li:last-child { border-bottom: none; }

.ing-qty {
font-weight: 400;
color: rgba(26,20,16,0.45);
font-size: 12px;
}

.steps-list {
list-style: none;
counter-reset: steps;
}

.steps-list li {
counter-increment: steps;
font-size: 13px;
font-weight: 300;
color: var(–ink);
padding: 6px 0 6px 28px;
position: relative;
border-bottom: 1px dashed rgba(26,20,16,0.08);
line-height: 1.55;
}

.steps-list li:last-child { border-bottom: none; }

.steps-list li::before {
content: counter(steps);
position: absolute;
left: 0;
top: 6px;
font-size: 10px;
font-weight: 700;
width: 18px;
height: 18px;
border-radius: 50%;
display: flex;
align-items: center;
justify-content: center;
color: var(–paper);
}

.korean .steps-list li::before { background: var(–gochujang); }
.japanese .steps-list li::before { background: var(–matcha); }
.brotbox .steps-list li::before { background: var(–miso); }

.tip-box {
margin-top: 16px;
padding: 12px 16px;
border-left: 3px solid;
background: rgba(26,20,16,0.03);
font-size: 12.5px;
font-weight: 300;
color: rgba(26,20,16,0.65);
line-height: 1.6;
}

.korean .tip-box { border-color: var(–gochujang-light); }
.japanese .tip-box { border-color: var(–matcha-light); }
.brotbox .tip-box { border-color: var(–miso-light); }

.tip-box strong { font-weight: 500; color: var(–ink); }

.toggle-btn {
margin-top: 12px;
display: inline-flex;
align-items: center;
gap: 6px;
font-size: 12.5px;
font-weight: 500;
color: rgba(26,20,16,0.45);
background: none;
border: none;
cursor: pointer;
transition: color 0.2s;
letter-spacing: 0.02em;
}

.toggle-btn:hover { color: var(–ink); }

.toggle-icon { transition: transform 0.25s; font-size: 10px; }
.toggle-icon.rotated { transform: rotate(180deg); }

/* FOOTER */
footer {
max-width: 900px;
margin: 0 auto;
padding: 20px 40px 60px;
display: flex;
justify-content: space-between;
align-items: center;
border-top: 1.5px solid var(–border);
}

.footer-kana {
font-family: ‘Noto Serif JP’, serif;
font-size: 18px;
color: rgba(26,20,16,0.12);
}

.footer-text {
font-size: 12px;
font-weight: 300;
color: rgba(26,20,16,0.35);
letter-spacing: 0.03em;
}

@media (max-width: 640px) {
header, .nav-wrap, .category-section { padding-left: 20px; padding-right: 20px; }
.recipe-grid { grid-template-columns: 1fr; }
.details-col-wrap { grid-template-columns: 1fr; }
h1 { font-size: 2rem; }
}
</style>

</head>
<body>

<header>
  <div class="header-kana">健康 · 스포츠 · Gesund & Sportlich</div>
  <h1>Mein<br><span>Rezeptbuch</span></h1>
  <div class="header-divider"></div>
  <p class="header-sub">Einfache, günstige Gerichte aus der koreanischen und japanischen Küche – plus schnelle Brotbox-Ideen für unterwegs.</p>
</header>

<div class="nav-wrap">
  <div class="nav-tabs">
    <button class="tab-btn korean active" onclick="showTab('korean', this)">
      <span class="tab-emoji">🇰🇷</span> Koreanisch
    </button>
    <button class="tab-btn japanese" onclick="showTab('japanese', this)">
      <span class="tab-emoji">🇯🇵</span> Japanisch
    </button>
    <button class="tab-btn brotbox" onclick="showTab('brotbox', this)">
      <span class="tab-emoji">🥡</span> Brotbox
    </button>
  </div>
</div>

<!-- =================== KOREANISCH =================== -->

<section id="korean" class="category-section visible korean">
  <div class="section-header">
    <div class="section-kanji">한식</div>
    <div class="section-title-wrap">
      <h2>Koreanische Küche</h2>
      <p>Würzig, fermentiert, reich an Gemüse und Proteinen</p>
    </div>
  </div>
  <div class="recipe-grid">

```
<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">비빔밥 · Bibimbap</div>
      <div class="card-title">Bibimbap mit Ei & Gemüse</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 25 Min</span>
      <span class="badge badge-kcal">~480 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Der koreanische Klassiker: buntes Gemüse auf Reis mit würziger Gochujang-Sauce und einem Spiegelei. Protein-reich und sättigend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Person)</div>
        <ul class="ingredient-list">
          <li><span>Reis (gekocht)</span><span class="ing-qty">200 g</span></li>
          <li><span>Ei</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Spinat</span><span class="ing-qty">80 g</span></li>
          <li><span>Karotte</span><span class="ing-qty">½ Stk</span></li>
          <li><span>Zucchini</span><span class="ing-qty">½ Stk</span></li>
          <li><span>Sojasprossen</span><span class="ing-qty">50 g</span></li>
          <li><span>Gochujang-Paste</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesam</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Karotte und Zucchini in feine Streifen schneiden und je separat in etwas Öl kurz anbraten, mit Salz würzen.</li>
          <li>Spinat 1 Min. blanchieren, ausdrücken und mit Sesamöl und Salz würzen. Sprossen ebenfalls kurz blanchieren.</li>
          <li>Sauce: Gochujang, Sesamöl, Sojasauce und 1 TL Wasser verrühren.</li>
          <li>Reis in eine Schüssel geben, Gemüse fächerartig darauf anrichten.</li>
          <li>Spiegelei braten, obenauf setzen. Sauce darüber, Sesam bestreuen und gut vermischen.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Reste-Gericht! Verwende beliebiges Gemüse aus dem Kühlschrank. Für extra Protein einfach mehr Ei oder etwas Tofu ergänzen.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">된장찌개 · Doenjang Jjigae</div>
      <div class="card-title">Koreanische Miso-Suppe</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~280 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Herzhafte Fermentationssuppe mit Tofu, Zucchini und Pilzen. Probiotikareich, wärmend und unglaublich einfach.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Doenjang (Fermentierte Sojapaste)</span><span class="ing-qty">2 EL</span></li>
          <li><span>Fester Tofu</span><span class="ing-qty">150 g</span></li>
          <li><span>Zucchini</span><span class="ing-qty">½ Stk</span></li>
          <li><span>Champignons</span><span class="ing-qty">80 g</span></li>
          <li><span>Frühlingszwiebel</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">2 Zehen</span></li>
          <li><span>Wasser oder Gemüsebrühe</span><span class="ing-qty">500 ml</span></li>
          <li><span>Gochugaru (Chilipulver, optional)</span><span class="ing-qty">½ TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Wasser aufkochen, Doenjang einrühren bis es sich auflöst.</li>
          <li>Tofu in Würfel, Zucchini in Halbmonde, Pilze in Scheiben schneiden.</li>
          <li>Knoblauch fein hacken, alles in die Brühe geben.</li>
          <li>10 Min. bei mittlerer Hitze köcheln lassen.</li>
          <li>Mit Frühlingszwiebeln garnieren, optional Chilipulver nach Wunsch.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Doenjang gibt es in asiatischen Supermärkten. Alternativ funktioniert japanische Miso-Paste – Ergebnis leicht milder, aber genauso lecker.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">계란볶음밥 · Gyeran Bokkeum-bap</div>
      <div class="card-title">Koreanischer Eirreis</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~420 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Gebratener Reis mit Ei, Sesamöl und Kimchi. Das ultimative schnelle Gericht für Reste-Reis – in 15 Minuten fertig.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Person)</div>
        <ul class="ingredient-list">
          <li><span>Gekochter Reis (vom Vortag)</span><span class="ing-qty">200 g</span></li>
          <li><span>Eier</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Kimchi (oder Sauerkraut)</span><span class="ing-qty">60 g</span></li>
          <li><span>Frühlingszwiebel</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 EL</span></li>
          <li><span>Neutrales Öl</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sesam</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Öl in Pfanne erhitzen, Kimchi kurz anbraten.</li>
          <li>Reste-Reis dazugeben und bei hoher Hitze 3–4 Min. braten bis er leicht knusprig ist.</li>
          <li>Eine Mulde schieben, Eier aufschlagen und verrühren, dann untermischen.</li>
          <li>Sojasauce und Sesamöl einrühren.</li>
          <li>Mit Frühlingszwiebeln und Sesam servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Reste-Reis aus dem Kühlschrank funktioniert am besten – frischer Reis macht den Fried Rice matschig. Kimchi gibt es im Asia-Laden oder du fermentierst Weißkohl selbst!</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">잡채 · Japchae</div>
      <div class="card-title">Glasnudeln mit Gemüse</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 30 Min</span>
      <span class="badge badge-kcal">~380 kcal</span>
      <span class="badge badge-cost">€ mittel</span>
    </div>
  </div>
  <p class="card-desc">Süßkartoffel-Glasnudeln mit buntem Gemüse und Sojasauce – leicht, farbenfroh, glutenfrei und super sättigend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Dangmyeon (Glasnudeln)</span><span class="ing-qty">120 g</span></li>
          <li><span>Spinat</span><span class="ing-qty">100 g</span></li>
          <li><span>Karotte</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Paprika (bunt)</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Champignons</span><span class="ing-qty">100 g</span></li>
          <li><span>Ei</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">3 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 EL</span></li>
          <li><span>Zucker</span><span class="ing-qty">1 TL</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">2 Zehen</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Glasnudeln nach Packung kochen, abgießen und in mundgerechte Stücke schneiden.</li>
          <li>Gemüse in feine Streifen schneiden, Spinat blanchieren und ausdrücken.</li>
          <li>Alles Gemüse separat in Öl anbraten, würzen.</li>
          <li>Sauce aus Soja, Sesamöl, Zucker, Knoblauch mischen.</li>
          <li>Nudeln, Gemüse und Sauce in einer großen Schüssel vermischen. Sesam darüber.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Japchae schmeckt warm und kalt – perfekt auch für die Brotbox! Dangmyeon gibt es im Asiamarkt, alternativ Mung-Bohnen-Nudeln verwenden.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">순두부찌개 · Sundubu Jjigae</div>
      <div class="card-title">Seidenweiche Tofu-Suppe</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~220 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Würzig-scharfe Suppe mit Seidentofu, Ei und Pilzen. Wärmend, eiweißreich und in 20 Minuten auf dem Tisch.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Seidentofu</span><span class="ing-qty">300 g</span></li>
          <li><span>Ei</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Shiitake-Pilze</span><span class="ing-qty">80 g</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">3 Stk</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">3 Zehen</span></li>
          <li><span>Gochugaru (Chilipulver)</span><span class="ing-qty">1,5 EL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Gemüsebrühe</span><span class="ing-qty">400 ml</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Öl erhitzen, Knoblauch und Gochugaru 1 Min. anrösten bis es duftet.</li>
          <li>Brühe und Sojasauce dazugeben, aufkochen.</li>
          <li>Pilze und Tofu in groben Stücken hineingeben, 5 Min. köcheln.</li>
          <li>Eier direkt in die heiße Suppe aufschlagen, Deckel drauf, 2 Min. garziehen lassen.</li>
          <li>Mit Sesamöl beträufeln und Frühlingszwiebeln garnieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Traditionell in einem kleinen Tonpott serviert. Zu Hause funktioniert jeder kleine Topf. Schärfe ganz nach Geschmack – weniger Gochugaru für eine milde Version.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">시금치나물 · Sigeumchi Namul</div>
      <div class="card-title">Würziger Spinat-Salat</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 10 Min</span>
      <span class="badge badge-kcal">~90 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Blanchierter Spinat mit Knoblauch, Sesamöl und Sesam – die klassische koreanische Beilage (Banchan). Einfacher geht es kaum.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Frischer Spinat</span><span class="ing-qty">300 g</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">2 Zehen</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesam (geröstet)</span><span class="ing-qty">1 TL</span></li>
          <li><span>Salz</span><span class="ing-qty">1 Prise</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Wasser aufkochen, Spinat 30 Sekunden blanchieren.</li>
          <li>Sofort in Eiswasser abschrecken, gut ausdrücken.</li>
          <li>Spinat grob hacken, Knoblauch fein reiben.</li>
          <li>Alles mit Sesamöl, Soja, Knoblauch und Salz vermengen.</li>
          <li>Mit Sesam bestreuen und kalt servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Meal-Prep:</strong> Hält 3 Tage im Kühlschrank – am besten gleich eine große Portion machen und als Beilage zu Reis oder in die Brotbox packen.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">파전 · Pajeon</div>
      <div class="card-title">Koreanischer Frühlingszwiebel-Pfannkuchen</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~310 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Knuspriger herzhafter Pfannkuchen mit Frühlingszwiebeln. Schnell gemacht, als Snack oder leichtes Abendessen perfekt.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Pfannkuchen)</div>
        <ul class="ingredient-list">
          <li><span>Mehl (oder Reismehl)</span><span class="ing-qty">80 g</span></li>
          <li><span>Wasser (kalt)</span><span class="ing-qty">120 ml</span></li>
          <li><span>Ei</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">6 Stk</span></li>
          <li><span>Salz</span><span class="ing-qty">½ TL</span></li>
          <li><span>Neutrales Öl</span><span class="ing-qty">2 EL</span></li>
          <li><span>Sojasauce + Reisessig (Dip)</span><span class="ing-qty">je 1 EL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Mehl, Wasser, Ei und Salz zu einem glatten Teig verrühren (klumpenfrei).</li>
          <li>Frühlingszwiebeln der Länge nach halbieren, in Teig wenden.</li>
          <li>Öl in Pfanne erhitzen (mittel-hoch), Teig mit Zwiebeln hineingeben.</li>
          <li>4–5 Min. goldbraun braten, wenden, nochmals 3 Min. braten.</li>
          <li>In Stücke schneiden, mit Soja-Essig-Dip servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Für extra Knusprigkeit: Teig mit eiskaltem Wasser anrühren. Optional Kimchi, Paprika oder TK-Garnelen in den Teig einarbeiten.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">콩나물국 · Kongnamul Guk</div>
      <div class="card-title">Sojasprossen-Suppe</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~80 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Leichte, klare Suppe mit Sojasprossen – das koreanische Hausmittel gegen Heißhunger und Kater. Kalorienarm und erfrischend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Sojasprossen</span><span class="ing-qty">200 g</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">2 Zehen</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Wasser</span><span class="ing-qty">600 ml</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1,5 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Gochugaru (optional)</span><span class="ing-qty">½ TL</span></li>
          <li><span>Salz & Pfeffer</span><span class="ing-qty">nach Bedarf</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Wasser mit Knoblauch und Sojasauce aufkochen.</li>
          <li>Sojasprossen dazugeben, Deckel drauf – 8 Min. kochen ohne zu rühren (sonst Fischgeruch).</li>
          <li>Erst dann umrühren, mit Salz abschmecken.</li>
          <li>Mit Sesamöl, Frühlingszwiebeln und Gochugaru abschmecken.</li>
          <li>Zu Reis servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Wichtig:</strong> Deckel in den ersten 8 Minuten nicht öffnen – sonst werden die Sprossen unangenehm fischig. Danke an die Koreanische Küchenweisheit! 🙏</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">두부조림 · Dubu Jorim</div>
      <div class="card-title">Würziger gebratener Tofu</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~250 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Knusprig gebratener Tofu in einer würzigen Gochujang-Soja-Glasur. Pflanzenbasiert, proteinreich und absolut süchtig machend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Fester Tofu</span><span class="ing-qty">300 g</span></li>
          <li><span>Gochujang</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">2 EL</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">3 Zehen</span></li>
          <li><span>Zucker</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Wasser</span><span class="ing-qty">3 EL</span></li>
          <li><span>Frühlingszwiebeln + Sesam</span><span class="ing-qty">zum Garnieren</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Tofu in 1 cm dicke Scheiben schneiden, mit Küchenpapier gut trocknen.</li>
          <li>In Öl von beiden Seiten goldbraun braten (je 3–4 Min.).</li>
          <li>Sauce aus Gochujang, Soja, Knoblauch, Zucker, Wasser verrühren.</li>
          <li>Sauce über den Tofu geben, bei mittlerer Hitze einglasieren (2–3 Min.).</li>
          <li>Mit Sesamöl, Frühlingszwiebeln und Sesam servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Je trockener der Tofu vor dem Braten, desto knuspriger wird er. Ruhig 15–30 Min. zwischen Küchentüchern pressen. Auch kalt als Banchan (Beilage) oder in der Brotbox super.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">미역국 · Miyeok Guk</div>
      <div class="card-title">Seetang-Suppe</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~100 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Die koreanische Geburtstagssuppe mit Wakame-Seetang: reich an Jod, Kalzium und Antioxidantien. Nährend und unglaublich einfach.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Getrockneter Wakame-Seetang</span><span class="ing-qty">15 g</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">3 Zehen</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">2 EL</span></li>
          <li><span>Wasser</span><span class="ing-qty">700 ml</span></li>
          <li><span>Salz</span><span class="ing-qty">nach Bedarf</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Wakame 10 Min. in kaltem Wasser einweichen, dann abgießen und grob schneiden.</li>
          <li>Sesamöl in Topf erhitzen, Knoblauch und Wakame 2 Min. anbraten.</li>
          <li>Wasser dazugeben, aufkochen, dann 10 Min. köcheln lassen.</li>
          <li>Mit Sojasauce und Salz abschmecken.</li>
          <li>Mit Reis servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Wissenswertes:</strong> In Korea isst man diese Suppe traditionell am Geburtstag als Dank an die Mutter. Wakame gibt es getrocknet günstig im Asialaden – eine Packung reicht Monate.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">오이무침 · Oi Muchim</div>
      <div class="card-title">Würziger Gurken-Salat</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 10 Min</span>
      <span class="badge badge-kcal">~60 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Scharf-säuerlicher Gurkensalat mit Gochugaru, Knoblauch und Essig. Fertig in 10 Minuten – knackig, frisch und süchtig machend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Salatgurke</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Gochugaru (Chiliflocken)</span><span class="ing-qty">1 TL</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">1 Zehe</span></li>
          <li><span>Reisessig</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Zucker</span><span class="ing-qty">½ TL</span></li>
          <li><span>Sesam + Frühlingszwiebeln</span><span class="ing-qty">je 1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Gurke in dünne Scheiben oder Halbmonde schneiden.</li>
          <li>Mit 1 TL Salz vermischen und 5 Min. stehen lassen, dann ausdrücken.</li>
          <li>Alle Zutaten für das Dressing verrühren.</li>
          <li>Gurken und Dressing gut vermengen.</li>
          <li>Sofort servieren oder 30 Min. ziehen lassen für intensiveren Geschmack.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Als schnelle Banchan (Beilage) zu jedem Reisgerichte. Die Gurke vorher salzen und ausdrücken ist der Schlüssel – sonst wässert der Salat.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">닭죽 · Dakjuk</div>
      <div class="card-title">Koreanischer Hühner-Reisbrei</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 35 Min</span>
      <span class="badge badge-kcal">~340 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Cremiger Reisbrei (Juk) mit zartem Hühnchen, Ingwer und Sesam. Das perfekte Gericht für Regenerationstage nach intensivem Training.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Runkoreis (roh)</span><span class="ing-qty">100 g</span></li>
          <li><span>Hähnchenbrustfilet</span><span class="ing-qty">150 g</span></li>
          <li><span>Frischer Ingwer</span><span class="ing-qty">1 cm</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">2 Zehen</span></li>
          <li><span>Wasser oder Brühe</span><span class="ing-qty">800 ml</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sojasauce + Salz</span><span class="ing-qty">nach Bedarf</span></li>
          <li><span>Frühlingszwiebeln + Sesam</span><span class="ing-qty">zum Garnieren</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Hähnchen mit Ingwer und Knoblauch in Wasser 15 Min. kochen, herausnehmen und zupfen.</li>
          <li>Reis in die Brühe geben (Hähnchen raus), bei mittlerer Hitze 20 Min. köcheln, regelmäßig rühren.</li>
          <li>Wenn Reis cremig und aufgelöst ist, gezupftes Hähnchen wieder einrühren.</li>
          <li>Mit Salz und Sojasauce abschmecken.</li>
          <li>Mit Sesamöl, Sesam und Frühlingszwiebeln servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Recovery-Tipp:</strong> Leicht verdaulich und nährstoffreich – ideal nach langen Trainingseinheiten oder wenn man sich nicht gut fühlt. Reste halten 2 Tage im Kühlschrank.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">제육볶음 · Jeyuk Bokkeum</div>
      <div class="card-title">Würziges Schweinefleischschmoren</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 25 Min</span>
      <span class="badge badge-kcal">~430 kcal</span>
      <span class="badge badge-cost">€ mittel</span>
    </div>
  </div>
  <p class="card-desc">Dünn geschnittenes Schweinefleisch in einer feurigen Gochujang-Marinade mit Zwiebeln und Paprika. Der koreanische Klassiker aus der Imbiss-Küche.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Schweinebauch oder -nacken (dünn)</span><span class="ing-qty">250 g</span></li>
          <li><span>Zwiebel</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Paprika</span><span class="ing-qty">½ Stk</span></li>
          <li><span>Gochujang</span><span class="ing-qty">2 EL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 EL</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">3 Zehen</span></li>
          <li><span>Ingwer (gerieben)</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesamöl + Sesam</span><span class="ing-qty">je 1 TL</span></li>
          <li><span>Zucker</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Fleisch in mundgerechte Stücke schneiden, mit Gochujang, Soja, Knoblauch, Ingwer, Zucker 10 Min. marinieren.</li>
          <li>Öl in Pfanne erhitzen, mariniertes Fleisch bei hoher Hitze anbraten.</li>
          <li>Zwiebeln und Paprika dazugeben, weitere 5 Min. braten.</li>
          <li>Mit Sesamöl ablöschen, Sesam drüber.</li>
          <li>Mit Reis und Salatblättern servieren (Fleisch darin einwickeln).</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Traditionell in Salatblättern (Sangchussam) gegessen: Reisblatt + Fleisch + Knoblauch + Gochujang = perfekter Bissen. Mit magerem Schweinefleisch oder Hähnchen kalorienärmer.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>
```

  </div>
</section>

<!-- =================== JAPANISCH =================== -->

<section id="japanese" class="category-section japanese">
  <div class="section-header">
    <div class="section-kanji">和食</div>
    <div class="section-title-wrap">
      <h2>Japanische Küche</h2>
      <p>Umami, Ausgewogenheit und natürliche Zutaten</p>
    </div>
  </div>
  <div class="recipe-grid">

```
<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">味噌汁 · Miso Shiru</div>
      <div class="card-title">Traditionelle Miso-Suppe</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 10 Min</span>
      <span class="badge badge-kcal">~120 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Das tägliche Basisgericht Japans: seidige Miso-Brühe mit Tofu und Meeresgemüse. Fertig in 10 Minuten, reich an Probiotika.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Helle Miso-Paste</span><span class="ing-qty">2 EL</span></li>
          <li><span>Seidentofu</span><span class="ing-qty">100 g</span></li>
          <li><span>Wakame (getrocknetes Meeresgemüse)</span><span class="ing-qty">2 TL</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Wasser</span><span class="ing-qty">500 ml</span></li>
          <li><span>Dashi-Granulat (optional)</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Wasser (mit Dashi-Granulat) erhitzen, aber nicht kochen lassen.</li>
          <li>Wakame einweichen (5 Min.), Tofu in kleine Würfel schneiden.</li>
          <li>Miso-Paste in einer kleinen Schüssel mit etwas heißer Brühe auflösen.</li>
          <li>Tofu und Wakame in die Brühe geben, dann Miso einrühren.</li>
          <li>Nicht mehr kochen! Mit Frühlingszwiebeln servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Wichtig:</strong> Miso nie kochen – die wertvollen Probiotika werden durch Hitze zerstört. Die Suppe immer am Ende bei niedriger Temperatur einrühren.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">親子丼 · Oyakodon</div>
      <div class="card-title">Hühner-Ei-Reisschüssel</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~520 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">„Eltern-Kind-Schüssel": zartes Hühnchen und Ei in einer süßlich-herzhaften Soße über Reis. Japanisches Comfort Food pur.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Person)</div>
        <ul class="ingredient-list">
          <li><span>Hähnchenbrustfilet</span><span class="ing-qty">120 g</span></li>
          <li><span>Eier</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Zwiebel</span><span class="ing-qty">½ Stk</span></li>
          <li><span>Gekochter Reis</span><span class="ing-qty">200 g</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">2 EL</span></li>
          <li><span>Mirin</span><span class="ing-qty">2 EL</span></li>
          <li><span>Dashi oder Wasser</span><span class="ing-qty">80 ml</span></li>
          <li><span>Zucker</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Hähnchen in mundgerechte Stücke, Zwiebel in dünne Scheiben schneiden.</li>
          <li>Sojasauce, Mirin, Dashi und Zucker in kleiner Pfanne aufkochen.</li>
          <li>Zwiebel hineingeben, 2 Min. köcheln, dann Hähnchen dazugeben (5 Min.).</li>
          <li>Eier verquirlen, über das Hähnchen gießen und bei mittlerer Hitze gar werden lassen (Ei soll noch leicht cremig sein).</li>
          <li>Über Reis gleiten lassen, mit Frühlingszwiebeln garnieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Mirin gibt es im Asialaden oder größeren Supermärkten. Alternativ: 1 TL Zucker + 1 EL Reisessig. Das Ei sollte cremig bleiben – nicht zu lang garen!</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">冷やし中華 · Hiyashi Chuka</div>
      <div class="card-title">Kalte Ramen-Nudeln</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~390 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Erfrischende kalte Nudeln mit knackigem Gemüse und einer würzigen Sesam-Soja-Sauce – perfekt nach dem Sport.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Ramen- oder Weizennudeln</span><span class="ing-qty">160 g</span></li>
          <li><span>Ei</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Gurke</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Karotte</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">3 EL</span></li>
          <li><span>Reisessig</span><span class="ing-qty">2 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 EL</span></li>
          <li><span>Zucker</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesampaste / Tahini</span><span class="ing-qty">1 EL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Nudeln al dente kochen, kalt abschrecken und mit Sesamöl vermischen.</li>
          <li>Eier zu dünnen Omeletts braten, in Streifen schneiden.</li>
          <li>Gurke und Karotte in feine Julienne (Stäbchen) schneiden.</li>
          <li>Sauce aus Soja, Essig, Sesam-Öl, Zucker und Sesampaste rühren.</li>
          <li>Nudeln anrichten, Gemüse und Ei fächerartig darauf, Sauce darüber geben.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Im Sommer besonders erfrischend. Gut im Voraus zubereitet – Nudeln und Belag getrennt aufbewahren und erst kurz vor dem Essen zusammenstellen.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">卵かけご飯 · Tamago Kake Gohan</div>
      <div class="card-title">Ei auf Reis (TKG)</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 5 Min</span>
      <span class="badge badge-kcal">~320 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Japans einfachstes Frühstück: rohes Ei auf heißem Reis mit Sojasauce. Unglaublich gut, cremig und in 5 Minuten fertig.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Person)</div>
        <ul class="ingredient-list">
          <li><span>Frisch gekochter Reis</span><span class="ing-qty">200 g</span></li>
          <li><span>Sehr frisches Ei</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesamöl (optional)</span><span class="ing-qty">½ TL</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Nori-Flocken (optional)</span><span class="ing-qty">1 Prise</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Frisch gekochten, noch heißen Reis in eine Schüssel geben.</li>
          <li>Rohes Ei aufschlagen und über den Reis geben.</li>
          <li>Sojasauce und Sesamöl dazu.</li>
          <li>Gut verrühren bis eine cremige, leicht gebundene Sauce entsteht.</li>
          <li>Mit Frühlingszwiebeln und Nori garnieren. Sofort essen!</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Wichtig:</strong> Nur Bio-Eier und innerhalb von 1–2 Tagen nach Kauf verwenden. Der heiße Reis „gart" das Ei leicht an. Wer unsicher ist: Ei 10 Min. bei 65°C im Wasserbad pasteurisieren.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">豚汁 · Tonjiru</div>
      <div class="card-title">Herzhafte Miso-Suppe mit Schweinefleisch</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 25 Min</span>
      <span class="badge badge-kcal">~310 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Die deftige Geschwister-Suppe der Miso-Suppe: mit Schweinefleisch, Karotten, Daikon und Miso. Eine vollständige Mahlzeit in einer Schüssel.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Schweineschulter (dünn)</span><span class="ing-qty">150 g</span></li>
          <li><span>Karotte</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Daikon (Rettich) oder Kohlrabi</span><span class="ing-qty">100 g</span></li>
          <li><span>Kartoffel</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Miso-Paste (dunkel)</span><span class="ing-qty">2,5 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Wasser</span><span class="ing-qty">600 ml</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">2 Stk</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Sesamöl erhitzen, Fleisch kurz anbraten, dann Gemüse (gewürfelt) dazugeben.</li>
          <li>Wasser dazugeben, aufkochen, Schaum abschöpfen.</li>
          <li>Bei mittlerer Hitze 15 Min. köcheln bis Gemüse weich ist.</li>
          <li>Miso in einem Sieb in die Suppe einrühren (nicht kochen!).</li>
          <li>Mit Frühlingszwiebeln garnieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Mit Hähnchen oder ganz ohne Fleisch (nur Gemüse + Tofu) genauso lecker. Dunkle Miso-Paste gibt mehr Körper und Umami als helle.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">炒り豆腐 · Iri Dofu</div>
      <div class="card-title">Gebratener Tofu mit Ei und Gemüse</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~260 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Krümeliger, gebratener Tofu mit Ei – Japans vegane Antwort auf Rührei. Leicht, sättigend, und in einer Pfanne fertig.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Fester Tofu</span><span class="ing-qty">300 g</span></li>
          <li><span>Eier</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Karotte</span><span class="ing-qty">½ Stk</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">3 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1,5 EL</span></li>
          <li><span>Mirin</span><span class="ing-qty">1 EL</span></li>
          <li><span>Zucker</span><span class="ing-qty">½ TL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Tofu in ein sauberes Tuch wickeln und kräftig ausdrücken.</li>
          <li>Öl erhitzen, Karotte kurz anbraten, Tofu dazukrümeln.</li>
          <li>Bei mittlerer Hitze braten bis das Wasser verdunstet ist (ca. 5 Min.).</li>
          <li>Soja, Mirin und Zucker einrühren, kurz karamellisieren lassen.</li>
          <li>Eier verquirlen, über den Tofu geben und stocken lassen. Mit Sesamöl und Frühlingszwiebeln fertig.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Perfektes Frühstück oder leichtes Abendessen. Auch kalt als Brotbox-Füllung sehr gut. Geriebenen Ingwer mitbraten für extra Würze.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">野菜炒め · Yasai Itame</div>
      <div class="card-title">Japanisches Wok-Gemüse</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~180 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Schnell gebratenes Gemüse in Soja-Mirin-Sauce. Das japanische Stir-Fry – simpel, gesund und als Beilage immer passend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Weißkohl</span><span class="ing-qty">200 g</span></li>
          <li><span>Karotte</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Paprika</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">3 Stk</span></li>
          <li><span>Knoblauch</span><span class="ing-qty">2 Zehen</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">2 EL</span></li>
          <li><span>Mirin</span><span class="ing-qty">1 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Öl zum Braten</span><span class="ing-qty">1 EL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Alle Gemüse in mundgerechte Stücke schneiden.</li>
          <li>Öl in Wok oder großer Pfanne auf hohe Hitze bringen.</li>
          <li>Zuerst Karotte, dann restliches Gemüse in 2-Min.-Abständen dazugeben.</li>
          <li>Knoblauch einrühren, 30 Sek. braten.</li>
          <li>Soja und Mirin dazu, kurz schwenken, mit Sesamöl fertig.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Hochhitze ist das Geheimnis – das Gemüse soll brutzeln, nicht dünsten. Beliebiges Saison-Gemüse verwenden. Mit Hähnchen oder Tofu zu einer vollständigen Mahlzeit ergänzen.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">そばサラダ · Soba Sarada</div>
      <div class="card-title">Kalter Buchweizen-Nudel-Salat</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~350 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Buchweizennudeln mit Gurke, Avocado und einem Soja-Ingwer-Dressing. Glutenärmer als Weizennudeln, nussig und sehr sättigend.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Soba-Nudeln (Buchweizen)</span><span class="ing-qty">160 g</span></li>
          <li><span>Gurke</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Avocado</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Frühlingszwiebeln</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">3 EL</span></li>
          <li><span>Reisessig</span><span class="ing-qty">1,5 EL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 EL</span></li>
          <li><span>Ingwer (gerieben)</span><span class="ing-qty">1 TL</span></li>
          <li><span>Sesam</span><span class="ing-qty">1 EL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Soba nach Packung kochen (meist 4–5 Min.), kalt abschrecken, mit etwas Sesamöl vermischen.</li>
          <li>Gurke in Julienne schneiden, Avocado würfeln.</li>
          <li>Dressing aus Soja, Essig, Sesamöl und Ingwer verrühren.</li>
          <li>Nudeln, Gurke und Dressing vermengen.</li>
          <li>Avocado vorsichtig unterheben, mit Frühlingszwiebeln und Sesam servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Soba-Tipp:</strong> Buchweizennudeln nach dem Kochen besonders gründlich unter fließendem Wasser abspülen – das entfernt die Stärke und macht sie bissfester. Dressing erst kurz vor dem Essen dazugeben.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">だし巻き卵 · Dashimaki Tamago</div>
      <div class="card-title">Japanisches Rollenomelett</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~200 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Das japanische Tamagoyaki – süßlich-herzhaftes Rollenomelett aus mehreren Schichten. Sieht beeindruckend aus und ist leichter als gedacht.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Person)</div>
        <ul class="ingredient-list">
          <li><span>Eier</span><span class="ing-qty">3 Stk</span></li>
          <li><span>Dashi oder Wasser</span><span class="ing-qty">2 EL</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 TL</span></li>
          <li><span>Mirin oder Zucker</span><span class="ing-qty">1 TL</span></li>
          <li><span>Öl zum Braten</span><span class="ing-qty">wenig</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Eier mit Dashi, Soja und Mirin gut verquirlen (nicht schaumig).</li>
          <li>Pfanne mit Öl bei mittlerer Hitze erhitzen, ⅓ der Eiermasse eingießen.</li>
          <li>Sobald die Ränder stocken, das Omelett von einer Seite zur anderen aufrollen.</li>
          <li>Die Rolle zur Seite schieben, Pfanne neu ölen, nächste Schicht eingießen – unter die Rolle laufen lassen und wieder aufrollen.</li>
          <li>Wiederholen, in Scheiben schneiden und servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Der erste Versuch ist fast immer ein bisschen chaotisch – das ist normal! Eine rechteckige Pfanne (Tamagoyaki-Pfanne) macht es leichter. Kalt in der Brotbox genauso lecker.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">肉じゃが · Nikujaga</div>
      <div class="card-title">Japanischer Fleisch-Kartoffel-Eintopf</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 35 Min</span>
      <span class="badge badge-kcal">~400 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Japans Hausmannskost: zartes Fleisch mit Kartoffeln in einer süßlich-herzhaften Soja-Dashi-Sauce. Wie eine Umarmung in einer Schüssel.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Rinder- oder Schweinefleisch (dünn)</span><span class="ing-qty">150 g</span></li>
          <li><span>Kartoffeln</span><span class="ing-qty">3 Stk</span></li>
          <li><span>Zwiebel</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Karotte</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">3 EL</span></li>
          <li><span>Mirin</span><span class="ing-qty">2 EL</span></li>
          <li><span>Zucker</span><span class="ing-qty">1 EL</span></li>
          <li><span>Dashi oder Wasser</span><span class="ing-qty">200 ml</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Kartoffeln und Karotten würfeln, Zwiebeln in Streifen schneiden.</li>
          <li>Öl erhitzen, Fleisch anbraten, Zwiebeln dazu bis weich.</li>
          <li>Kartoffeln und Karotten dazugeben, kurz mitbraten.</li>
          <li>Dashi, Soja, Mirin und Zucker dazugeben. Aufkochen, Schaum abschöpfen.</li>
          <li>Bei mittlerer Hitze 20 Min. köcheln bis Kartoffeln weich sind.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Meal-Prep:</strong> Schmeckt am nächsten Tag noch besser! Für 4 Portionen kochen und im Kühlschrank aufbewahren. Auch mit Hähnchen oder nur Gemüse (z.B. Pilze statt Fleisch) köstlich.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">冷奴 · Hiyayakko</div>
      <div class="card-title">Kalter Tofu mit Toppings</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 5 Min</span>
      <span class="badge badge-kcal">~120 kcal</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Seidentofu direkt aus dem Kühlschrank mit Sojasauce, Ingwer und Frühlingszwiebeln. Das japanische Null-Kochen-Gericht – rein, frisch, perfekt.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Person)</div>
        <ul class="ingredient-list">
          <li><span>Seidentofu (kalt)</span><span class="ing-qty">150 g</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1 TL</span></li>
          <li><span>Frischer Ingwer (gerieben)</span><span class="ing-qty">½ TL</span></li>
          <li><span>Frühlingszwiebeln (fein)</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Katsuobushi (Bonito-Flocken, optional)</span><span class="ing-qty">1 Prise</span></li>
          <li><span>Sesamöl (optional)</span><span class="ing-qty">½ TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Tofu vorsichtig aus der Packung nehmen und auf einen Teller gleiten lassen.</li>
          <li>Frühlingszwiebeln fein schneiden, Ingwer reiben.</li>
          <li>Toppings auf den Tofu geben.</li>
          <li>Mit Sojasauce beträufeln.</li>
          <li>Sofort servieren – einfach so essen oder mit Reis.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Im Sommer das erfrischendste Gericht überhaupt. Weitere leckere Toppings: geraspelter Daikon, Natto, eingelegte Pflaume (Umeboshi), oder Wasabi.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">きんぴらごぼう · Kinpira Gobo</div>
      <div class="card-title">Gebratene Burdock-Karotten</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~130 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Knackig gebratene Karotten (und Gobo wenn erhältlich) in einer würzigen Soja-Mirin-Glasur. Klassische japanische Beilage, die zu allem passt.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (2 Personen)</div>
        <ul class="ingredient-list">
          <li><span>Karotten</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Gobo (Klettenwurzel, optional)</span><span class="ing-qty">1 Stk</span></li>
          <li><span>Sojasauce</span><span class="ing-qty">1,5 EL</span></li>
          <li><span>Mirin</span><span class="ing-qty">1,5 EL</span></li>
          <li><span>Zucker</span><span class="ing-qty">½ TL</span></li>
          <li><span>Sesamöl</span><span class="ing-qty">1 TL</span></li>
          <li><span>Chiliflocken (optional)</span><span class="ing-qty">½ TL</span></li>
          <li><span>Sesam</span><span class="ing-qty">1 TL</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Karotten in feine Julienne (Stäbchen) schneiden. Gobo schälen, ebenso schneiden und 5 Min. wässern.</li>
          <li>Sesamöl erhitzen, Karotten (und Gobo) bei mittlerer Hitze 3–4 Min. braten.</li>
          <li>Soja, Mirin und Zucker einrühren.</li>
          <li>Weiterrühren bis die Flüssigkeit eingekocht und die Karotten glasiert sind.</li>
          <li>Mit Sesam und Chili servieren.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Tipp:</strong> Auch ohne Gobo (Klettenwurzel) hervorragend – einfach mehr Karotten nehmen. Hält 4–5 Tage im Kühlschrank, super für Bento-Box oder als Banchan-Beilage.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>
```

  </div>
</section>

<!-- =================== BROTBOX =================== -->

<section id="brotbox" class="category-section brotbox">
  <div class="section-header">
    <div class="section-kanji">弁当</div>
    <div class="section-title-wrap">
      <h2>Brotbox & Meal-Prep</h2>
      <p>Zum Mitnehmen – für Sport, Arbeit & Schule</p>
    </div>
  </div>
  <div class="recipe-grid">

```
<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">おにぎり · Onigiri</div>
      <div class="card-title">Japanische Reisbälle</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 15 Min</span>
      <span class="badge badge-kcal">~220 kcal / Stk</span>
      <span class="badge badge-cost">€ sehr günstig</span>
    </div>
  </div>
  <p class="card-desc">Der japanische Snack-Klassiker: gepresste Reisbälle mit Füllung. Perfekt für die Tasche, hält bis zu 8 Stunden frisch.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (4 Stück)</div>
        <ul class="ingredient-list">
          <li><span>Japanischer Rundkornreis (gegart)</span><span class="ing-qty">400 g</span></li>
          <li><span>Salz</span><span class="ing-qty">1 TL</span></li>
          <li><span>Nori-Blätter</span><span class="ing-qty">2 Stk</span></li>
          <li><span>Thunfisch (Dose) + Mayonnaise</span><span class="ing-qty">je 1 EL</span></li>
          <li><span>ODER: Edamame + Sesam</span><span class="ing-qty">nach Belieben</span></li>
          <li><span>ODER: Umeboshi (Salz-Pflaume)</span><span class="ing-qty">2 Stk</span></li>
        </ul>
      </div>
      <div>
        <div class="details-label">Zubereitung</div>
        <ol class="steps-list">
          <li>Hände befeuchten und leicht salzen, eine Handvoll Reis nehmen.</li>
          <li>Eine Mulde formen, Füllung einsetzen und mit Reis verschließen.</li>
          <li>Zu einem Dreieck oder einer Kugel pressen – fest aber nicht zu hart.</li>
          <li>Nori-Streifen um den unteren Teil wickeln.</li>
          <li>In Frischhaltefolie oder Brotbox-Papier einwickeln.</li>
        </ol>
      </div>
    </div>
    <div class="tip-box"><strong>Meal-Prep:</strong> Morgens in 15 Min. zubereiten. Hält sich bei Zimmertemperatur 6–8 Stunden gut. Für maximale Frische: Nori erst kurz vor dem Essen wickeln.</div>
  </div>
  <button class="toggle-btn" onclick="toggleCard(this)">Rezept anzeigen <span class="toggle-icon">▼</span></button>
</div>

<div class="recipe-card">
  <div class="card-header">
    <div class="card-title-group">
      <div class="card-kana">간단 도시락 · Dosirak</div>
      <div class="card-title">Koreanische Bento-Box</div>
    </div>
    <div class="card-badges">
      <span class="badge badge-time">⏱ 20 Min</span>
      <span class="badge badge-kcal">~490 kcal</span>
      <span class="badge badge-cost">€ günstig</span>
    </div>
  </div>
  <p class="card-desc">Reis, einfaches Omelett, Spinat-Namul und Karotten-Sticks – die koreanische Variante der Bento-Box. Ausgewogen und farbenfroh.</p>
  <div class="card-details">
    <div class="details-col-wrap">
      <div>
        <div class="details-label">Zutaten (1 Box)</div>
        <ul class="ingredient-list
