<!DOCTYPE html>
<html lang="sr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Balkan Clutch CS2 Server</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
    body {
        margin: 0;
        font-family: 'Roboto', sans-serif;
        background: linear-gradient(135deg, #1e1e1e, #111111);
        color: #fff;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
        text-align: center;
    }

    h1 {
        font-size: 3em;
        color: #ff4500;
        margin-bottom: 10px;
        animation: glow 2s infinite alternate;
    }

    @keyframes glow {
        0% { text-shadow: 0 0 10px #ff4500, 0 0 20px #ff4500; }
        100% { text-shadow: 0 0 20px #ff6347, 0 0 30px #ff6347; }
    }

    .container {
        background-color: rgba(30,30,30,0.85);
        padding: 40px 60px;
        border-radius: 15px;
        box-shadow: 0 0 20px #ff4500;
        animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(-20px); }
        to { opacity: 1; transform: translateY(0); }
    }

    .btn {
        display: inline-block;
        margin: 15px;
        padding: 15px 30px;
        font-size: 1.2em;
        font-weight: bold;
        color: #fff;
        background: #ff4500;
        border: none;
        border-radius: 10px;
        cursor: pointer;
        transition: all 0.3s ease;
        text-decoration: none;
    }

    .btn:hover {
        background: #ff6347;
        transform: scale(1.1);
    }

    p {
        font-size: 1.2em;
        margin: 10px 0;
    }

    a {
        color: #1e90ff;
        text-decoration: none;
        font-weight: bold;
    }

    a:hover {
        text-decoration: underline;
    }

    .footer {
        position: absolute;
        bottom: 20px;
        font-size: 0.9em;
        color: #888;
    }
</style>
</head>
<body>
    <h1>Balkan Clutch CS2</h1>
    <div class="container">
        <p>🎮 IP Servera: <a href="steam://connect/212.100.172.160:29376">212.100.172.160:29376</a></p>
        <p>💬 Discord: <a href="https://discord.gg/ZM2u4xqN" target="_blank">Pridruži se našem Discordu</a></p>
        <a class="btn" href="steam://connect/212.100.172.160:29376">Poveži se odmah</a>
        <a class="btn" href="https://discord.gg/ZM2u4xqN" target="_blank">Idi na Discord</a>
    </div>
    <div class="footer">© 2026 Balkan Clutch CS2 Server</div>
</body>
</html>
