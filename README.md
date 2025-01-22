<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Photo - Raphaël</title>
    <style>
        /* Styles généraux */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }

        nav {
            background-color: #34495e;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1em;
        }
        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background-image: url('https://via.placeholder.com/1200x400?text=Bienvenue+sur+mon+Blog+Photo');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
            background-blend-mode: multiply;
            background-color: rgba(44, 62, 80, 0.6);
        }
        .hero h2 {
            font-size: 2.5em;
            margin: 0 0 10px;
        }
        .hero p {
            font-size: 1.2em;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 40px 20px;
            background-color: white;
        }
        .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }
        .gallery-item:hover img {
            transform: scale(1.1);
        }
        .gallery-item .caption {
            position: absolute;
            bottom: 0;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            width: 100%;
            text-align: center;
            padding: 10px 0;
            font-size: 1em;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        .gallery-item:hover .caption {
            opacity: 1;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Le Blog Photo de Raphaël</h1>
        <p>Partage de moments capturés à travers mon objectif</p>
    </header>
    <nav>
        <a href="#">Accueil</a>
        <a href="#">Galerie</a>
        <a href="#">À propos</a>
        <a href="#">Contact</a>
    </nav>
    <div class="hero">
        <h2>Bienvenue sur mon blog</h2>
        <p>Découvrez mes photos et mes aventures photographiques.</p>
    </div>
    <section class="gallery">
        <div class="gallery-item">
            <img src="https://via.placeholder.com/300x200" alt="Photo 1">
            <div class="caption">Photo 1 - Une belle vue</div>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/300x200" alt="Photo 2">
            <div class="caption">Photo 2 - Instant magique</div>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/300x200" alt="Photo 3">
            <div class="caption">Photo 3 - Nature à l’état pur</div>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/300x200" alt="Photo 4">
            <div class="caption">Photo 4 - Coucher de soleil</div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Raphaël Photographie - Tous droits réservés.</p>
    </footer>
</body>
</html>
