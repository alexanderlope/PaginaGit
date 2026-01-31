<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sitio Personal</title>

    <style>
        /* ====== ESTILOS GENERALES ====== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        /* ====== ENCABEZADO ====== */
        header {
            background-color: #1e3a8a;
            color: white;
            padding: 20px;
            text-align: center;
        }

        /* ====== MENÚ DE NAVEGACIÓN ====== */
        nav {
            background-color: #2563eb;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            flex-wrap: wrap;
        }

        nav ul li {
            margin: 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* ====== CONTENIDO PRINCIPAL ====== */
        .contenedor {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
        }

        .contenido {
            display: flex;
            gap: 20px;
        }

        .texto {
            flex: 2;
        }

        .imagenes {
            flex: 1;
        }

        .imagenes img {
            width: 100%;
            margin-bottom: 10px;
            border-radius: 8px;
        }

        /* ====== PIE DE PÁGINA ====== */
        footer {
            background-color: #1e293b;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        /* ====== RESPONSIVE (CELULARES) ====== */
        @media (max-width: 768px) {
            .contenido {
                flex-direction: column;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>

    <!-- ENCABEZADO -->
    <header>
        <h1>Mi Sitio Web Personal</h1>
        <p>Bienvenido a mi página</p>
    </header>

    <!-- MENÚ -->
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Sobre mí</a></li>
            <li><a href="#">Proyectos</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>

    <!-- CONTENIDO -->
    <div class="contenedor">
        <div class="contenido">
            <div class="texto">
                <h2>Sobre mí</h2>
                <p>
                    Hola, soy un estudiante apasionado por la tecnología y el desarrollo web.
                    Este sitio es un ejemplo de una página web responsiva creada con HTML y CSS.
                </p>
                <p>
                    Aquí puedo mostrar mis proyectos, mis intereses y compartir información personal.
                </p>
            </div>

            <div class="imagenes">
                <img src="https://via.placeholder.com/300" alt="Imagen 1">
                <img src="https://via.placeholder.com/300" alt="Imagen 2">
            </div>
        </div>
    </div>

    <!-- PIE DE PÁGINA -->
    <footer>
        <p>© 2026 - Mi Sitio Personal | Todos los derechos reservados</p>
    </footer>

</body>
</html>
