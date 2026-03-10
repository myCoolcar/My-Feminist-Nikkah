<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Know Your Rights in an Islamic Marriage | Nikah Contract Guide</title>
  <meta name="description" content="Learn about your rights in an Islamic marriage contract (Nikah). Understand the protections Islam allows you to include." />

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Amiri:ital,wght@0,400;0,700;1,400&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet" />

  <style>
    /* ===== DESIGN TOKENS ===== */
    :root {
      --teal-deep:    #0d5f6b;
      --teal-mid:     #1a8a9a;
      --teal-light:   #d4f0f5;
      --gold:         #b8882a;
      --gold-light:   #f5e6c0;
      --gold-pale:    #fdf8ee;
      --cream:        #faf7f2;
      --white:        #ffffff;
      --text-dark:    #1c2b30;
      --text-mid:     #3d5a60;
      --text-soft:    #5e7a80;
      --border:       #d0e8ec;
      --shadow-sm:    0 2px 8px rgba(13,95,107,0.10);
      --shadow-md:    0 6px 24px rgba(13,95,107,0.14);
      --radius-sm:    10px;
      --radius-md:    18px;
      --radius-lg:    28px;
      --font-body:    'Nunito', sans-serif;
      --font-display: 'Amiri', serif;
    }

    /* ===== RESET & BASE ===== */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; font-size: 18px; }
    body {
      font-family: var(--font-body);
      background: var(--cream);
      color: var(--text-dark);
      line-height: 1.7;
    }
    img { max-width: 100%; display: block; }
    a { color: var(--teal-deep); }
    a:focus-visible, button:focus-visible {
      outline: 3px solid var(--gold);
      outline-offset: 3px;
      border-radius: 4px;
    }

    /* ===== GEOMETRIC PATTERN (SVG background) ===== */
    .pattern-bg {
      background-color: var(--teal-deep);
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='60' height='60'%3E%3Cg fill='none' stroke='%23ffffff' stroke-width='0.6' opacity='0.12'%3E%3Cpolygon points='30,4 56,18 56,42 30,56 4,42 4,18'/%3E%3Cpolygon points='30,14 46,23 46,37 30,46 14,37 14,23'/%3E%3Cline x1='30' y1='4' x2='30' y2='14'/%3E%3Cline x1='56' y1='18' x2='46' y2='23'/%3E%3Cline x1='56' y1='42' x2='46' y2='37'/%3E%3Cline x1='30' y1='56' x2='30' y2='46'/%3E%3Cline x1='4' y1='42' x2='14' y2='37'/%3E%3Cline x1='4' y1='18' x2='14' y2='23'/%3E%3C/g%3E%3C/svg%3E");
    }

    /* ===== SKIP LINK ===== */
    .skip-link {
      position: absolute;
      top: -999px;
      left: 0;
      background: var(--gold);
      color: var(--text-dark);
      padding: 12px 20px;
      font-weight: 700;
      z-index: 10000;
      border-radius: 0 0 var(--radius-sm) 0;
      text-decoration: none;
    }
    .skip-link:focus { top: 0; }

    /* ===== TOP UTILITY BAR ===== */
    .utility-bar {
      background: var(--text-dark);
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 10px;
    }
    .utility-bar__left {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    /* Language Selector */
    .lang-select-wrapper {
      position: relative;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    .lang-select-wrapper label {
      color: #ccc;
      font-size: 0.78rem;
      font-weight: 600;
      white-space: nowrap;
    }
    .lang-select {
      background: #2c3e42;
      color: #fff;
      border: 1px solid #4a6468;
      border-radius: 6px;
      padding: 5px 10px;
      font-size: 0.82rem;
      font-family: var(--font-body);
      cursor: pointer;
    }

    /* TTS Button */
    .tts-btn {
      display: flex;
      align-items: center;
      gap: 7px;
      background: #2c3e42;
      color: #ddd;
      border: 1px solid #4a6468;
      border-radius: 6px;
      padding: 6px 12px;
      font-size: 0.82rem;
      font-family: var(--font-body);
      cursor: pointer;
      transition: background 0.2s;
    }
    .tts-btn:hover { background: var(--teal-deep); color: #fff; }
    .tts-btn svg { flex-shrink: 0; }

    /* Quick Exit */
    .quick-exit-btn {
      background: #c0392b;
      color: #fff;
      border: none;
      border-radius: 8px;
      padding: 8px 18px;
      font-size: 0.85rem;
      font-weight: 800;
      font-family: var(--font-body);
      cursor: pointer;
      letter-spacing: 0.03em;
      transition: background 0.2s, transform 0.1s;
      display: flex;
      align-items: center;
      gap: 7px;
    }
    .quick-exit-btn:hover { background: #a93226; transform: scale(1.03); }

    /* ===== NAV ===== */
    .site-nav {
      background: var(--white);
      border-bottom: 3px solid var(--teal-light);
      padding: 0 24px;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: var(--shadow-sm);
    }
    .nav-inner {
      max-width: 1100px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 16px;
      min-height: 64px;
      flex-wrap: wrap;
      padding: 8px 0;
    }
    .nav-logo {
      font-family: var(--font-display);
      font-size: 1.35rem;
      font-weight: 700;
      color: var(--teal-deep);
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .nav-logo span.logo-icon {
      width: 36px;
      height: 36px;
      background: var(--teal-deep);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 1.1rem;
    }

    .nav-links {
      display: flex;
      list-style: none;
      gap: 4px;
      flex-wrap: wrap;
    }
    .nav-links a {
      text-decoration: none;
      color: var(--text-mid);
      font-size: 0.88rem;
      font-weight: 700;
      padding: 6px 12px;
      border-radius: var(--radius-sm);
      transition: background 0.2s, color 0.2s;
    }
    .nav-links a:hover {
      background: var(--teal-light);
      color: var(--teal-deep);
    }

    /* ===== HERO ===== */
    .hero {
      padding: 70px 24px 80px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(160deg, var(--teal-deep) 0%, #0a4a55 100%);
      z-index: 0;
    }
    /* Decorative arcs */
    .hero::after {
      content: '';
      position: absolute;
      bottom: -60px;
      left: 50%;
      transform: translateX(-50%);
      width: 120%;
      height: 120px;
      background: var(--cream);
      border-radius: 50% 50% 0 0 / 100% 100% 0 0;
      z-index: 1;
    }
    .hero-content {
      position: relative;
      z-index: 2;
      max-width: 800px;
      margin: 0 auto;
    }
    .hero-badge {
      display: inline-block;
      background: rgba(255,255,255,0.15);
      color: var(--gold-light);
      border: 1px solid rgba(255,255,255,0.25);
      border-radius: 40px;
      padding: 6px 20px;
      font-size: 0.82rem;
      font-weight: 700;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      margin-bottom: 22px;
    }
    .hero h1 {
      font-family: var(--font-display);
      font-size: clamp(2rem, 5vw, 3.4rem);
      color: var(--white);
      line-height: 1.2;
      margin-bottom: 16px;
    }
    .hero h1 em {
      font-style: normal;
      color: var(--gold-light);
    }
    .hero-subtitle {
      font-size: clamp(1.05rem, 2.5vw, 1.3rem);
      color: rgba(255,255,255,0.88);
      margin-bottom: 28px;
      font-weight: 600;
    }
    .hero-intro {
      font-size: 1.02rem;
      color: rgba(255,255,255,0.80);
      max-width: 640px;
      margin: 0 auto 32px;
    }
    .hero-verse {
      display: inline-block;
      background: rgba(255,255,255,0.10);
      border-left: 4px solid var(--gold-light);
      border-radius: 0 var(--radius-sm) var(--radius-sm) 0;
      padding: 16px 24px;
      text-align: left;
      max-width: 540px;
      width: 100%;
      margin: 0 auto;
    }
    .hero-verse blockquote {
      font-family: var(--font-display);
      font-size: 1.18rem;
      color: var(--gold-light);
      font-style: italic;
      margin-bottom: 6px;
    }
    .hero-verse cite {
      font-size: 0.82rem;
      color: rgba(255,255,255,0.65);
      font-style: normal;
      font-weight: 700;
    }

    /* ===== MAIN WRAPPER ===== */
    main { position: relative; z-index: 2; }
    .section {
      padding: 60px 24px;
      max-width: 1100px;
      margin: 0 auto;
    }
    .section--alt {
      background: var(--white);
    }
    .section--alt-inner {
      max-width: 100%;
      padding: 0;
    }
    .full-width-section {
      padding: 60px 24px;
    }

    /* ===== SECTION TITLES ===== */
    .section-title {
      font-family: var(--font-display);
      font-size: clamp(1.6rem, 3.5vw, 2.4rem);
      color: var(--teal-deep);
      margin-bottom: 12px;
      line-height: 1.25;
    }
    .section-subtitle {
      font-size: 1.02rem;
      color: var(--text-soft);
      margin-bottom: 36px;
      max-width: 680px;
    }
    .title-divider {
      width: 60px;
      height: 4px;
      background: linear-gradient(90deg, var(--gold), var(--teal-mid));
      border-radius: 4px;
      margin-bottom: 16px;
    }

    /* ===== INFO CARDS (Why Nikah Matters) ===== */
    .info-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));
      gap: 22px;
      margin-top: 10px;
    }
    .info-card {
      background: var(--white);
      border-radius: var(--radius-md);
      padding: 28px 26px;
      border: 1.5px solid var(--border);
      box-shadow: var(--shadow-sm);
      transition: box-shadow 0.25s, transform 0.25s;
    }
    .info-card:hover {
      box-shadow: var(--shadow-md);
      transform: translateY(-3px);
    }
    .info-card__icon {
      width: 52px;
      height: 52px;
      border-radius: 14px;
      background: var(--teal-light);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.6rem;
      margin-bottom: 16px;
      flex-shrink: 0;
    }
    .info-card h3 {
      font-size: 1.08rem;
      font-weight: 800;
      color: var(--teal-deep);
      margin-bottom: 9px;
    }
    .info-card p {
      font-size: 0.95rem;
      color: var(--text-mid);
      line-height: 1.65;
    }

    /* ===== HADITH HIGHLIGHT ===== */
    .hadith-highlight {
      background: linear-gradient(135deg, var(--teal-deep), #0a4a55);
      border-radius: var(--radius-md);
      padding: 32px 36px;
      margin-top: 36px;
      display: flex;
      gap: 20px;
      align-items: flex-start;
    }
    .hadith-highlight__icon {
      font-size: 2rem;
      flex-shrink: 0;
      margin-top: 4px;
    }
    .hadith-highlight blockquote {
      font-family: var(--font-display);
      font-size: 1.22rem;
      font-style: italic;
      color: var(--gold-light);
      margin-bottom: 8px;
      line-height: 1.55;
    }
    .hadith-highlight cite {
      font-size: 0.82rem;
      color: rgba(255,255,255,0.65);
      font-style: normal;
      font-weight: 700;
    }
    .hadith-highlight p {
      font-size: 0.93rem;
      color: rgba(255,255,255,0.80);
      margin-top: 10px;
    }

    /* ===== ACCORDION CARDS (Rights) ===== */
    .rights-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      gap: 18px;
    }
    .accordion-card {
      background: var(--white);
      border-radius: var(--radius-md);
      border: 1.5px solid var(--border);
      box-shadow: var(--shadow-sm);
      overflow: hidden;
      transition: box-shadow 0.2s;
    }
    .accordion-card:hover { box-shadow: var(--shadow-md); }
    .accordion-card--open {
      border-color: var(--teal-mid);
    }
    .accordion-trigger {
      width: 100%;
      background: none;
      border: none;
      cursor: pointer;
      padding: 20px 22px;
      display: flex;
      align-items: center;
      gap: 14px;
      text-align: left;
      font-family: var(--font-body);
    }
    .accordion-trigger:hover .trigger-title { color: var(--teal-deep); }
    .trigger-icon {
      width: 46px;
      height: 46px;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.45rem;
      flex-shrink: 0;
      background: var(--teal-light);
    }
    .trigger-text { flex: 1; min-width: 0; }
    .trigger-title {
      font-size: 1rem;
      font-weight: 800;
      color: var(--text-dark);
      display: block;
      line-height: 1.3;
      transition: color 0.2s;
    }
    .trigger-tag {
      display: inline-block;
      font-size: 0.72rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      color: var(--teal-mid);
      margin-top: 3px;
    }
    .trigger-chevron {
      width: 28px;
      height: 28px;
      border-radius: 50%;
      background: var(--teal-light);
      display: flex;
      align-items: center;
      justify-content: center;
      transition: transform 0.3s, background 0.2s;
      flex-shrink: 0;
    }
    .accordion-card--open .trigger-chevron {
      transform: rotate(180deg);
      background: var(--teal-deep);
    }
    .accordion-card--open .trigger-chevron svg path { stroke: white; }

    .accordion-body {
      display: none;
      padding: 0 22px 22px;
      animation: fadeSlide 0.25s ease;
    }
    .accordion-body--open { display: block; }
    @keyframes fadeSlide {
      from { opacity: 0; transform: translateY(-8px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .accordion-body__divider {
      height: 1px;
      background: var(--border);
      margin-bottom: 16px;
    }
    .accordion-body h4 {
      font-size: 0.82rem;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 0.07em;
      color: var(--text-soft);
      margin: 14px 0 7px;
    }
    .accordion-body p {
      font-size: 0.95rem;
      color: var(--text-mid);
      line-height: 1.65;
    }
    .accordion-body ul {
      padding-left: 20px;
      margin-top: 6px;
    }
    .accordion-body ul li {
      font-size: 0.93rem;
      color: var(--text-mid);
      margin-bottom: 5px;
      line-height: 1.6;
    }
    .reference-pill {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: var(--gold-light);
      color: var(--gold);
      border-radius: 20px;
      padding: 5px 12px;
      font-size: 0.78rem;
      font-weight: 700;
      margin-top: 12px;
    }

    /* ===== EXAMPLE WORDING SECTION ===== */
    .example-section {
      background: var(--gold-pale);
      border-radius: var(--radius-lg);
      padding: 40px 36px;
      border: 2px dashed var(--gold);
    }
    .example-section h3 {
      font-family: var(--font-display);
      font-size: 1.4rem;
      color: var(--teal-deep);
      margin-bottom: 8px;
    }
    .example-section > p {
      font-size: 0.95rem;
      color: var(--text-soft);
      margin-bottom: 24px;
    }
    .clause-example {
      background: var(--white);
      border-radius: var(--radius-md);
      border-left: 5px solid var(--teal-mid);
      padding: 20px 22px;
      margin-bottom: 18px;
      box-shadow: var(--shadow-sm);
    }
    .clause-example__title {
      font-size: 0.82rem;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 0.07em;
      color: var(--teal-mid);
      margin-bottom: 8px;
    }
    .clause-example__text {
      font-family: var(--font-display);
      font-size: 1.05rem;
      color: var(--text-dark);
      font-style: italic;
      line-height: 1.7;
    }

    /* ===== REMINDER BANNER ===== */
    .reminder-banner {
      background: linear-gradient(135deg, #fff8e8, #fef3d0);
      border: 2px solid var(--gold);
      border-radius: var(--radius-md);
      padding: 30px 32px;
      display: flex;
      gap: 18px;
      align-items: flex-start;
    }
    .reminder-banner__icon {
      font-size: 2.2rem;
      flex-shrink: 0;
    }
    .reminder-banner h3 {
      font-size: 1.12rem;
      font-weight: 800;
      color: var(--gold);
      margin-bottom: 10px;
    }
    .reminder-banner ul {
      padding-left: 18px;
    }
    .reminder-banner ul li {
      font-size: 0.96rem;
      color: var(--text-mid);
      margin-bottom: 7px;
      line-height: 1.6;
    }

    /* ===== RESOURCES SECTION ===== */
    .resources-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 22px;
      margin-top: 12px;
    }
    .resource-card {
      background: var(--white);
      border-radius: var(--radius-md);
      padding: 26px 24px;
      border: 1.5px solid var(--border);
      box-shadow: var(--shadow-sm);
    }
    .resource-card__header {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 16px;
    }
    .resource-card__icon-wrap {
      width: 46px;
      height: 46px;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.5rem;
      background: var(--teal-light);
      flex-shrink: 0;
    }
    .resource-card h3 {
      font-size: 1rem;
      font-weight: 800;
      color: var(--teal-deep);
    }
    .resource-card p {
      font-size: 0.92rem;
      color: var(--text-soft);
      margin-bottom: 16px;
      line-height: 1.6;
    }
    .resource-placeholder {
      background: var(--cream);
      border: 1.5px dashed var(--border);
      border-radius: var(--radius-sm);
      padding: 10px 14px;
      font-size: 0.83rem;
      color: var(--text-soft);
      font-style: italic;
    }
    .resource-link-list {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 8px;
    }
    .resource-link-list li a {
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: 0.9rem;
      font-weight: 700;
      color: var(--teal-deep);
      text-decoration: none;
      padding: 8px 12px;
      background: var(--cream);
      border-radius: var(--radius-sm);
      border: 1.5px solid var(--border);
      transition: background 0.2s, border-color 0.2s;
    }
    .resource-link-list li a:hover {
      background: var(--teal-light);
      border-color: var(--teal-mid);
    }

    /* ===== FOOTER ===== */
    footer {
      background: var(--text-dark);
      color: rgba(255,255,255,0.65);
      text-align: center;
      padding: 36px 24px;
      font-size: 0.85rem;
      line-height: 1.8;
    }
    footer a { color: var(--teal-light); }
    footer strong { color: rgba(255,255,255,0.85); }
    .footer-logo {
      font-family: var(--font-display);
      font-size: 1.3rem;
      color: var(--gold-light);
      margin-bottom: 10px;
    }

    /* ===== PRINT BUTTON ===== */
    .print-btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--teal-deep);
      color: white;
      border: none;
      border-radius: var(--radius-sm);
      padding: 12px 22px;
      font-family: var(--font-body);
      font-size: 0.92rem;
      font-weight: 700;
      cursor: pointer;
      margin-top: 20px;
      text-decoration: none;
      transition: background 0.2s;
    }
    .print-btn:hover { background: var(--teal-mid); color: white; }

    /* ===== READING EASE NOTICE ===== */
    .reading-notice {
      background: var(--teal-light);
      border-radius: var(--radius-sm);
      padding: 12px 18px;
      font-size: 0.85rem;
      color: var(--teal-deep);
      font-weight: 600;
      margin-bottom: 30px;
      display: flex;
      gap: 10px;
      align-items: center;
    }

    /* ===== RESPONSIVE ===== */
    @media (max-width: 700px) {
      html { font-size: 17px; }
      .hero { padding: 50px 18px 70px; }
      .section { padding: 44px 18px; }
      .full-width-section { padding: 44px 18px; }
      .hadith-highlight { flex-direction: column; padding: 24px 22px; }
      .example-section { padding: 28px 20px; }
      .reminder-banner { flex-direction: column; padding: 22px 20px; }
      .nav-links { display: none; }
      .rights-grid { grid-template-columns: 1fr; }
    }
    @media print {
      .utility-bar, .site-nav, .quick-exit-btn, .print-btn { display: none !important; }
      .accordion-body { display: block !important; }
    }
  </style>
</head>
<body>

  <!-- ===== SKIP LINK ===== -->
  <a href="#main-content" class="skip-link">Skip to main content</a>

  <!-- ===== UTILITY BAR ===== -->
  <div class="utility-bar" role="banner" aria-label="Accessibility tools">
    <div class="utility-bar__left">

      <!-- Language Selector (placeholder) -->
      <div class="lang-select-wrapper">
        <label for="lang-select">🌐 Language:</label>
        <select id="lang-select" class="lang-select" aria-label="Select language">
          <option value="en">English</option>
          <option value="ar">العربية (Arabic)</option>
          <option value="ur">اردو (Urdu)</option>
          <option value="bn">বাংলা (Bengali)</option>
          <option value="tr">Türkçe (Turkish)</option>
          <option value="so">Soomaali (Somali)</option>
          <option value="fr">Français (French)</option>
          <option value="id">Bahasa Indonesia</option>
        </select>
      </div>

      <!-- Text-to-Speech (placeholder) -->
      <button class="tts-btn" id="tts-btn" aria-label="Read this page aloud using text-to-speech" onclick="handleTTS()">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" aria-hidden="true">
          <path d="M11 5L6 9H2v6h4l5 4V5z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M15.54 8.46a5 5 0 0 1 0 7.07M19.07 4.93a10 10 0 0 1 0 14.14" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        Read Aloud
      </button>
    </div>

    <!-- Quick Exit -->
    <button class="quick-exit-btn" onclick="quickExit()" aria-label="Quick exit — closes this page immediately and goes to a safe website">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" aria-hidden="true">
        <path d="M18 6L6 18M6 6l12 12" stroke="white" stroke-width="2.5" stroke-linecap="round"/>
      </svg>
      Quick Exit ✕
    </button>
  </div>

  <!-- ===== MAIN NAVIGATION ===== -->
  <nav class="site-nav" aria-label="Main navigation">
    <div class="nav-inner">
      <a href="#" class="nav-logo" aria-label="Home — Know Your Nikah Rights">
        <span class="logo-icon" aria-hidden="true">☽</span>
        Know Your Rights
      </a>
      <ul class="nav-links" role="list">
        <li><a href="#why-nikah">Why It Matters</a></li>
        <li><a href="#your-rights">Your Rights</a></li>
        <li><a href="#example-wording">Example Wording</a></li>
        <li><a href="#resources">Resources</a></li>
      </ul>
    </div>
  </nav>

  <!-- ===== HERO ===== -->
  <header class="hero pattern-bg" role="banner" aria-labelledby="hero-title">
    <div class="hero-content">
      <div class="hero-badge" aria-hidden="true">Islamic Marriage Rights</div>
      <h1 id="hero-title">Know Your Rights in an<br><em>Islamic Marriage</em></h1>
      <p class="hero-subtitle">A Nikah contract can protect you.<br>Islam allows conditions in marriage.</p>
      <p class="hero-intro">
        Islam is built on justice, kindness, and keeping promises. The Nikah contract is not just a ceremony — it is a legal agreement. You have the right to add conditions to this agreement. These conditions can protect your life, your choices, and your dignity.
      </p>
      <div class="hero-verse" role="complementary" aria-label="Qur'an verse">
        <blockquote>"O you who believe, fulfil your contracts."</blockquote>
        <cite>— Qur'an 5:1 (Al-Ma'idah)</cite>
      </div>
    </div>
  </header>

  <!-- ===== MAIN CONTENT ===== -->
  <main id="main-content">

    <!-- ===== SECTION 1: WHY THE NIKAH CONTRACT MATTERS ===== -->
    <section id="why-nikah" class="section" aria-labelledby="why-title">
      <div class="title-divider" aria-hidden="true"></div>
      <h2 class="section-title" id="why-title">Why the Nikah Contract Matters</h2>
      <p class="section-subtitle">Understanding what a Nikah contract is — and why your rights in it are important.</p>

      <div class="reading-notice" role="note" aria-label="Information">
        📖 This page is written in simple English. Take your time. You can also press "Read Aloud" at the top of the page.
      </div>

      <div class="info-grid" role="list">
        <div class="info-card" role="listitem">
          <div class="info-card__icon" aria-hidden="true">📜</div>
          <h3>What is a Nikah contract?</h3>
          <p>
            A Nikah is the Islamic marriage contract. Both the husband and wife agree to its terms. Like any contract, it can include conditions — agreed rules that both people must follow.
          </p>
        </div>

        <div class="info-card" role="listitem">
          <div class="info-card__icon" aria-hidden="true">⚖️</div>
          <h3>Why can women add conditions?</h3>
          <p>
            Islamic scholars throughout history have agreed that a woman can include conditions in her Nikah. If the husband agrees to these conditions and then breaks them, she may have the right to end the marriage.
          </p>
        </div>

        <div class="info-card" role="listitem">
          <div class="info-card__icon" aria-hidden="true">💡</div>
          <h3>Why don't many women know this?</h3>
          <p>
            Many women are not told about these rights before or during their marriage. Cultural traditions sometimes replace Islamic law. This page is here to change that — knowledge is protection.
          </p>
        </div>
      </div>

      <!-- Hadith Highlight -->
      <div class="hadith-highlight" role="complementary" aria-label="Hadith reference">
        <div class="hadith-highlight__icon" aria-hidden="true">📿</div>
        <div>
          <blockquote>"The believers are bound by their conditions, except for a condition that makes the lawful unlawful, or the unlawful lawful."</blockquote>
          <cite>— Prophet Muhammad ﷺ (Sunan Abi Dawud, 3594; authenticated by scholars)</cite>
          <p>This hadith means that conditions agreed in the Nikah must be kept — as long as they are fair and allowed in Islam.</p>
        </div>
      </div>
    </section>

    <!-- ===== SECTION 2: YOUR RIGHTS ===== -->
    <div class="section--alt">
      <section id="your-rights" class="section section--alt-inner full-width-section" aria-labelledby="rights-title">
        <div class="title-divider" aria-hidden="true"></div>
        <h2 class="section-title" id="rights-title">Key Protections You Can Include</h2>
        <p class="section-subtitle">
          Below are common conditions women include in their Nikah contract. Click on each one to learn more. You can show these to an imam, Islamic scholar, or lawyer.
        </p>

        <div class="rights-grid" role="list">

          <!-- 1. Monogamy Clause -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-1">
            <button
              class="accordion-trigger"
              id="acc-btn-1"
              aria-expanded="false"
              aria-controls="acc-body-1"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">💍</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-1">Monogamy Clause</span>
                <span class="trigger-tag">No second wife without consent</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-1" role="region" aria-labelledby="acc-btn-1">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>You can ask your husband to agree that he will not marry another woman while you are married to him — or that he must get your written agreement before doing so.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Protects your emotional and financial security.</li>
                <li>If he breaks this condition, you may have grounds to seek divorce (khul' or faskh).</li>
                <li>Islamic law allows polygamy under strict conditions, but does not require it — this clause is valid.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Qur'an 4:3 — "if you fear you cannot be just, then marry only one."
              </div>
            </div>
          </article>

          <!-- 2. Delegated Divorce (Talaq al-Tafwid) -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-2">
            <button
              class="accordion-trigger"
              id="acc-btn-2"
              aria-expanded="false"
              aria-controls="acc-body-2"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">🗝️</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-2">Delegated Right of Divorce</span>
                <span class="trigger-tag">Talaq al-Tafwid</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-2" role="region" aria-labelledby="acc-btn-2">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>The husband can agree to give you the right to divorce yourself (talaq al-tafwid) without needing to go to court. This means you can end the marriage if you need to, without depending on his permission.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Gives you equal ability to exit the marriage.</li>
                <li>Recognised by classical Islamic scholars including Ibn Qudama and the Hanbali school.</li>
                <li>Especially important if you are in a country where Islamic divorce is not legally enforced.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Fiqh basis: Al-Mughni (Ibn Qudama); Hanbali, Shafi'i, and Maliki jurisprudence
              </div>
            </div>
          </article>

          <!-- 3. Financial Independence -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-3">
            <button
              class="accordion-trigger"
              id="acc-btn-3"
              aria-expanded="false"
              aria-controls="acc-body-3"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">💰</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-3">Financial Independence</span>
                <span class="trigger-tag">Control over your own money</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-3" role="region" aria-labelledby="acc-btn-3">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>Islam already gives women the right to own and manage their own money and property. This clause makes it clear in the contract that your earnings and assets are yours alone.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Prevents a husband from controlling or taking your income.</li>
                <li>Strengthens your independence if the marriage ends.</li>
                <li>Islamic law is clear: a woman's wealth is her own property.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Qur'an 4:32 — "Men have a share of what they earn and women have a share of what they earn."
              </div>
            </div>
          </article>

          <!-- 4. Right to Work -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-4">
            <button
              class="accordion-trigger"
              id="acc-btn-4"
              aria-expanded="false"
              aria-controls="acc-body-4"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">👩‍💼</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-4">Right to Work</span>
                <span class="trigger-tag">Keep your career or employment</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-4" role="region" aria-labelledby="acc-btn-4">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>You can include a condition that says your husband will not prevent you from working in a permissible (halal) job of your choosing.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Prevents isolation and financial dependence.</li>
                <li>Women in early Islamic history worked, traded, and ran businesses — Khadijah RA being a clear example.</li>
                <li>Gives you security and independence within the marriage.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Example: Khadijah bint Khuwaylid RA — a successful businesswoman and the Prophet's ﷺ wife.
              </div>
            </div>
          </article>

          <!-- 5. Right to Education -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-5">
            <button
              class="accordion-trigger"
              id="acc-btn-5"
              aria-expanded="false"
              aria-controls="acc-body-5"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">📚</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-5">Right to Education</span>
                <span class="trigger-tag">Continue studying or learning</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-5" role="region" aria-labelledby="acc-btn-5">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>This condition states that you have the right to continue your education — whether that is at school, college, university, or through Islamic study — after marriage.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Education is a right — and a duty — for every Muslim, men and women equally.</li>
                <li>Prevents a husband from stopping your studies.</li>
                <li>Investing in your education protects your future and your children's future.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Hadith: "Seeking knowledge is an obligation upon every Muslim." (Ibn Majah, 224)
              </div>
            </div>
          </article>

          <!-- 6. Separate Housing -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-6">
            <button
              class="accordion-trigger"
              id="acc-btn-6"
              aria-expanded="false"
              aria-controls="acc-body-6"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">🏠</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-6">Separate Housing from In-Laws</span>
                <span class="trigger-tag">Your own home as a couple</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-6" role="region" aria-labelledby="acc-btn-6">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>You can ask that your husband provides you with a home of your own — separate from his parents' or family's home — where you have privacy and autonomy.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Islamic scholars agree that a wife has the right to a private, suitable home.</li>
                <li>Reduces family conflict and protects your privacy as a couple.</li>
                <li>A woman cannot be forced to live with in-laws under Islamic law.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Qur'an 65:6 — "Lodge them [wives] where you dwell, according to your means."
              </div>
            </div>
          </article>

          <!-- 7. Protection from Abuse -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-7">
            <button
              class="accordion-trigger"
              id="acc-btn-7"
              aria-expanded="false"
              aria-controls="acc-body-7"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">🛡️</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-7">Protection from Abuse</span>
                <span class="trigger-tag">Safety and dignity in marriage</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-7" role="region" aria-labelledby="acc-btn-7">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>This clause confirms that any form of abuse — physical, emotional, verbal, or financial — is a breach of the marriage contract and of Islamic teachings, and gives you the right to end the marriage if it occurs.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Abuse is haram (forbidden) in Islam — the Prophet ﷺ never harmed a woman.</li>
                <li>Makes it explicit and documented in the contract.</li>
                <li>Can support legal action in your country of residence.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Hadith: "The best of you are those who are the best to their wives." (Tirmidhi, 3895)
              </div>
            </div>
          </article>

          <!-- 8. Right to Travel -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-8">
            <button
              class="accordion-trigger"
              id="acc-btn-8"
              aria-expanded="false"
              aria-controls="acc-body-8"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">✈️</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-8">Right to Travel</span>
                <span class="trigger-tag">Freedom of movement</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-8" role="region" aria-labelledby="acc-btn-8">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>You can include a condition that allows you to travel for work, education, family visits, or Hajj/Umrah, either alone or with a mahram, without unreasonable restriction.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Prevents control and isolation through restriction of movement.</li>
                <li>Protects your ability to visit family, attend medical appointments, or pursue education.</li>
                <li>Can be tailored to your specific needs and beliefs.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Classical fiqh recognises conditions around travel in the Nikah as valid.
              </div>
            </div>
          </article>

          <!-- 9. Fair Mahr -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-9">
            <button
              class="accordion-trigger"
              id="acc-btn-9"
              aria-expanded="false"
              aria-controls="acc-body-9"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">🌟</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-9">Fair Mahr</span>
                <span class="trigger-tag">Your bridal gift — your right</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-9" role="region" aria-labelledby="acc-btn-9">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>Mahr is a gift from the husband to the wife — it is her right, and hers alone. It can be money, gold, property, or something else of value. The amount and timing of payment should be clearly written in the Nikah.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>A mahr is not optional — it is a Qur'anic obligation.</li>
                <li>A clearly stated mahr prevents disputes later.</li>
                <li>Specify whether it is paid upfront (mu'ajjal) or deferred (mu'akhar) — or both.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Qur'an 4:4 — "Give women their mahr as a free gift."
              </div>
            </div>
          </article>

          <!-- 10. Right to Mediation -->
          <article class="accordion-card" role="listitem" aria-labelledby="acc-title-10">
            <button
              class="accordion-trigger"
              id="acc-btn-10"
              aria-expanded="false"
              aria-controls="acc-body-10"
              onclick="toggleAccordion(this)"
              type="button">
              <span class="trigger-icon" aria-hidden="true">🤝</span>
              <span class="trigger-text">
                <span class="trigger-title" id="acc-title-10">Right to Mediation</span>
                <span class="trigger-tag">Fair resolution during disputes</span>
              </span>
              <span class="trigger-chevron" aria-hidden="true">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none">
                  <path d="M6 9l6 6 6-6" stroke="#0d5f6b" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
              </span>
            </button>
            <div class="accordion-body" id="acc-body-10" role="region" aria-labelledby="acc-btn-10">
              <div class="accordion-body__divider"></div>
              <h4>What it means</h4>
              <p>You can include a condition that in the event of a serious dispute, both parties agree to seek mediation — from an imam, Islamic scholar, or qualified mediator — before any other steps are taken.</p>
              <h4>Why it protects you</h4>
              <ul>
                <li>Ensures disputes are handled fairly and with both parties heard.</li>
                <li>The Qur'an itself instructs the appointment of arbiters from both families in cases of dispute.</li>
                <li>Prevents decisions being made unilaterally or under pressure.</li>
              </ul>
              <div class="reference-pill" aria-label="Islamic reference">
                📖 Qur'an 4:35 — "If you fear a breach between them, appoint an arbiter from his family and an arbiter from her family."
              </div>
            </div>
          </article>

        </div><!-- /.rights-grid -->
      </section>
    </div><!-- /.section--alt -->

    <!-- ===== SECTION 3: EXAMPLE WORDING ===== -->
    <section id="example-wording" class="section" aria-labelledby="example-title">
      <div class="title-divider" aria-hidden="true"></div>
      <h2 class="section-title" id="example-title">Example Nikah Contract Clause Wording</h2>
      <p class="section-subtitle">
        You can show these example sentences to an imam, Islamic scholar, or family lawyer. They are starting points — a qualified person can help you finalise the wording.
      </p>

      <div class="example-section" role="region" aria-label="Example contract clauses">
        <h3>📋 Sample Clauses</h3>
        <p>These are examples only. Always seek advice from a qualified scholar or lawyer for your situation and country.</p>

        <div class="clause-example">
          <div class="clause-example__title">Monogamy / Polygamy Consent</div>
          <p class="clause-example__text">"The husband agrees that he will not enter into a second marriage during the subsistence of this marriage without the prior written consent of the wife. If this condition is breached, the wife shall have the right to divorce herself (talaq al-tafwid)."</p>
        </div>

        <div class="clause-example">
          <div class="clause-example__title">Delegated Right of Divorce (Talaq al-Tafwid)</div>
          <p class="clause-example__text">"The husband delegates to the wife the right to divorce herself (talaq al-tafwid) in the event that [specific condition is breached / at any time of her choosing]."</p>
        </div>

        <div class="clause-example">
          <div class="clause-example__title">Right to Work and Education</div>
          <p class="clause-example__text">"The husband agrees that the wife shall retain the right to pursue employment and education of her choosing, provided it is lawful (halal), and shall not be prevented from doing so."</p>
        </div>

        <div class="clause-example">
          <div class="clause-example__title">Separate Accommodation</div>
          <p class="clause-example__text">"The husband agrees to provide the wife with a suitable, private home separate from his family home, in which she has full privacy and autonomy in managing the household."</p>
        </div>

        <div class="clause-example">
          <div class="clause-example__title">Protection from Harm</div>
          <p class="clause-example__text">"Any act of physical, emotional, verbal, or financial abuse by the husband shall be considered a material breach of this contract, entitling the wife to seek dissolution of the marriage."</p>
        </div>

        <div class="clause-example">
          <div class="clause-example__title">Mahr</div>
          <p class="clause-example__text">"The agreed mahr is [amount/description]. The amount of [X] shall be paid immediately (mu'ajjal) upon marriage, and the deferred mahr (mu'akhar) of [amount] shall be paid upon [divorce / death / demand]."</p>
        </div>

        <button class="print-btn" onclick="window.print()" aria-label="Print this page to save the example clauses">
          🖨️ Print / Save This Page
        </button>
      </div>
    </section>

    <!-- ===== SECTION 4: IMPORTANT REMINDER ===== -->
    <section class="section" aria-labelledby="reminder-title" style="padding-top: 0;">
      <div class="title-divider" aria-hidden="true"></div>
      <h2 class="section-title" id="reminder-title">Important Reminder</h2>

      <div class="reminder-banner" role="note" aria-label="Important legal notice">
        <div class="reminder-banner__icon" aria-hidden="true">⚠️</div>
        <div>
          <h3>Please read this carefully</h3>
          <ul>
            <li><strong>Laws are different in every country.</strong> The legal standing of Nikah conditions varies depending on where you live. In some countries the Nikah has no legal recognition — you may also need a civil marriage.</li>
            <li><strong>Seek legal advice if you can.</strong> A family lawyer, or an organisation that supports Muslim women, can help you ensure your contract is valid both Islamically and legally in your country.</li>
            <li><strong>This page is for education only.</strong> It is not legal advice. It is a starting point to help you understand your rights and have informed conversations.</li>
            <li><strong>You are not alone.</strong> Many organisations exist to help Muslim women navigate marriage contracts and family law. See the Resources section below.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- ===== SECTION 5: RESOURCES ===== -->
    <div class="section--alt">
      <section id="resources" class="section section--alt-inner full-width-section" aria-labelledby="resources-title">
        <div class="title-divider" aria-hidden="true"></div>
        <h2 class="section-title" id="resources-title">Resources &amp; Support</h2>
        <p class="section-subtitle">You do not have to navigate this alone. Below are types of support available. Ask a trusted person to help you search for local services.</p>

        <div class="resources-grid" role="list">

          <div class="resource-card" role="listitem">
            <div class="resource-card__header">
              <div class="resource-card__icon-wrap" aria-hidden="true">⚖️</div>
              <h3>Legal Advice</h3>
            </div>
            <p>Look for a family law solicitor or lawyer who has experience with Islamic family law and civil marriage law in your country.</p>
            <div class="resource-placeholder" role="note">
              Placeholder: Add local legal aid organisation links here (e.g., Legal Aid UK, local bar association, Muslim legal helplines).
            </div>
          </div>

          <div class="resource-card" role="listitem">
            <div class="resource-card__header">
              <div class="resource-card__icon-wrap" aria-hidden="true">🤲</div>
              <h3>Women's Support Organisations</h3>
            </div>
            <p>Many organisations support Muslim women with marriage, divorce, and family issues — offering confidential, sensitive, and culturally informed help.</p>
            <ul class="resource-link-list" aria-label="Example organisations (placeholder)">
              <li><a href="#" aria-label="Placeholder: Muslim Women's Network UK">🔗 Muslim Women's Network UK (placeholder)</a></li>
              <li><a href="#" aria-label="Placeholder: Nour DV domestic violence charity">🔗 Nour DV — Domestic Violence Support (placeholder)</a></li>
              <li><a href="#" aria-label="Placeholder: Karma Nirvana honour abuse charity">🔗 Karma Nirvana — Honour Abuse (placeholder)</a></li>
              <li><a href="#" aria-label="Placeholder: Islamic Family Advice Bureau">🔗 Islamic Family Advice Bureau (placeholder)</a></li>
            </ul>
          </div>

          <div class="resource-card" role="listitem">
            <div class="resource-card__header">
              <div class="resource-card__icon-wrap" aria-hidden="true">📖</div>
              <h3>Educational Resources</h3>
            </div>
            <p>Learn more about Islamic family law, your rights, and how scholars have discussed these issues throughout history.</p>
            <ul class="resource-link-list" aria-label="Example educational resources (placeholder)">
              <li><a href="#" aria-label="Placeholder: Nikah rights guide from scholarly source">📄 Nikah Contract Rights — Scholar Guide (placeholder)</a></li>
              <li><a href="#" aria-label="Placeholder: Islamic women's fiqh resource">📄 Islamic Fiqh for Women (placeholder)</a></li>
              <li><a href="#" aria-label="Placeholder: Qur'an translation resource">📄 Qur'an — Clear English Translation (placeholder)</a></li>
            </ul>
          </div>

          <div class="resource-card" role="listitem">
            <div class="resource-card__header">
              <div class="resource-card__icon-wrap" aria-hidden="true">🆘</div>
              <h3>If You Are in Danger</h3>
            </div>
            <p>If you are in immediate danger, please contact emergency services. If you need confidential support, a domestic abuse helpline can help.</p>
            <ul class="resource-link-list" aria-label="Emergency contacts (placeholder)">
              <li><a href="tel:999" aria-label="Emergency: Call 999 (UK emergency services)">📞 Emergency: 999 (UK) / 911 (US)</a></li>
              <li><a href="#" aria-label="Placeholder: National Domestic Abuse Helpline">📞 National Domestic Abuse Helpline (placeholder)</a></li>
              <li><a href="#" aria-label="Placeholder: Forced Marriage Unit">📞 Forced Marriage Unit — 020 7008 0151 (UK)</a></li>
            </ul>
          </div>

        </div>
      </section>
    </div>

  </main>

  <!-- ===== FOOTER ===== -->
  <footer role="contentinfo">
    <div class="footer-logo">☽ Know Your Nikah Rights</div>
    <p>
      This website provides <strong>educational information only</strong> — it is not legal advice.<br>
      Always consult a qualified Islamic scholar and/or lawyer for your personal situation.<br>
      Information is based on classical Islamic jurisprudence and widely accepted scholarly positions.
    </p>
    <p style="margin-top: 16px;">
      <em>"And among His signs is that He created for you mates from among yourselves, that you may find tranquillity in them, and He placed between you affection and mercy."</em><br>
      <strong>— Qur'an 30:21</strong>
    </p>
    <p style="margin-top: 20px; font-size: 0.78rem; opacity: 0.55;">
      Placeholder website · Built for educational use · Content verified by [Islamic scholar placeholder] · Last updated March 2026
    </p>
  </footer>

  <!-- ===== JAVASCRIPT ===== -->
  <script>
    // ---- Quick Exit ----
    function quickExit() {
      // Immediately replace current page in history and redirect
      window.location.replace('https://www.google.com');
    }
    // Keyboard shortcut: Press Escape twice quickly to exit
    let escCount = 0;
    let escTimer;
    document.addEventListener('keydown', function(e) {
      if (e.key === 'Escape') {
        escCount++;
        clearTimeout(escTimer);
        if (escCount >= 2) { quickExit(); }
        escTimer = setTimeout(() => { escCount = 0; }, 800);
      }
    });

    // ---- Text-to-Speech (placeholder) ----
    function handleTTS() {
      const btn = document.getElementById('tts-btn');
      if ('speechSynthesis' in window) {
        if (window.speechSynthesis.speaking) {
          window.speechSynthesis.cancel();
          btn.textContent = '';
          btn.innerHTML = `<svg width="16" height="16" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M11 5L6 9H2v6h4l5 4V5z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.54 8.46a5 5 0 0 1 0 7.07M19.07 4.93a10 10 0 0 1 0 14.14" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg> Read Aloud`;
          return;
        }
        // Read main headings and visible paragraph text
        const textContent = document.getElementById('main-content').innerText;
        const utterance = new SpeechSynthesisUtterance(textContent);
        utterance.rate = 0.88;
        utterance.lang = 'en-GB';
        utterance.onend = () => {
          btn.innerHTML = `<svg width="16" height="16" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M11 5L6 9H2v6h4l5 4V5z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.54 8.46a5 5 0 0 1 0 7.07M19.07 4.93a10 10 0 0 1 0 14.14" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg> Read Aloud`;
        };
        window.speechSynthesis.speak(utterance);
        btn.innerHTML = `<svg width="16" height="16" viewBox="0 0 24 24" fill="none" aria-hidden="true"><rect x="6" y="4" width="4" height="16" rx="1" fill="currentColor"/><rect x="14" y="4" width="4" height="16" rx="1" fill="currentColor"/></svg> Stop Reading`;
      } else {
        alert('Sorry, your browser does not support text-to-speech. Try using Google Chrome.');
      }
    }

    // ---- Accordion ----
    function toggleAccordion(btn) {
      const card = btn.closest('.accordion-card');
      const body = card.querySelector('.accordion-body');
      const isOpen = card.classList.contains('accordion-card--open');

      // Close all open accordions
      document.querySelectorAll('.accordion-card--open').forEach(openCard => {
        openCard.classList.remove('accordion-card--open');
        openCard.querySelector('.accordion-body').classList.remove('accordion-body--open');
        openCard.querySelector('.accordion-trigger').setAttribute('aria-expanded', 'false');
      });

      // If it wasn't open, open it
      if (!isOpen) {
        card.classList.add('accordion-card--open');
        body.classList.add('accordion-body--open');
        btn.setAttribute('aria-expanded', 'true');
        // Smooth scroll to card
        setTimeout(() => {
          card.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
        }, 50);
      }
    }

    // ---- Language selector (placeholder handler) ----
    document.getElementById('lang-select').addEventListener('change', function() {
      const lang = this.value;
      if (lang !== 'en') {
        alert('Translation for ' + this.options[this.selectedIndex].text + ' is coming soon. For now, please use your browser\'s built-in translation feature (right-click > Translate).');
        this.value = 'en';
      }
    });
  </script>

</body>
</html>
