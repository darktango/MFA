/* Cyber Background Animation */
.background {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: url('https://yourimagehost.com/your-cyber-theme-image.jpg'), linear-gradient(to right, #0a192f, #172a45);
    background-repeat: no-repeat;
    background-size: cover;
    animation: gradientBackground 10s ease infinite;
    z-index: -1;
}

@keyframes gradientBackground {
    0% {background-position: 0% 50%;}
    50% {background-position: 100% 50%;}
    100% {background-position: 0% 50%;}
}

/* Navigation Menu */
nav {
    background-color: #111;
    padding: 15px;
    text-align: center;
}

.nav-menu {
    list-style: none;
    padding: 0;
    margin: 0;
}

.nav-menu li {
    display: inline;
    margin: 0 15px;
}

.nav-menu a {
    color: #00b894;
    text-decoration: none;
    font-size: 1.2em;
    transition: color 0.3s;
}

.nav-menu a:hover {
    color: #e76f51;
}

/* Header Styling */
header {
    background-color: #111;
    color: #fff;
    padding: 20px;
    text-align: center;
    opacity: 0;
    animation: fadeIn 2s forwards;
}

@keyframes fadeIn {
    0% { opacity: 0; }
    100% { opacity: 1; }
}

h1, h2 {
    color: #00b894;
    text-shadow: 0px 0px 10px rgba(0, 255, 255, 0.8);
}

/* Menu Structure */
<nav>
    <ul class="nav-menu">
        <li><a href="#mfa">Multi-Factor Authentication</a></li>
        <li><a href="#healthcare">Healthcare Cybersecurity</a></li>
        <li><a href="#phishing">Phishing & Onsite Threats</a></li>
        <li><a href="#resources">Cybersecurity Resources</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

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
