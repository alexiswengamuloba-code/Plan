<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PLANING-E.D.A - Alexis</title>
    <style>
        /* --- CONFIGURATION GÉNÉRALE --- */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(180px, #000000, #808000); /* Dégradé noir vers olive */
            background-attachment: fixed;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* --- BARRE DE NAVIGATION DU HAUT --- */
        .top-nav {
            width: 100%;
            background: #f0f0f0;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-sizing: border-box;
            color: #00bcd4;
            font-weight: bold;
            font-size: 0.8rem;
        }

        .nav-buttons {
            display: flex;
            gap: 5px;
        }

        .nav-btn {
            padding: 5px 10px;
            border: 1px solid #00bcd4;
            background: transparent;
            color: #00bcd4;
            font-size: 0.7rem;
            border-radius: 3px;
        }

        .nav-btn.active {
            background: #00bcd4;
            color: white;
        }

        /* --- CONTENU PRINCIPAL --- */
        .container {
            width: 90%;
            max-width: 1000px;
            margin-top: 20px;
        }

        .main-title {
            font-size: 1.4rem;
            text-transform: uppercase;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }

        /* --- GRILLE DE BOUTONS (RESPONSIVE) --- */
        .submenu-container {
            display: grid;
            grid-template-columns: 1fr; /* 1 colonne sur petit mobile */
            gap: 10px;
            margin-bottom: 25px;
        }

        .btn-sub {
            padding: 12px;
            border: none;
            border-radius: 5px;
            color: white;
            font-weight: bold;
            cursor: pointer;
            text-align: center;
            transition: transform 0.2s;
        }

        .btn-sub:active { transform: scale(0.95); }

        /* Couleurs des boutons */
        .btn-blue { background: #0066ff; }
        .btn-purple { background: #9900ff; }
        .btn-green { background: #00b359; }
        .btn-dark { background: #333333; }

        /* --- CARTE DE DESCRIPTION --- */
        .description-card {
            background: #5c1a99; /* Violet comme sur ta capture */
            border-radius: 10px;
            padding: 20px;
            display: flex;
            flex-direction: column; /* Empilé sur mobile */
            align-items: center;
            gap: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        .project-img {
            width: 100%;
            max-width: 250px;
            border: 2px solid #00ffff;
            border-radius: 15px;
        }

        .text-content {
            text-align: center;
        }

        .text-content h3 { margin-top: 0; }

        /* --- FORMULAIRE --- */
        input {
            width: 100%;
            padding: 12px;
            margin-top: 15px;
            background: #111;
            border: 1px solid #444;
            color: #00ffcc;
            border-radius: 5px;
            box-sizing: border-box;
            font-size: 16px; /* Empêche le zoom auto iOS */
        }

        /* --- AJUSTEMENTS POUR ORDINATEUR (ECRANS > 768px) --- */
        @media (min-width: 768px) {
            .submenu-container {
                grid-template-columns: repeat(4, 1fr); /* 4 colonnes sur PC */
            }

            .description-card {
                flex-direction: row; /* Côte à côte sur PC */
                text-align: left;
            }

            .text-content {
                text-align: left;
            }

            .main-title {
                font-size: 2rem;
            }
        }

        /* --- ANIMATION --- */
        @keyframes fadeIn { from {opacity: 0;} to {opacity: 1;} }
        .container { animation: fadeIn 1s ease-in; }

    </style>
</head>
<body>

    <div class="top-nav">
        <div>PLANING-E.D.A (ENTITÉ D'ORGANISATION PAR ALEXIS)</div>
        <div class="nav-buttons">
            <button class="nav-btn">1. Accueil</button>
            <button class="nav-btn active">2. Planing</button>
        </div>
    </div>

    <div class="container">
        <h2 class="main-title">GESTION E.D.A</h2>

        <div class="submenu-container">
            <div class="btn-sub btn-blue">1. PLANING-E.D.A</div>
            <div class="btn-sub btn-purple">2. Mon Projet</div>
            <div class="btn-sub btn-green">3. E.D.A</div>
            <div class="btn-sub btn-dark">4. Configuration</div>
        </div>

        <div class="description-card">
            <img src="https://via.placeholder.com/250x50/000/00ffff?text=Alexis+Project" alt="Alexis Project" class="project-img">
            
            <div class="text-content">
                <h3>Description du Projet</h3>
                <p>Alexis a utilisé son initiative pour créer <strong>PLANING-E.D.A</strong> afin d'expliquer le fonctionnement du projet dans les villes comme <strong>Bukavu, Kamituga, etc.</strong></p>
            </div>
        </div>

        <input type="text" placeholder="Entrez une commande ou un projet...">
    </div>

</body>
</html>
