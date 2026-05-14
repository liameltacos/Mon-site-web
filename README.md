<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon App</title>
    <style>
        body { font-family: sans-serif; background-color: #f0f0f7; display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; margin: 0; }
        .card { background: white; padding: 30px; border-radius: 20px; box-shadow: 0 10px 20px rgba(0,0,0,0.1); text-align: center; width: 80%; }
        button { background-color: #007AFF; color: white; border: none; padding: 15px 30px; border-radius: 10px; font-size: 18px; cursor: pointer; }
        button:active { background-color: #0051a8; }
    </style>
</head>
<body>
    <div class="card">
        <h1>Salut ! 🚀</h1>
        <p>C'est ma première application codée sur iPad.</p>
        <button onclick="saluer()">Clique ici</button>
    </div>

    <script>
        function saluer() {
            alert("Bravo, tu viens de coder ton premier script !");
        }
    </script>
</body>
</html>

