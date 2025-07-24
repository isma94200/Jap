<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sakura Sushi - Restaurant Japonais</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #d7000f;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #333;
            padding: 10px 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            background-image: url('https://images.unsplash.com/photo-1553621042-f6e147245754');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            margin-bottom: 30px;
        }
        .hero h1 {
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .specialties {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .specialty-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .specialty-card:hover {
            transform: translateY(-10px);
        }
        .specialty-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .specialty-card-content {
            padding: 15px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sakura Sushi</h1>
        <p>Authentique cuisine japonaise depuis 2005</p>
    </header>
    <nav>
        <ul>
            <li><a href="#accueil">Accueil</a></li>
            <li><a href="#specialites">Spécialités</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <section id="accueil" class="hero">
            <div>
                <h1>Découvrez les saveurs du Japon</h1>
                <p>Nos chefs préparent chaque plat avec passion et authenticité</p>
            </div>
        </section>
        
        <section id="specialites">
            <h2>Nos spécialités japonaises</h2>
            <div class="specialties">
                <div class="specialty-card">
                    <img src="https://images.unsplash.com/photo-1579871494447-9811cf80d66c" alt="Sushi">
                    <div class="specialty-card-content">
                        <h3>Sushi Variés</h3>
                        <p>Assortiment de sushi frais préparés quotidiennement avec du poisson de première qualité.</p>
                    </div>
                </div>
                <div class="specialty-card">
                    <img src="https://images.unsplash.com/photo-1611270633750-8d1e062d4388" alt="Ramen">
                    <div class="specialty-card-content">
                        <h3>Ramen Traditionnel</h3>
                        <p>Notre ramen signature avec bouillon mijoté pendant 12 heures, nouilles faites maison et garnitures fraîches.</p>
                    </div>
                </div>
                <div class="specialty-card">
                    <img src="https://images.unsplash.com/photo-1626804475297-41608ea09aeb" alt="Tempura">
                    <div class="specialty-card-content">
                        <h3>Tempura</h3>
                        <p>Beignets légers et croustillants de crevettes et légumes de saison, servis avec sauce tentsuyu.</p>
                    </div>
                </div>
                <div class="specialty-card">
                    <img src="https://images.unsplash.com/photo-1601050690597-df0568f70950" alt="Yakitori">
                    <div class="specialty-card-content">
                        <h3>Yakitori</h3>
                        <p>Brochettes de poulet grillées au charbon de bois, marinées dans notre sauce tare secrète.</p>
                    </div>
                </div>
                <div class="specialty-card">
                    <img src="https://images.unsplash.com/photo-1617196035154-1e2b7e1a61c3" alt="Okonomiyaki">
                    <div class="specialty-card-content">
                        <h3>Okonomiyaki</h3>
                        <p>"Pizza japonaise" à base de chou, porc, fruits de mer et garnie de mayonnaise et sauce okonomiyaki.</p>
                    </div>
                </div>
                <div class="specialty-card">
                    <img src="https://images.unsplash.com/photo-1585032226651-759b368d7246" alt="Matcha Dessert">
                    <div class="specialty-card-content">
                        <h3>Desserts au Matcha</h3>
                        <p>Selection de desserts traditionnels japonais à base de thé matcha de qualité supérieure.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="contact">
            <h2>Contactez-nous</h2>
            <p>Adresse : 15 Rue des Cerisiers, 75000 Paris</p>
            <p>Téléphone : 01 23 45 67 89</p>
            <p>Ouvert du mardi au dimanche, de 12h à 14h30 et de 19h à 22h30</p>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2023 Sakura Sushi - Tous droits réservés</p>
    </footer>
</body>
</html>
