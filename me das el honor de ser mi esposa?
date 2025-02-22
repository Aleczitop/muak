<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Jade, ¿Quieres casarte conmigo?</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }
        h1 {
            font-size: 2.5em;
            color: white;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 1.5em;
            color: white;
            animation: fadeIn 3s ease-in-out;
        }
        .buttons {
            margin-top: 20px;
            position: relative;
        }
        button {
            font-size: 1.2em;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
            transition: all 0.3s ease-in-out;
        }
        #yes {
            background-color: #4CAF50;
            color: white;
        }
        #no {
            background-color: #ff4d4d;
            color: white;
            position: absolute;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes heartBeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .heart {
            color: red;
            font-size: 3em;
            animation: heartBeat 1s infinite;
        }
    </style>
</head>
<body>

    <h1>💖 Mi preciosa Jade 💖</h1>
    <p>Eres la persona más hermosa y especial para mí. No hay un solo día en el que no agradezca tenerte en mi vida. Quiero compartir mi presente y futuro contigo.</p>
    <p>¿Quieres casarte conmigo? 🥰</p>
    
    <div class="buttons">
        <button id="yes" onclick="acceptProposal()">¡Sí, mi amor! 💍</button>
        <button id="no" onmouseover="moveNoButton()">No 😳</button>
    </div>

    <script>
        function acceptProposal() {
            document.body.innerHTML = '<h1>🎉 ¡Sabía que dirías que sí! 🎉</h1>' +
                                      '<p>Te amo, Jade 💖</p>' +
                                      '<p>Seremos felices para siempre 💍</p>' +
                                      '<div class="heart">❤️</div>';
        }

        function moveNoButton() {
            let btn = document.getElementById("no");
            let x = Math.random() * (window.innerWidth - 100);
            let y = Math.random() * (window.innerHeight - 50);
            btn.style.left = `${x}px`;
            btn.style.top = `${y}px`;
        }
    </script>

</body>
</html>
