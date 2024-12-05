<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Concierto Paulo Londra</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Estilos globales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        /* Estilos para el encabezado */
        header {
            background-color: #1e90ff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        /* Estilos para el menú de navegación */
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1rem;
        }

        nav ul li a:hover {
            color: #1e90ff;
        }

        /* Estilos para la sección principal */
        main {
            padding: 20px;
            background-color: white;
            margin: 20px auto;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            border-bottom: 2px solid #1e90ff;
            padding-bottom: 10px;
            margin-bottom: 20px;
            color: #1e90ff;
        }

        p {
            margin-bottom: 20px;
        }

        /* Estilos para las listas */
        ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }

        ul li {
            margin-bottom: 10px;
        }

        /* Estilos para el pie de página */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Concierto de Paulo Londra</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Información del Evento</a></li>
            <li><a href="#">Boletos</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Detalles del Concierto</h2>
            <p><strong>Artista:</strong> Paulo Londra</p>
            <p><strong>Fecha:</strong> Sábado, 28 de septiembre de 2024, 9:00 p.m.</p>
            <p><strong>Lugar:</strong> Pepsi Center WTC, México, DF</p>
        </section>

        <section>
            <h2>Artículo Relacionado</h2>
            <p>Para más información sobre los precios oficiales y detalles del concierto en la CDMX, visita el siguiente artículo:</p>
            <p><a href="https://www.infobae.com/mexico/2024/09/06/paulo-londra-en-la-cdmx-estos-son-los-precios-oficiales-para-el-concierto-en-el-pepsi-center-wtc/" target="_blank">
                Leer artículo en Infobae</a></p>
        </section>

        <section>
            <h2>Multimedia</h2>

            <!-- Video del concierto -->
            <h3>Video video más popular</h3>
            <video controls width="100%">
                <source src="Paulo Londra Adan y Eva.mp4" type="video/mp4">
                Tu navegador no soporta la reproducción de video.
            </video>

            <!-- Audio de la canción -->
            <h3>Cancion más reciente - Recién Soltera</h3>
            <audio controls>
                <source src="Paulo Londra Recién Soltera.mp3" type="audio/mp3">
                Tu navegador no soporta la reproducción de audio.
            </audio>
        </section>
    </main>

    <footer>
        <p>© 2024 Concierto Paulo Londra. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
