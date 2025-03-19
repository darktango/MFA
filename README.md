<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Awareness</title>
    <style>
        /* Cyber Background Animation */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            overflow-x: hidden;
        }

        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: black;
            z-index: -2;
        }

        /* Matrix Falling Code Effect */
        .matrix-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        /* Cyber-Themed Grid Overlay */
        .grid-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            background: url('https://www.transparenttextures.com/patterns/grid.png');
            opacity: 0.1;
            z-index: -1;
        }

        /* Header Styling */
        header {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            animation: fadeIn 2s forwards;
        }

        /* Fade-In Animation */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        h1, h2 {
            color: #00ff99;
            text-shadow: 0px 0px 10px rgba(0, 255, 255, 0.8);
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
        }

        /* Menu Button */
        .menu-button {
            position: fixed;
            top: 20px;
            left: 20px;
            background: #00b894;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }

        .dropdown-menu {
            display: none;
            position: absolute;
            top: 50px;
            left: 20px;
            background: rgba(0, 0, 0, 0.9);
            border-radius: 5px;
            overflow: hidden;
            width: 200px;
        }

        .dropdown-menu a {
            display: block;
            padding: 10px;
            color: white;
            text-decoration: none;
        }

        .dropdown-menu a:hover {
            background: #00ff99;
        }
    </style>
</head>
<body>
    <div class="background"></div>
    <canvas class="matrix-canvas"></canvas>
    <div class="grid-overlay"></div>

    <button class="menu-button" onclick="toggleMenu()">☰ Menu</button>
    <div class="dropdown-menu" id="menu">
        <a href="#">Home</a>
        <a href="#">Cybersecurity</a>
        <a href="#">Fake CAPTCHA</a>
        <a href="#">Resources</a>
    </div>

    <header>
        <h1>Cybersecurity Awareness: MFA & Healthcare</h1>
        <p>Your Guide to Protecting Data & Using MFA</p>
    </header>

    <section>
        <h2>Why Use Multi-Factor Authentication (MFA)</h2>
        <p>MFA adds an additional layer of security by requiring verification using two or more factors: something you know (password), something you have (phone), or something you are (fingerprint).</p>
    </section>

    <script>
        function toggleMenu() {
            var menu = document.getElementById("menu");
            menu.style.display = menu.style.display === "block" ? "none" : "block";
        }

        /* Matrix Falling Code Effect */
        const canvas = document.querySelector('.matrix-canvas');
        const ctx = canvas.getContext('2d');

        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        const letters = "ABCDEFGHIJKLMNOPQRSTUVWXYZ123456789@#$%^&*()*&^%".split("");
        const fontSize = 14;
        const columns = canvas.width / fontSize;
        const drops = [];

        for (let i = 0; i < columns; i++) {
            drops[i] = Math.floor(Math.random() * canvas.height / fontSize);
        }

        function drawMatrix() {
            ctx.fillStyle = 'rgba(0, 0, 0, 0.05)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            ctx.fillStyle = '#00ff99';
            ctx.font = fontSize + 'px monospace';

            for (let i = 0; i < drops.length; i++) {
                const text = letters[Math.floor(Math.random() * letters.length)];
                ctx.fillText(text, i * fontSize, drops[i] * fontSize);

                if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                drops[i]++;
            }
        }
        setInterval(drawMatrix, 50);
    </script>
</body>
</html>

