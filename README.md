<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flores Amarillas para Ti</title>
    <style>
        body {
            background-color: #f9f9f9;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .flower {
            width: 150px;
            cursor: pointer;
        }
        .hidden-message {
            display: none;
            font-size: 1.5em;
            color: #ffb703;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Un Ramo de Flores Amarillas 🌼</h1>
    <img src="flores-amarillas.png" alt="Flores Amarillas" class="flower" onclick="showMessage()">
    <p class="hidden-message">¡Que estas flores te llenen de alegría y luz como el sol! 😊</p>

    <script>
        function showMessage() {
            document.querySelector('.hidden-message').style.display = 'block';
        }
    </script>
</body>
</html>
