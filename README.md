<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Elegant nettbutikk for kvalitetstøy laget med fokus på materialer og håndverk.">
    <title>Kvalitetstøy Nettbutikk</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: #ffffff;
        }
        header {
            background-color: #1E1E1E;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 2rem;
            font-weight: bold;
            color: #F8C471;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 20px;
        }
        nav ul li {
            font-size: 1rem;
        }
        nav ul li a {
            text-decoration: none;
            color: #ffffff;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #F8C471;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background: url('hero-image.jpg') no-repeat center center/cover;
        }
        .hero h2 {
            font-size: 3rem;
            color: #ffffff;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
            color: #dcdcdc;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            padding: 50px;
        }
        .product {
            background-color: #1E1E1E;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .product h3 {
            font-size: 1.5rem;
            margin: 15px 0;
            color: #F8C471;
        }
        .product p {
            font-size: 1rem;
            color: #dcdcdc;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1E1E1E;
            color: #dcdcdc;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kvalitetstøy</h1>
        <nav>
            <ul>
                <li><a href="#">Hjem</a></li>
                <li><a href="#">Produkter</a></li>
                <li><a href="#">Om Oss</a></li>
                <li><a href="#">Kontakt</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>Eksklusivt Tøy for den Moderne</h2>
        <p>Utforsk vår kolleksjon laget med de fineste materialene og eksepsjonelt håndverk.</p>
    </section>
    <section class="products">
        <div class="product">
            <img src="product1.jpg" alt="Produkt 1">
            <h3>Elegant Ullgenser</h3>
            <p>Laget av 100% merinoull, perfekt for alle anledninger.</p>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Produkt 2">
            <h3>Komfortabel Skjorte</h3>
            <p>Bomullsskjorte med fokus på detaljer og passform.</p>
        </div>
        <div class="product">
            <img src="product3.jpg" alt="Produkt 3">
            <h3>Eksklusiv Frakk</h3>
            <p>En frakk som kombinerer stil og funksjonalitet.</p>
        </div>
    </section>
    <footer>
        &copy; 2024 Kvalitetstøy. Alle rettigheter reservert.
    </footer>
</body>
</html>
