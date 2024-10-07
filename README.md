# GitRenat
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Queres ir a las carrozas conmigo, como el año pasado?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
        }
        #resultado {
            margin-top: 20px;
            font-size: 24px;
        }
        .celebracion {
            color: green;
        }
        .triste {
            color: blue;
        }
    </style>
</head>
<body>
    <h1>¿Queres ir a las carrozas conmigo, como el año pasado?</h1>
    <button onclick="mostrarCelebracion()">Sí</button>
    <button onclick="mostrarTriste()">No</button>

    <div id="resultado"></div>

    <script>
        function mostrarCelebracion() {
            document.getElementById('resultado').innerHTML = "🎉 ¡Siuu! ¡Te compro un algodón de azúcar! 🎉";
            document.getElementById('resultado').className = 'celebracion';
        }

        function mostrarTriste() {
            document.getElementById('resultado').innerHTML = "😢 perfecto, sos peronista";
            document.getElementById('resultado').className = 'triste';
        }
    </script>
</body>
</html>
