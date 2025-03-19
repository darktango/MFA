<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Awareness</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        body {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            overflow: hidden;
        }

        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, #1e3c72 30%, #2a5298 100%);
            z-index: -1;
            animation: cyberAnimation 10s infinite alternate ease-in-out;
        }

        @keyframes cyberAnimation {
            0% {
                filter: hue-rotate(0deg);
                transform: scale(1);
            }
            100% {
                filter: hue-rotate(360deg);
                transform: scale(1.05);
            }
        }

        nav {
            background: rgba(0, 0, 0, 0.7);
            padding: 10px 0;
        }

        .nav-menu {
            list-style: none;
            padding: 0;
        }

        .nav-menu li {
            display: inline;
            margin: 0 15px;
        }

        .nav-menu a {
            color: #00b894;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
        }

        footer {
            background: rgba(0, 0, 0, 0.7);
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Cyber Background Animation -->
    <div class="background"></div>

    <!-- Navigation Menu -->
    <nav>
        <ul class="nav-menu">
            <li><a href="#mfa">Multi-Factor Authentication</a></li>
            <li><a href="#healthcare">Healthcare Cybersecurity</a></li>
            <li><a href="#phishing">Phishing & Onsite Threats</a></li>
            <li><a href="#resources">Cybersecurity Resources</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Content Sections -->
    <section id="mfa">
        <h2>Why Use Multi-Factor Authentication (MFA)</h2>
        <p>Multi-Factor Authentication (MFA) adds an additional layer of security...</p>
    </section>

    <section id="healthcare">
        <h2>Cyber Attacks in Healthcare: Protecting Valuable Data</h2>
        <p>Healthcare data is some of the most valuable information in the world...</p>
    </section>

    <section id="phishing">
        <h2>Common Cyber Attacks: Phishing & Onsite Threats</h2>
        <p>Cybercriminals employ various tactics to gain unauthorized access...</p>
    </section>

    <section id="resources">
        <h2>Helpful Resources to Further Understand Cybersecurity</h2>
        <ul>
            <li><a href="https://www.osinttechniques.com/" target="_blank">OSINT Techniques</a></li>
            <li><a href="https://www.cisecurity.org/cybersecurity-best-practices/" target="_blank">Cybersecurity Best Practices</a></li>
            <li><a href="https://brainstation.io/career-guides/what-tools-do-cybersecurity-analysts-use" target="_blank">Cybersecurity Skills Tools</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Get In Touch</h2>
        <p>If you would like to know more about protecting your personal or organization’s data...</p>
        <a href="mailto:contact@yourwebsite.com" class="cta-button">Contact Us</a>
    </section>

    <footer>
        <p>&copy; 2025 Your Website. All Rights Reserved.</p>
    </footer>
</body>
</html>

