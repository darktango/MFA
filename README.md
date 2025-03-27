<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MFA in Healthcare</title>
    <style>
        body {
            background-color: #1a1a1a;
            color: #f0f0f0;
            font-family: 'Courier New', monospace;
            text-align: center;
            margin: 0;
            padding: 0;
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }
        h1, h2 {
            color: #ff9800;
            animation: slideIn 1s ease-out;
        }
        @keyframes slideIn {
            from { transform: translateY(-20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .section {
            background: #333;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(255, 152, 0, 0.3);
            transition: transform 0.3s ease-in-out;
            animation: fadeInUp 1s ease-in-out;
        }
        @keyframes fadeInUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        .section:hover {
            transform: scale(1.05);
        }
        a {
            color: #ff9800;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        .btn {
            background-color: #ff9800;
            color: #1a1a1a;
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 10px;
            transition: background 0.3s ease-in-out;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #e68900;
        }
        .hidden {
            display: none;
        }
    </style>
    <script>
        function toggleLearnMore(id) {
            var content = document.getElementById(id);
            if (content.classList.contains("hidden")) {
                content.classList.remove("hidden");
            } else {
                content.classList.add("hidden");
            }
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>Why MFA is Critical in Healthcare</h1>
        <div class="section">
            <h2>What is Multi-Factor Authentication?</h2>
            <p>Multi-Factor Authentication (MFA) adds an extra layer of security by requiring multiple forms of verification before granting access.</p>
        </div>
        <div class="section">
            <h2>Why is MFA Important in Healthcare?</h2>
            <ul>
                <li>Protects patient data from breaches</li>
                <li>Reduces the risk of phishing attacks</li>
                <li>Ensures compliance with HIPAA and security regulations</li>
                <li>Prevents unauthorized access to medical records</li>
            </ul>
        </div>
        <div class="section">
            <h2>How to Implement MFA in Your Organization</h2>
            <p>Learn how to strengthen security with MFA solutions tailored for healthcare professionals.</p>
            <button class="btn" onclick="toggleLearnMore('learnMoreContent')">Learn More</button>
            <div id="learnMoreContent" class="hidden">
                <h3>Additional Resources:</h3>
                <ul>
                    <li><a href="https://www.cisa.gov/mfa" target="_blank">Why MFA Matters</a></li>
                    <li><a href="https://www.phishing.org/" target="_blank">Recognizing Phishing Emails</a></li>
                    <li><a href="https://www.nist.gov/" target="_blank">NIST Cybersecurity Framework</a></li>
                </ul>
            </div>
        </div>
        <div class="section">
            <h2>Protecting Patient Information</h2>
            <p>It's crucial to protect patient data and avoid sharing sensitive information through email, even within your organization.</p>
            <button class="btn" onclick="toggleLearnMore('patientInfoContent')">Learn More</button>
            <div id="patientInfoContent" class="hidden">
                <h3>Best Practices:</h3>
                <ul>
                    <li>Use secure messaging platforms for internal communication.</li>
                    <li>Encrypt sensitive data before transmission.</li>
                    <li>Avoid including patient details in emails, even internally.</li>
                    <li>Ensure compliance with HIPAA regulations regarding patient data sharing.</li>
                </ul>
            </div>
        </div>
        <div class="section">
            <h2>Protecting Yourself from Scams</h2>
            <p>Cybercriminals often target individuals with phishing and scam attempts. Stay vigilant and protect yourself from fraud.</p>
            <button class="btn" onclick="toggleLearnMore('scamProtectionContent')">Learn More</button>
            <div id="scamProtectionContent" class="hidden">
                <h3>How to Stay Safe:</h3>
                <ul>
                    <li>Verify email senders before clicking on links or downloading attachments.</li>
                    <li>Use strong, unique passwords and enable MFA wherever possible.</li>
                    <li>Be cautious of urgent or unexpected requests for personal information.</li>
                    <li>Report suspicious emails and messages to your IT department or security team.</li>
                </ul>
            </div>
        </div>
        <div class="section">
            <h2>About Me</h2>
            <p>Hi, I'm Travis Dewitt, a cybersecurity professional with a passion for protecting digital assets and educating others on security best practices. I hold a Bachelor's degree in Cybersecurity and a CompTIA Security+ certification. With hands-on experience in ethical hacking, Active Directory, and IT security, I am dedicated to making technology safer. Connect with me to learn more!</p>
        </div>
        <div class="section">
            <h2>Contact</h2>
            <p>Have questions? Connect with me on <a href="https://www.linkedin.com/in/travis-dewitt-03ba492b7/" target="_blank">LinkedIn</a></p>
        </div>
    </div>
</body>
</html>
