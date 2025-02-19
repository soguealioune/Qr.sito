# Qr.sito
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Il Mio Sito Futuristico</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Benvenuto nel Futuro</h1>
        <p>Scansiona il QR code per un'esperienza immersiva</p>
        <button onclick="showMessage()">Scopri di più</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    background-color: #0a0a0a;
    color: #00ffcc;
    font-family: 'Arial', sans-serif;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    border: 2px solid #00ffcc;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 15px #00ffcc;
}

h1 {
    text-shadow: 0 0 10px #00ffcc;
}

button {
    background-color: black;
    color: #00ffcc;
    border: 1px solid #00ffcc;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #00ffcc;
    color: black;
}
function showMessage() {
    alert("Prossimamente nuove funzionalità!");
}


