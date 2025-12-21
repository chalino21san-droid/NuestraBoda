<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Nos Casamos! - Juana & Juan</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .invitation {
            width: 90%; /* Ancho relativo al contenedor padre */
            max-width: 600px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            padding: 20px; /* Reducir el padding */
            text-align: center;
            position: relative;
        }
        .floral-top {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: auto;
            background-image: url('URL_DE_LA_IMAGEN_DE_FLORES_SUPERIOR.jpg');
            background-size: cover;
            background-position: top;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
            overflow: hidden;
            height: 120px; /* Reducir la altura */
        }
        h1 {
            font-family: 'Brush Script MT', cursive;
            font-size: 2.5em; /* Reducir el tamaño */
            color: #333;
            margin-bottom: 5px;
        }
        h2 {
            font-size: 1.2em; /* Reducir el tamaño */
            color: #555;
            margin-top: 0;
            font-style: italic;
        }
        p {
            font-size: 1em; /* Reducir el tamaño */
            line-height: 1.4; /* Reducir el espaciado */
            margin-bottom: 15px; /* Reducir el margen */
        }
        .details {
            display: flex;
            flex-direction: column; /* Apilar los detalles en pantallas pequeñas */
            align-items: center; /* Centrar los detalles */
            margin-top: 20px; /* Reducir el margen */
        }
        .detail {
            text-align: center;
            margin-bottom: 15px; /* Espacio entre los detalles */
        }
        .detail h3 {
            font-size: 1.1em; /* Reducir el tamaño */
            color: #555;
            margin-bottom: 5px;
        }
        .detail p {
            font-size: 0.9em; /* Reducir el tamaño */
            margin-bottom: 0;
        }
        .separator {
            border-left: none; /* Eliminar la línea vertical */
            border-top: 1px solid #bbb; /* Añadir una línea horizontal */
            margin: 10px 0; /* Reducir el margen */
            height: auto; /* Ajustar la altura automáticamente */
            width: 80%; /* Ancho relativo */
        }
        .confirm {
            margin-top: 30px; /* Reducir el margen */
            font-size: 0.8em; /* Reducir el tamaño */
            color: #777;
        }
        .map-button {
            display: inline-block;
            padding: 8px 16px; /* Reducir el padding */
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px; /* Reducir el margen */
            font-size: 0.9em; /* Reducir el tamaño */
        }

        /* Media Query para pantallas más pequeñas (móviles) */
        @media screen and (max-width: 600px) {
            .invitation {
                padding: 15px; /* Reducir el padding */
            }
            .floral-top {
                height: 80px; /* Reducir la altura */
            }
            h1 {
                font-size: 2em; /* Reducir el tamaño */
            }
            h2 {
                font-size: 1em; /* Reducir el tamaño */
            }
            p {
                font-size: 0.9em; /* Reducir el tamaño */
            }
            .detail h3 {
                font-size: 1em; /* Reducir el tamaño */
            }
            .detail p {
                font-size: 0.8em; /* Reducir el tamaño */
            }
        }
    </style>
</head>
<body>
    <div class="invitation">
        <div class="floral-top"></div>
        <h1>¡Nos Casamos!</h1>
        <h2>Juana y Juan</h2>
        <p>Queremos compartir contigo la felicidad de nuestra unión.</p>
        <div class="details">
            <div class="detail">
                <h3>Día</h3>
                <p>6 de Mayo</p>
            </div>
            <div class="separator"></div>
            <div class="detail">
                <h3>Lugar</h3>
                <p>Cabecera Indígenas/Villa de allende, Arriba del parque con la familia sanchez</p>
            </div>
            <div class="separator"></div>
            <div class="detail">
                <h3>Hora</h3>
                <p>4:00 P.M.</p>
            </div>
        </div>
        <a href="https://www.google.com/maps/place/Cabecera+Indigenas,+Villa+de+Allende,+Mexico" class="map-button" target="_blank">Ver en Google Maps</a>
        <p>Lluvia de sobres</p>
        <p class="confirm">CONFIRMAR ASISTENCIA:</p>
    </div>
</body>
</html>
