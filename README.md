index.html

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LIKA-SHOP | Accueil</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>LIKA-SHOP</h1>
      <nav>
        <a href="index.html">Accueil</a>
        <a href="catalogue.html">Catalogue</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>
  <main>
    <section class="hero">
      <h2>Bienvenue chez LIKA-SHOP</h2>
      <p>Découvrez nos collections de sacoches, chaussures, parfums et vêtements.</p>
      <a href="catalogue.html" class="btn">Voir le catalogue</a>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 LIKA-SHOP. Tous droits réservés.</p>
  </footer>
</body>
</html>

catalogue.html

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catalogue | LIKA-SHOP</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>LIKA-SHOP</h1>
      <nav>
        <a href="index.html">Accueil</a>
        <a href="catalogue.html">Catalogue</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>
  <main>
    <section class="catalogue">
      <h2>Nos Produits</h2>
      <div class="product-list">
        <div class="product-item">
          <img src="images/sacoche.jpg" alt="Sacoche">
          <h3>Sacoche élégante</h3>
          <p>Prix : 50€</p>
          <button>Ajouter au panier</button>
        </div>
        <div class="product-item">
          <img src="images/chaussures.jpg" alt="Chaussures">
          <h3>Chaussures en cuir</h3>
          <p>Prix : 80€</p>
          <button>Ajouter au panier</button>
        </div>
      </div>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 LIKA-SHOP. Tous droits réservés.</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | LIKA-SHOP</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>LIKA-SHOP</h1>
      <nav>
        <a href="index.html">Accueil</a>
        <a href="catalogue.html">Catalogue</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>
  <main>
    <section class="contact">
      <h2>Contactez-nous</h2>
      <form action="submit_form.php" method="POST">
        <label for="name">Nom :</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message :</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Envoyer</button>
      </form>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 LIKA-SHOP. Tous droits réservés.</p>
  </footer>
</body>
</html>

styles.css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background: #4CAF50;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

nav a {
  margin: 0 1rem;
  color: #fff;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 2rem;
  background: #f4f4f4;
}

.hero h2 {
  color: #4CAF50;
}

.btn {
  display: inline-block;
  padding: 0.5rem 1rem;
  color: #fff;
  background: #4CAF50;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 1rem;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
