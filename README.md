# Rose-shancia--site
Site web moderne présentant les projets et activités de Rose Chancia
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rose Shancia Affiliation</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #111, #444);
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #ddd;
    }

    nav {
      background: #222;
      text-align: center;
      padding: 15px 10px;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s;
    }

    nav a:hover {
      color: #ffd700;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
      margin-top: 30px;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }

    /* Boutons réseaux sociaux */
    .social-buttons {
      margin-top: 20px;
    }

    .social-buttons a {
      display: inline-block;
      margin: 5px;
      padding: 12px 20px;
      border-radius: 8px;
      color: white;
      font-weight: bold;
      text-decoration: none;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .social-buttons a:hover {
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    .facebook { background: #3b5998; }
    .twitter { background: #1da1f2; }
    .instagram { background: #e4405f; }
    .linkedin { background: #0077b5; }
    .youtube { background: #ff0000; }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 25px 10px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      nav a {
        display: block;
        margin: 10px 0;
      }
      .social-buttons a {
        width: 100%;
        text-align: center;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Bienvenue sur le site de Rose Shancia</h1>
  <p>Site personnel – Présentation et affiliations</p>
</header>

<nav>
  <a href="#">Accueil</a>
  <a href="#about">À propos</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <div class="card">
    <h2>À propos de moi</h2>
    <p>Bonjour, je m'appelle Rose Shancia. Ceci est mon site personnel où je présente mes projets, activités et affiliations. Vous pouvez me suivre sur mes réseaux sociaux pour plus d'informations et collaborations.</p>

    <div class="social-buttons">
      <a href="https://www.facebook.com" class="facebook" target="_blank">Facebook</a>
      <a href="https://www.twitter.com" class="twitter" target="_blank">Twitter</a>
      <a href="https://www.instagram.com" class="instagram" target="_blank">Instagram</a>
      <a href="https://www.linkedin.com" class="linkedin" target="_blank">LinkedIn</a>
      <a href="https://www.youtube.com" class="youtube" target="_blank">YouTube</a>
    </div>
  </div>
</section>

<section id="contact">
  <div class="card">
    <h2>Contact</h2>
    <p>Email : <a href="mailto:zoeroumeni@gmail.com">zoeroumeni@gmail.com</a></p>
    <p>Téléphone : <a href="tel:+241065537936">+241 065 537936</a></p>
  </div>
</section>

<footer>
  <p>© 2026 Rose Shancia - Tous droits réservés</p>
</footer>

</body>
</html>
