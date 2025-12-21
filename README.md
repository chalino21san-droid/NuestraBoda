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
            width: 80%;
            max-width: 600px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            padding: 30px;
            text-align: center;
            position: relative;
        }
        .floral-top {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: auto;
            background-image: url('plantilla(1).jfif');
            background-size: cover;
            background-position: top;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
            overflow: hidden;
            height: 150px;
        }
        h1 {
            font-family: 'Brush Script MT', cursive;
            font-size: 3.5em;
            color: #333;
            margin-bottom: 5px;
        }
        h2 {
            font-size: 1.5em;
            color: #555;
            margin-top: 0;
            font-style: italic;
        }
        p {
            font-size: 1.1em;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .details {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
        }
        .detail {
            text-align: center;
        }
        .detail h3 {
            font-size: 1.2em;
            color: #555;
            margin-bottom: 5px;
        }
        .detail p {
            font-size: 1em;
            margin-bottom: 0;
        }
        .separator {
            border-left: 1px solid #bbb;
            margin: 0 20px;
            height: 50px;
        }
        .confirm {
            margin-top: 40px;
            font-size: 0.9em;
            color: #777;
        }
        .map-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
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
                <p>Cabecera Indigenas/Villa de allende,<br>Arriba del parque con la familia sanchez</p>
            </div>
            <div class="separator"></div>
            <div class="detail">
                <h3>Hora</h3>
                <p>4:00 P.M.</p>
            </div>
        </div>
        <a href="https://maps.app.goo.gl/Px3zd2VqAXigspcP8" class="map-button" target="_blank">Ver en Google Maps</a>
        <p>Lluvia de sobres</p>
        <p class="confirm">CONFIRMAR ASISTENCIA:</p>
    </div>
</body>
</html>
