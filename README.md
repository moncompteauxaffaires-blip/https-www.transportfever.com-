# https-www.transportfever.com-
https://www.transportfever.com/


<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Construisez votre empire du transport, de la locomotive à grande vitesse au réseau mondial.">
  <title>Railway Empire — Construisez votre réseau</title>

  <style>
    :root {
      color-scheme: dark;
      --ink: #f4f3ef;
      --muted: #c4c6c5;
      --night: #10191d;
      --panel: #19262b;
      --gold: #efb85d;
      --line: rgb(255 255 255 / 15%);
    }

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      color: var(--ink);
      background: var(--night);
      font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
    }

    a { color: inherit; text-decoration: none; }

    .hero {
      min-height: 760px;
      position: relative;
      display: flex;
      flex-direction: column;
      overflow: hidden;
      background:
        linear-gradient(90deg, rgb(8 15 19 / 88%), rgb(8 15 19 / 15%)),
        linear-gradient(0deg, var(--night), transparent 40%),
        radial-gradient(ellipse at 75% 42%, #8a653d 0, #35464a 25%, #17272c 60%, #10191d 100%);
    }

    .hero::after {
      position: absolute;
      content: "";
      inset: 45% -5% 10%;
      transform: rotate(-8deg);
      border-top: 5px solid rgb(239 184 93 / 50%);
      border-bottom: 2px solid rgb(255 255 255 / 18%);
      box-shadow: 0 -12px 0 rgb(255 255 255 / 10%), 0 12px 0 rgb(255 255 255 / 8%);
      pointer-events: none;
    }

    header, main, footer { position: relative; z-index: 1; }

    header {
      width: min(1180px, calc(100% - 40px));
      margin: auto;
      padding: 26px 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 24px;
      border-bottom: 1px solid var(--line);
    }

    .brand {
      font-size: 1.15rem;
      font-weight: 850;
      letter-spacing: .12em;
      text-transform: uppercase;
    }

    nav { display: flex; gap: 28px; color: var(--muted); font-size: .92rem; }
    nav a:hover { color: var(--gold); }

    .hero-content {
      width: min(1180px, calc(100% - 40px));
      margin: auto;
      padding: 110px 0 150px;
    }

    .eyebrow {
      color: var(--gold);
      font-size: .78rem;
      font-weight: 800;
      letter-spacing: .2em;
      text-transform: uppercase;
    }

    h1 {
      max-width: 700px;
      margin: 18px 0;
      font-size: clamp(3rem, 8vw, 6.7rem);
      line-height: .92;
      letter-spacing: -.06em;
      text-transform: uppercase;
    }

    .intro {
      max-width: 560px;
      color: var(--muted);
      font-size: 1.15rem;
      line-height: 1.7;
    }

    .actions { display: flex; flex-wrap: wrap; gap: 14px; margin-top: 30px; }

    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 48px;
      padding: 0 22px;
      border: 1px solid var(--gold);
      background: var(--gold);
      color: #172024;
      font-weight: 800;
      transition: transform .2s, background .2s;
    }

    .button:hover { transform: translateY(-2px); background: #ffd184; }
    .button.secondary { background: transparent; color: var(--ink); border-color: var(--line); }

    .section {
      width: min(1180px, calc(100% - 40px));
      margin: auto;
      padding: 90px 0;
    }

    .section-heading {
      max-width: 700px;
      margin-bottom: 35px;
    }

    h2 {
      margin: 10px 0;
      font-size: clamp(2rem, 5vw, 3.6rem);
      line-height: 1;
      letter-spacing: -.04em;
      text-transform: uppercase;
    }

    .section-heading p, .card p {
      color: var(--muted);
      line-height: 1.7;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .card {
      min-height: 250px;
      padding: 28px;
      border: 1px solid var(--line);
      background: linear-gradient(145deg, #203238, var(--panel));
    }

    .card .number { color: var(--gold); font-weight: 800; letter-spacing: .12em; }
    .card h3 { margin: 28px 0 8px; font-size: 1.4rem; }

    .callout {
      padding: 60px 30px;
      text-align: center;
      background:
        linear-gradient(rgb(10 18 21 / 65%), rgb(10 18 21 / 85%)),
        radial-gradient(ellipse at center, #52605a, #19262b 70%);
      border: 1px solid var(--line);
    }

    .callout p { max-width: 600px; margin: 16px auto 26px; color: var(--muted); }

    footer {
      padding: 28px 20px;
      border-top: 1px solid var(--line);
      color: var(--muted);
      text-align: center;
      font-size: .9rem;
    }

    @media (max-width: 720px) {
      header { align-items: flex-start; flex-direction: column; }
      nav { flex-wrap: wrap; gap: 14px 20px; }
      .hero { min-height: 690px; }
      .hero-content { padding: 85px 0 130px; }
      .features { grid-template-columns: 1fr; }
      .card { min-height: 0; }
    }
  </style>
</head>

<body>
  <section class="hero" id="accueil">
    <header>
      <a class="brand" href="#accueil">Railway Empire</a>
      <nav aria-label="Navigation principale">
        <a href="#jeu">Le jeu</a>
        <a href="#fonctionnalites">Fonctionnalités</a>
        <a href="#commencer">Commencer</a>
      </nav>
    </header>

    <main class="hero-content">
      <p class="eyebrow">Bâtissez. Reliez. Développez.</p>
      <h1>Le monde est à vous.</h1>
      <p class="intro">
        Concevez des lignes ferroviaires, reliez des villes et transformez
        votre petite compagnie en un réseau de transport prospère.
      </p>
      <div class="actions">
        <a class="button" href="#commencer">Découvrir le jeu</a>
        <a class="button secondary" href="#fonctionnalites">Explorer les possibilités</a>
      </div>
    </main>
  </section>

  <section class="section" id="jeu">
    <div class="section-heading">
      <p class="eyebrow">Votre prochaine grande aventure</p>
      <h2>Chaque ligne change la donne.</h2>
      <p>
        Transportez voyageurs et marchandises, répondez aux besoins des villes
        et planifiez un réseau capable de traverser les époques.
      </p>
    </div>

    <div class="features" id="fonctionnalites">
      <article class="card">
        <span class="number">01 / CONSTRUIRE</span>
        <h3>Tracez votre réseau</h3>
        <p>Reliez les villes par le rail et développez des itinéraires adaptés au terrain.</p>
      </article>
      <article class="card">
        <span class="number">02 / TRANSPORTER</span>
        <h3>Faites circuler l’économie</h3>
        <p>Déplacez passagers et ressources avec des lignes pensées pour être efficaces.</p>
      </article>
      <article class="card">
        <span class="number">03 / PROSPÉRER</span>
        <h3>Voyez grand</h3>
        <p>Investissez dans votre compagnie et faites évoluer vos services au fil du temps.</p>
      </article>
    </div>
  </section>

  <section class="section" id="commencer">
    <div class="callout">
      <p class="eyebrow">À vous de jouer</p>
      <h2>Prêt à prendre les commandes ?</h2>
      <p>Planifiez votre première ligne et commencez à bâtir votre empire du transport.</p>
      <a class="button" href="#accueil">Retour en haut</a>
    </div>
  </section>

  <footer>
    <p>Projet de démonstration non officiel — remplacez ce contenu par vos propres textes et visuels.</p>
  </footer>
</body>
</html>
