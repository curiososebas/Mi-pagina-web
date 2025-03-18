<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Artify - Cuadros de Spotify</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        .slogan {
            font-size: 1.5em;
            margin: 20px 0;
            color: #333;
        }
        .product-gallery {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .product-card {
            width: 250px;
            background-color: white;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }
        .product-card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .product-card h3 {
            margin: 15px 0;
            font-size: 1.2em;
        }
        .btn {
            background-color: #ff4d4d;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1em;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #ff3333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Artify</h1>
    <p>El arte de la música en cada cuadro</p>
</header>

<section>
    <h2>Bienvenido a Artify</h2>
    <p class="slogan">Convierte tu música favorita en arte visual. Cuadros acrílicos personalizados con tus canciones de Spotify.</p>
    
    <div class="product-gallery">
        <!-- Product 1 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/250" alt="Cuadro Spotify 1">
            <h3>Cuadro Acrílico 1</h3>
            <p>Personalizado con tu canción favorita.</p>
            <a href="#" class="btn">Comprar ahora</a>
        </div>
        <!-- Product 2 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/250" alt="Cuadro Spotify 2">
            <h3>Cuadro Acrílico 2</h3>
            <p>El regalo perfecto para los amantes de la música.</p>
            <a href="#" class="btn">Comprar ahora</a>
        </div>
        <!-- Product 3 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/250" alt="Cuadro Spotify 3">
            <h3>Cuadro Acrílico 3</h3>
            <p>Da vida a tus canciones favoritas en una obra de arte.</p>
            <a href="#" class="btn">Comprar ahora</a>
        </div>
    </div>
</section>

<footer>
    <p>© 2025 Artify. Todos los derechos reservados.</p>
    <p>Creado por: D. Morales, J. Sanaría y S. Barragán</p>
</footer>

</body>
</html>
