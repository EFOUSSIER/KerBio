<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>KerBio - Lait & Légumes Bio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #222;
    }
    header {
      background: #3b7d3b;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    header p {
      margin: 0.3rem 0 0;
      font-size: 1rem;
    }
    nav {
      background: #2f5f2f;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 0.5rem;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 0.4rem 0.8rem;
      border-radius: 4px;
      font-size: 0.9rem;
    }
    nav a:hover {
      background: #244624;
    }
    main {
      max-width: 1000px;
      margin: 1rem auto 2rem;
      padding: 0 1rem;
    }
    section {
      background: white;
      margin-bottom: 1rem;
      padding: 1rem;
      border-radius: 6px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    section h2 {
      margin-top: 0;
      color: #2f5f2f;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
    }
    .card {
      border: 1px solid #ddd;
      border-radius: 6px;
      padding: 0.8rem;
      background: #fafafa;
    }
    .card h3 {
      margin-top: 0;
      font-size: 1.1rem;
      color: #2f5f2f;
    }
    .price {
      font-weight: bold;
      color: #c05b1b;
      margin: 0.3rem 0;
    }
    .btn {
      display: inline-block;
      margin-top: 0.4rem;
      padding: 0.4rem 0.8rem;
      background: #3b7d3b;
      color: white;
      text-decoration: none;
      border-radius: 4px;
      font-size: 0.9rem;
    }
    .btn:hover {
      background: #2f5f2f;
    }
    .small {
      font-size: 0.9rem;
      color: #555;
    }
    form label {
      display: block;
      margin-top: 0.6rem;
      font-size: 0.9rem;
    }
    form input, form select, form textarea {
      width: 100%;
      padding: 0.4rem;
      margin-top: 0.2rem;
      border-radius: 4px;
      border: 1px solid #ccc;
      font-size: 0.9rem;
      box-sizing: border-box;
    }
    form button {
      margin-top: 0.8rem;
      padding: 0.5rem 1rem;
      background: #3b7d3b;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 0.95rem;
    }
    form button:hover {
      background: #2f5f2f;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.85rem;
      background: #eee;
      color: #555;
    }
  </style>
</head>
<body>

<header>
  <h1>KerBio</h1>
  <p>Lait et légumes bio en vente directe, près de chez vous.</p>
</header>

<nav>
  <a href="#presentation">Présentation</a>
  <a href="#lait">Produits laitiers</a>
  <a href="#legumes">Légumes</a>
  <a href="#paniers">Paniers</a>
  <a href="#commande">Commander</a>
  <a href="#infos">Infos pratiques</a>
</nav>

<main>

  <section id="presentation">
    <h2>Présentation</h2>
    <p>
      Bienvenue à <strong>KerBio</strong>, une ferme bio qui produit du lait et des légumes frais,
      directement pour les habitants du coin.
    </p>
    <p class="small">
      Production en agriculture biologique, respect des animaux, des sols et des saisons.
    </p>
  </section>

  <section id="lait">
    <h2>Produits laitiers KerBio</h2>
    <div class="grid">
      <div class="card">
        <h3>Lait bio frais</h3>
        <p>Lait de vache bio, entier, tiré à la ferme KerBio.</p>
        <p class="price">1,20 € / litre</p>
        <a href="#commande" class="btn">Ajouter à la commande</a>
      </div>
      <div class="card">
        <h3>Yaourts fermiers</h3>
        <p>Yaourts nature au lait entier bio KerBio.</p>
        <p class="price">2,80 € / lot de 4</p>
        <a href="#commande" class="btn">Ajouter à la commande</a>
      </div>
      <div class="card">
        <h3>Fromage frais</h3>
        <p>Fromage frais bio, fabriqué à KerBio.</p>
        <p class="price">3,50 € / barquette</p>
        <a href="#commande" class="btn">Ajouter à la commande</a>
      </div>
    </div>
  </section>

  <section id="legumes">
    <h2>Légumes bio KerBio</h2>
    <div class="grid">
      <div class="card">
        <h3>Tomates bio</h3>
        <p>Tomates de saison, cultivées à KerBio.</p>
        <p class="price">3,20 € / kg</p>
        <a href="#commande" class="btn">Ajouter à la commande</a>
      </div>
      <div class="card">
        <h3>Courgettes bio</h3>
        <p>Courgettes fraîches, récoltées le jour même.</p>
        <p class="price">2,80 € / kg</p>
        <a href="#commande" class="btn">Ajouter à la commande</a>
      </div>
      <div class="card">
        <h3>Panier de légumes variés</h3>
        <p>Mélange de légumes de saison produits à KerBio.</p>
        <p class="price">10,00 € / panier</p>
        <a href="#commande" class="btn">Ajouter à la commande</a>
      </div>
    </div>
  </section>

  <section id="paniers">
    <h2>Paniers KerBio</h2>
    <div class="grid">
      <div class="card">
        <h3>Petit panier</h3>
        <p>Pour 1 à 2 personnes.</p>
        <p class="price">8,00 €</p>
        <a href="#commande" class="btn">Commander</a>
      </div>
      <div class="card">
        <h3>Panier famille</h3>
        <p>Pour 3 à 5 personnes.</p>
        <p class="price">15,00 €</p>
        <a href="#commande" class="btn">Commander</a>
      </div>
      <div class="card">
        <h3>Panier soupe</h3>
        <p>Idéal pour faire des soupes maison.</p>
        <p class="price">12,00 €</p>
        <a href="#commande" class="btn">Commander</a>
      </div>
    </div>
  </section>

  <section id="commande">
    <h2>Commander chez KerBio</h2>
    <p>Remplissez ce formulaire pour réserver vos produits.</p>
    <form>
      <label for="nom">Nom et prénom</label>
      <input type="text" id="nom" name="nom" required>

      <label for="tel">Téléphone</label>
      <input type="tel" id="tel" name="tel" required>

      <label for="produits">Produits souhaités</label>
      <textarea id="produits" name="produits" rows="4" required></textarea>

      <label for="jour">Jour de retrait</label>
      <select id="jour" name="jour">
        <option value="mercredi">Mercredi</option>
        <option value="vendredi">Vendredi</option>
        <option value="samedi">Samedi</option>
      </select>

      <button type="submit">Envoyer</button>
    </form>
  </section>

  <section id="infos">
    <h2>Infos pratiques</h2>
    <p><strong>Adresse :</strong> KerBio, 123 chemin des Prés</p>
    <p><strong>Horaires :</strong></p>
    <ul>
      <li>Mercredi : 16h – 19h</li>
      <li>Vendredi : 17h – 19h</li>
      <li>Samedi : 9h – 12h</li>
    </ul>
    <p><strong>Contact :</strong> 06 00 00 00 00</p>
  </section>

</main>

<footer>
  &copy; KerBio – Vente directe lait & légumes bio.
</footer>

</body>
</html>
