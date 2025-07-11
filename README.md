# e-social
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Solidarité Ensemble</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .container {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .card {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      width: 250px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-top: 0;
    }
    .progress {
      background-color: #f3f3f3;
      border-radius: 5px;
      overflow: hidden;
      margin: 10px 0;
    }
    .progress-bar {
      height: 10px;
      background-color: #2ecc71;
    }
    .button {
      background-color: #2ecc71;
      color: white;
      padding: 10px;
      text-align: center;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      display: block;
      width: 100%;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <h1 style="text-align:center;">Solidarité Ensemble</h1>

  <div class="container">
    <!-- Carte 1 -->
    <div class="card">
      <h3>Aide alimentaire pour la famille Diallo</h3>
      <p>Aidez une famille de 6 personnes à faire face à des difficultés alimentaires après une mauvaise récolte.</p>
      <p><strong>Collecté :</strong> 450 000 FCFA</p>
      <p><strong>Objectif :</strong> 750 000 FCFA</p>
      <div class="progress">
        <div class="progress-bar" style="width: 60%;"></div>
      </div>
      <a href="#" class="button">Soutenir</a>
    </div>

    <!-- Carte 2 -->
    <div class="card">
      <h3>Scolarité pour les enfants de Ndangane</h3>
      <p>Financement des frais scolaires pour 25 enfants du village de Ndangane qui risquent d’abandonner l’école.</p>
      <p><strong>Collecté :</strong> 1 200 000 FCFA</p>
      <p><strong>Objectif :</strong> 2 500 000 FCFA</p>
      <div class="progress">
        <div class="progress-bar" style="width: 48%;"></div>
      </div>
      <a href="#" class="button">Soutenir</a>
    </div>

    <!-- Carte 3 -->
    <div class="card">
      <h3>Construction d’un puits à Kédougou</h3>
      <p>Aidez-nous à construire un puits pour permettre à 3 villages d’avoir accès à l’eau potable.</p>
      <p><strong>Collecté :</strong> 2 750 000 FCFA</p>
      <p><strong>Objectif :</strong> 3 500 000 FCFA</p>
      <div class="progress">
        <div class="progress-bar" style="width: 78%;"></div>
      </div>
      <a href="#" class="button">Soutenir</a>
    </div>
  </div>

</body>
</html>
