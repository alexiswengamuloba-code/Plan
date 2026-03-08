<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PLANING-E.D.A | Alexis Officiel</title>
    <style>
        :root {
            /* Dégradé jaune et rouge demandé */
            --eda-gradient: linear-gradient(135deg, #3a2f02, #d1c304);
            --accent-cyan: #00d4ff; 
            --text-light: #ffffff;
            --glass-dark: rgba(90, 4, 170, 0.9);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: var(--eda-gradient);
            background-attachment: fixed;
            color: var(--text-light);
            margin: 0;
            padding: 0;
            min-height: 100vh;
        }

        /* --- HEADER ADAPTATIF --- */
        header {
            background: rgba(248, 250, 249, 0.95);
            padding: 15px 5%;
            display: flex;
            flex-wrap: wrap; /* Permet le passage à la ligne sur téléphone */
            justify-content: space-between;
            align-items: center;
            border-bottom: 3px solid #01617e;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .main-title {
            font-size: 1.1rem;
            font-weight: bold;
            color: var(--accent-cyan);
            text-transform: uppercase;
            flex: 1;
            min-width: 280px;
            margin-bottom: 10px;
        }

        nav {
            display: flex;
            gap: 10px;
            justify-content: flex-end; /* Aligne les boutons à droite */
        }

        .btn-nav {
            padding: 10px 15px;
            background: transparent;
            border: 2px solid var(--accent-cyan);
            color: var(--accent-cyan);
            cursor: pointer;
            font-weight: bold;
            border-radius: 5px;
            white-space: nowrap;
            transition: 0.3s;
        }

        .btn-nav.active, .btn-nav:hover {
            background: var(--accent-cyan);
            color: #001106;
        }

        /* --- CONTENU --- */
        .content-section {
            display: none;
            padding: 20px 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .content-section.active { display: block; animation: fadeIn 0.5s ease; }

        /* Grille Accueil (Serveur Central) */
        .grid-accueil {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .project-card {
            background: var(--glass-dark);
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.1);
            position: relative;
        }

        .btn-open {
            display: inline-block;
            margin-top: 15px;
            padding: 8px 15px;
            background: #00ff88;
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        /* --- MENU DES 4 SOUS-BOUTONS --- */
        .submenu-container {
            display: flex;
            flex-direction: column; /* Colonne pour mobile */
            gap: 15px;
            margin-bottom: 30px;
        }

        .btn-sub {
            padding: 20px;
            border: none;
            border-radius: 12px;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            font-size: 1rem;
            transition: 0.3s;
        }

        .color-1 { background: #0055ff; }
        .color-2 { background: #9d00ff; }
        .color-3 { background: #00aa55; }
        .color-4 { background: #333333; }

        .btn-sub:hover { transform: scale(1.02); filter: brightness(1.1); }

        .sub-content {
            display: none;
            background: var(--glass-dark);
            padding: 30px;
            border-radius: 15px;
            margin-top: 20px;
            border: 1px solid rgba(255,255,255,0.1);
        }

        .sub-content.active { display: block; }

        /* MISE EN PAGE FLEXIBLE (Image/Texte) */
        .flex-container {
            display: flex;
            flex-direction: column; /* Vertical sur mobile */
            gap: 30px;
            align-items: center;
        }

        .flex-container img {
            width: 100%;
            max-width: 400px;
            border-radius: 12px;
            border: 3px solid var(--accent-cyan);
        }

        /* --- MEDIA QUERIES (POUR ORDINATEUR) --- */
        @media (min-width: 768px) {
            .main-title { font-size: 1.5rem; margin-bottom: 0; }
            .submenu-container { flex-direction: row; } /* Ligne sur PC */
            .flex-container { flex-direction: row; text-align: left; } /* Image à gauche sur PC */
            .btn-sub { flex: 1; }
        }

        /* Formulaire */
        input {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            background: #111;
            border: 1px solid #444;
            color: #fff;
            border-radius: 5px;
            box-sizing: border-box;
        }

        @keyframes fadeIn { from {opacity: 0;} to {opacity: 1;} }

        .delete-btn {
            position: absolute; top: 10px; right: 10px;
            background: #ff4444; color: white; border: none;
            border-radius: 50%; width: 25px; height: 25px; cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <div class="main-title">PLANING-E.D.A (Entité d'organisation par Alexis)</div>
    <nav>
        <button class="btn-nav active" onclick="showSection('accueil')">1. Accueil</button>
        <button class="btn-nav" onclick="showSection('planing')">2. Planing</button>
    </nav>
</header>

<section id="accueil" class="content-section active">
    <h1>SERVEUR CENTRAL</h1>
    <p>Tous vos projets connectés s'affichent ici.</p>
    <div id="project-list" class="grid-accueil"></div>
</section>

<section id="planing" class="content-section">
    <h1>GESTION E.D.A</h1>

    <div class="submenu-container">
        <button class="btn-sub color-1" onclick="showSub('sub1')">1. PLANING-E.D.A</button>
        <button class="btn-sub color-2" onclick="showSub('sub2')">2. Mon Projet</button>
        <button class="btn-sub color-3" onclick="showSub('sub3')">3. E.D.A</button>
        <button class="btn-sub color-4" onclick="showSub('sub4')">4. Configuration</button>
    </div>

    <div id="sub1" class="sub-content">
        <div class="flex-container">
            <img src="https://via.placeholder.com/400x250/00d4ff/000000?text=Alexis+Officiel" alt="Alexis Project">
            <div>
                <h2>Description du Projet</h2>
                <p style="font-size: 1.1rem; line-height: 1.6;">Alexis a utilisé son initiative pour créer <strong>PLANING-E.D.A.</strong> afin d’expliquer le fonctionnement du projet dans les villes comme <strong>Bukavu, Kamituga, etc.</strong></p>
            </div>
        </div>
    </div>

    <div id="sub2" class="sub-content">
        <h2>Ajouter un Projet au Serveur</h2>
        <input type="text" id="pName" placeholder="Nom du projet">
        <input type="text" id="pIcon" placeholder="Icône (ex: 💻, 🚀, 📂)">
        <input type="text" id="pUrl" placeholder="Lien URL (https://...)">
        <button onclick="saveProject()" style="width:100%; padding:15px; background:#00ff88; border:none; border-radius:5px; cursor:pointer; font-weight:bold;">ENREGISTRER</button>
    </div>

    <div id="sub3" class="sub-content">
        <h2>E.D.A</h2>
        <p>Structure organisationnelle pour la gestion de Bukavu et Kamituga.</p>
    </div>

    <div id="sub4" class="sub-content">
        <h2>Configuration</h2>
        <p>Options de maintenance du serveur central.</p>
    </div>
</section>

<script>
    // Navigation entre Accueil et Planing
    function showSection(id) {
        document.querySelectorAll('.content-section').forEach(s => s.classList.remove('active'));
        document.querySelectorAll('.btn-nav').forEach(b => b.classList.remove('active'));
        document.getElementById(id).classList.add('active');
        event.currentTarget.classList.add('active');
    }

    // Navigation entre les 4 sous-boutons
    function showSub(id) {
        document.querySelectorAll('.sub-content').forEach(c => c.classList.remove('active'));
        document.getElementById(id).classList.add('active');
    }

    // Gestion de la mémoire locale
    let storage = JSON.parse(localStorage.getItem('eda_final_v3')) || [];

    function saveProject() {
        const name = document.getElementById('pName').value;
        const icon = document.getElementById('pIcon').value || "📁";
        const url = document.getElementById('pUrl').value;
        if(name && url) {
            storage.push({ id: Date.now(), name, icon, url });
            localStorage.setItem('eda_final_v3', JSON.stringify(storage));
            render();
            alert("Projet synchronisé avec succès !");
            document.getElementById('pName').value = '';
            document.getElementById('pUrl').value = '';
        }
    }

    function deleteProject(id) {
        if(confirm("Supprimer ce projet ?")) {
            storage = storage.filter(p => p.id !== id);
            localStorage.setItem('eda_final_v3', JSON.stringify(storage));
            render();
        }
    }

    function render() {
        const list = document.getElementById('project-list');
        list.innerHTML = '';
        storage.forEach(p => {
            list.innerHTML += `
                <div class="project-card">
                    <button class="delete-btn" onclick="deleteProject(${p.id})">X</button>
                    <div style="font-size: 3rem; margin-bottom:10px;">${p.icon}</div>
                    <h3>${p.name}</h3>
                    <a href="${p.url}" target="_blank" class="btn-open">OUVRIR</a>
                </div>
            `;
        });
    }

    // Initialisation au chargement
    render();
</script>

</body>
</html>
