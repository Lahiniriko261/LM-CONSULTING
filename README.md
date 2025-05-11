<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LM Consulting - Centre de Formation</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; }
    header { background: #003366; color: #fff; padding: 20px 0; text-align: center; }
    nav { background: #0059b3; display: flex; justify-content: center; flex-wrap: wrap; }
    nav a { color: white; padding: 14px 20px; text-decoration: none; }
    nav a:hover { background: #004080; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    footer { background: #003366; color: white; text-align: center; padding: 20px; }
    .card { background: #f4f4f4; padding: 20px; margin: 20px 0; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    form input, form textarea { width: 100%; padding: 10px; margin-top: 10px; margin-bottom: 20px; }
    form button { background: #0059b3; color: white; border: none; padding: 10px 20px; cursor: pointer; }
    form button:hover { background: #004080; }
  </style>
</head>
<body>
  <header>
    <h1>LM Consulting</h1>
    <p>Centre de formation, conseil et accompagnement</p>
  </header>
  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#apropos">À propos</a>
    <a href="#services">Nos services</a>
    <a href="#formations">Formations</a>
    <a href="#equipe">Équipe</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="accueil">
    <h2>Bienvenue chez LM Consulting</h2>
    <p>Nous vous accompagnons dans le renforcement des compétences, la formation professionnelle et le développement organisationnel.</p>
  </section>

  <section id="apropos">
    <h2>À propos de nous</h2>
    <div class="card">
      <p>LM Consulting est un centre de formation basé à Madagascar, spécialisé dans l’éducation, le coaching, le développement personnel et l’appui aux organisations de la société civile.</p>
    </div>
  </section>

  <section id="services">
    <h2>Nos services</h2>
    <div class="card">
      <ul>
        <li>Formation des enseignants et formateurs</li>
        <li>Coaching organisationnel</li>
        <li>Appui à la société civile</li>
        <li>Études et enquêtes</li>
        <li>Animation d’ateliers et séminaires</li>
      </ul>
    </div>
  </section>

  <section id="formations">
    <h2>Formations proposées</h2>
    <div class="card">
      <ul>
        <li>Utilisation éthique de l’intelligence artificielle</li>
        <li>Leadership et développement personnel</li>
        <li>Ingénierie de formation</li>
        <li>Approche genre et droits de l’enfant</li>
      </ul>
    </div>
  </section>

  <section id="equipe">
    <h2>Notre équipe</h2>
    <div class="card">
      <p><strong>Coach Thibault</strong> – Fondateur et Consultant principal</p>
      <p>Équipe pluridisciplinaire : éducateurs, juristes, psychologues, ingénieurs pédagogiques.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contactez-nous</h2>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <input type="text" name="name" placeholder="Votre nom" required>
      <input type="email" name="email" placeholder="Votre adresse email" required>
      <textarea name="message" placeholder="Votre message" rows="5" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 LM Consulting - Tous droits réservés</p>
  </footer>
</body>
</html>
