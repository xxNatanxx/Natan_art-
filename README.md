<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio Artístico - Natan_art</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1e90ff;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header p {
            margin: 5px 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #4682b4;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .section-title {
            border-bottom: 2px solid #1e90ff;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            height: auto;
            border: 2px solid #1e90ff;
        }
        footer {
            background-color: #1e90ff;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Portafolio Artístico - Natan_art</h1>
        <p>Estudio de Diseño ubicado en Peñalolen, Chile desde 2017.</p>
    </header>
    <nav>
        <a href="#dibujos">Dibujos</a>
        <a href="#animaciones2d">Animaciones 2D</a>
        <a href="#animaciones3d">Animaciones 3D</a>
        <a href="#pinturas">Pinturas</a>
        <a href="#ilustraciones">Ilustraciones</a>
        <a href="#imagenesdigitales">Imágenes Digitales</a>
    </nav>
    <div class="container">
        <section id="dibujos">
            <h2 class="section-title">Dibujos</h2>
            <div class="gallery">
                <!-- Inserta tus imágenes de dibujos aquí -->
                <img src="ruta/a/tu/imagen1.jpg" alt="Dibujo 1">
                <img src="ruta/a/tu/imagen2.jpg" alt="Dibujo 2">
                <!-- Agrega más imágenes según sea necesario -->
            </div>
        </section>
        <section id="animaciones2d">
            <h2 class="section-title">Animaciones 2D</h2>
            <div class="gallery">
                <!-- Inserta tus imágenes de animaciones 2D aquí -->
                <img src="ruta/a/tu/imagen3.jpg" alt="Animación 2D 1">
                <img src="ruta/a/tu/imagen4.jpg" alt="Animación 2D 2">
                <!-- Agrega más imágenes según sea necesario -->
            </div>
        </section>
        <section id="animaciones3d">
            <h2 class="section-title">Animaciones 3D</h2>
            <div class="gallery">
                <!-- Inserta tus imágenes de animaciones 3D aquí -->
                <img src="ruta/a/tu/imagen5.jpg" alt="Animación 3D 1">
                <img src="ruta/a/tu/imagen6.jpg" alt="Animación 3D 2">
                <!-- Agrega más imágenes según sea necesario -->
            </div>
        </section>
        <section id="pinturas">
            <h2 class="section-title">Pinturas</h2>
            <div class="gallery">
                <!-- Inserta tus imágenes de pinturas aquí -->
                <img src="ruta/a/tu/imagen7.jpg" alt="Pintura 1">
                <img src="ruta/a/tu/imagen8.jpg" alt="Pintura 2">
                <!-- Agrega más imágenes según sea necesario -->
            </div>
        </section>
        <section id="ilustraciones">
            <h2 class="section-title">Ilustraciones</h2>
            <div class="gallery">
                <!-- Inserta tus imágenes de ilustraciones aquí -->
                <img src="ruta/a/tu/imagen9.jpg" alt="Ilustración 1">
                <img src="ruta/a/tu/imagen10.jpg" alt="Ilustración 2">
                <!-- Agrega más imágenes según sea necesario -->
            </div>
        </section>
        <section id="imagenesdigitales">
            <h2 class="section-title">Imágenes Digitales</h2>
            <div class="gallery">
                <!-- Inserta tus imágenes de imágenes digitales aquí -->
                <img src="ruta/a/tu/imagen11.jpg" alt="Imagen Digital 1">
                <img src="ruta/a/tu/imagen12.jpg" alt="Imagen Digital 2">
                <!-- Agrega más imágenes según sea necesario -->
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Mi Portafolio Artístico - Natan_art. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
