
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Awareness: MFA & Healthcare</title>
    <style>
        body {                                    
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            background: #000;
            overflow-y: scroll; /* Allow scrolling */
        }

        /* Cyber Background Animation */
        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to right, #00b894, #2d3436);
            background-size: 400% 400%;
            animation: gradientBackground 10s ease infinite;
            z-index: -1;
        }

        @keyframes gradientBackground {
            0% {background-position: 0% 50%;}
            50% {background-position: 100% 50%;}
            100% {background-position: 0% 50%;}
        }

        /* Grid Overlay for Cyber Theme */
        .grid-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            background: url('https://www.transparenttextures.com/patterns/grid.png');
            opacity: 0.2;
            z-index: -2;
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

        /* Fade-In Animation */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        h1, h2 {
            color: #00b894;
            text-shadow: 0px 0px 10px rgba(0, 255, 255, 0.8);
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
            animation: slideIn 1.5s ease-out;
        }

        /* Slide-In Animation */
        @keyframes slideIn {
            0% { transform: translateY(50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        p {
            line-height: 1.6;
            font-size: 1.1em;
        }

        a {
            color: #2a9d8f;
            text-decoration: none;
            transition: color 0.3s ease-in-out;
        }

        a:hover {
            color: #00b894;
            text-decoration: underline;
        }

        .cta-button {
            display: inline-block;
            background-color: #e76f51;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.1em;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        .cta-button:hover {
            background-color: #00b894;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #111;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

    </style>
</head>
<body>
    <!-- Background Animation -->
    <div class="background"></div>
    <!-- Grid Overlay -->
    <div class="grid-overlay"></div>

    <!-- Header Section -->
    <header>
        <h1>Cybersecurity Awareness: MFA & Healthcare</h1>
        <p>Your Guide to Protecting Data & Using MFA</p>
        <p>By: Travis DeWitt</p>
    </header>

    <!-- MFA Section -->
    <section>
        <h2>Why Use Multi-Factor Authentication (MFA)</h2>
        <p>Multi-Factor Authentication (MFA) adds an additional layer of security to your online accounts. It requires you to verify your identity using two or more factors: something you know (like a password), something you have (like a phone), or something you are (like a fingerprint).</p>
        
        <p>Why is MFA so important? Cybercriminals are constantly trying to breach online accounts. Adding MFA means that even if your password is compromised, hackers would still need another piece of information to access your account, making it much harder for them to succeed.</p>

        <p>Examples of MFA include using SMS verification, authenticator apps like Google Authenticator, or even biometric factors like your fingerprint.</p>
        
        <a href="https://its.uky.edu/news/why-you-should-be-using-multifactor-authentication-all-your-online-accounts" class="cta-button" target="_blank">Learn more about MFA</a>
    </section>

    <!-- Healthcare Cybersecurity Section -->
    <section>
        <h2>Cyber Attacks in Healthcare: Protecting Valuable Data</h2>
        <p>Healthcare data is some of the most valuable information in the world, and cybercriminals know this. Hospitals, clinics, and other healthcare facilities house sensitive patient records, financial data, and other personal information that is a prime target for cyber attacks.</p>

        <p>In recent years, healthcare facilities have faced a surge in cyber attacks, including ransomware attacks, which can shut down entire hospital networks, compromising patient care. If patient data is compromised, it can have severe consequences, both for patients and the reputation of the healthcare provider.</p>

        <p>That’s why it's crucial for healthcare organizations to adopt cybersecurity best practices, including the implementation of MFA, to safeguard this sensitive information.</p>

        <a href="https://www.aha.org/center/cybersecurity-and-risk-advisory-services/ransomware-attacks-hospitals-have-changed" class="cta-button" target="_blank">Read more about ransomware attacks on healthcare</a>
    </section>

<!-- phising attacks 
    <!-- Cyber Attacks & Phishing Section -->
    <section>
        <h2>Common Cyber Attacks: Phishing & Onsite Threats</h2>
        <p>Cybercriminals employ various tactics to gain unauthorized access to systems, steal personal information, or infect networks. Among the most common methods are <strong>phishing attacks</strong> and <strong>onsite attacks</strong>. Let’s break down some of the key techniques hackers use to exploit these vulnerabilities.</p>
        
        <h3>1. Phishing Attacks</h3>
        <p>Phishing attacks involve hackers impersonating legitimate organizations to trick victims into revealing sensitive information, such as passwords, credit card details, or login credentials. These attacks typically happen through email, social media, or fake websites.</p>
        
        <h4>Types of Phishing:</h4>
        <ul>
            <li><strong>Email Phishing:</strong> The most common form, where attackers send emails that appear to be from trusted sources (e.g., banks, online services). These emails often contain malicious links or attachments.</li>
            <li><strong>Spear Phishing:</strong> A more targeted version of phishing, where the attacker customizes their message to a specific individual or organization. These emails are highly personalized and appear even more convincing.</li>
            <li><strong>Vishing (Voice Phishing):</strong> Hackers use phone calls to impersonate legitimate organizations, like tech support or financial institutions, and ask for personal information. This can also happen through text messages (Smishing).</li>
            <li><strong>Whaling:</strong> A type of spear phishing targeting high-level executives or influential individuals, often involving highly customized attacks to steal sensitive corporate information.</li>
            <li><strong>Clone Phishing:</strong> The attacker creates a replica of a legitimate email previously sent by a trusted entity, replacing a link or attachment with a malicious one, tricking the recipient into clicking.</li>
        </ul>

        <h3>2. Onsite Attacks</h3>
        <p>In addition to online phishing, onsite attacks refer to incidents where hackers exploit vulnerabilities in physical locations or directly interact with the victim to gain unauthorized access. These attacks include:</p>
        <ul>
            <li><strong>USB Drops:</strong> Hackers leave infected USB drives in public places, hoping that someone will plug them into a computer, thereby introducing malware into the system.</li>
            <li><strong>Social Engineering:</strong> Attackers manipulate people into divulging confidential information or bypassing security protocols. This could involve impersonating a colleague or service provider.</li>
            <li><strong>Shoulder Surfing:</strong> Hackers observe individuals in public spaces, like cafes or airports, to gather sensitive data by watching them enter passwords or PINs on their devices.</li>
            <li><strong>Physical Access Attacks:</strong> Attackers may attempt to gain physical access to an organization's premises, steal laptops, or tamper with security systems in order to extract sensitive information.</li>
        </ul>

        <h3>How to Protect Yourself from Phishing & Onsite Attacks:</h3>
        <ul>
            <li><strong>Verify Emails:</strong> Always check the sender’s email address before clicking on links or opening attachments. If in doubt, contact the organization directly through their official channels.</li>
            <li><strong>Be Cautious of Unsolicited Requests:</strong> Whether it’s via email, phone, or in person, always question unsolicited requests for sensitive information.</li>
            <li><strong>Use Multi-Factor Authentication (MFA):</strong> Implement MFA to add an extra layer of protection to your online accounts in case your password is compromised.</li>
            <li><strong>Secure Physical Devices:</strong> Lock your computer and mobile devices when not in use, and avoid leaving them unattended in public spaces.</li>
            <li><strong>Keep Software Updated:</strong> Regularly update your operating system, browsers, and security software to ensure they are equipped to defend against the latest threats.</li>
        </ul>
        
        <a href="https://www.occ.gov/topics/consumers-and-communities/consumer-protection/fraud-resources/phishing-attack-prevention.html" class="cta-button" target="_blank">Learn more about Phishing Prevention</a>
    </section>

    <!-- Additional Resources Section -->
    <section>
        <h2>Helpful Resources to Further Understand OSINT, Cybersecurity, and MFA</h2>
        <p>Here are some great resources that you can explore to dive deeper into the world of Open Source Intelligence (OSINT), Cybersecurity, and the role of Multi-Factor Authentication (MFA) in protecting your data.</p>

        <ul>
            <li><a href="https://www.osinttechniques.com/" target="_blank">OSINT Techniques</a></li>
            <li><a href="https://www.cisecurity.org/cybersecurity-best-practices/" target="_blank">Cybersecurity Best Practices</a></li>
            <li><a href="https://www.sans.org/cyber-security-skills/" target="_blank">Cybersecurity Skills Tools</a></li>
        </ul>
    </section>

    <!-- Contact Form Section -->
    <section>
        <h2>Get In Touch</h2>
        <p>If you would like to know more about protecting your personal or organization’s data, feel free to reach out for more information or consultation on OSINT, MFA, and overall cybersecurity.</p>

        <a href="mailto:contact@yourwebsite.com" class="cta-button">Contact Us</a>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Your Website. All Rights Reserved.</p>
    </footer>
</body>
</html>
