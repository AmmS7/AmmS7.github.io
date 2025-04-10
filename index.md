---
layout: default
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Cybersecurity Portfolio">
    <title>Your Name - Cybersecurity Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            padding: 30px;
            margin: 20px;
        }
        h2 {
            color: #333;
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .project {
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 48%;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        .project h3 {
            color: #007BFF;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        .contact-info {
            margin-top: 20px;
            font-size: 1.2em;
        }
        .skills ul {
            list-style-type: none;
            padding-left: 0;
        }
        .skills li {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Your Name</h1>
        <p>Cybersecurity Enthusiast | Penetration Tester | Security Analyst</p>
    </header>

    <!-- Introduction Section -->
    <section id="intro">
        <h2>About Me</h2>
        <p>Hello! I'm [Your Name], a passionate cybersecurity professional dedicated to learning and solving real-world security challenges. My journey in cybersecurity started with a curiosity to understand how systems can be exploited and how to defend them effectively. This portfolio showcases the projects, skills, and knowledge I’ve gained throughout my journey.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <h2>Core Skills</h2>
        <ul>
            <li><strong>Penetration Testing:</strong> Vulnerability assessments, exploitation, and ethical hacking techniques.</li>
            <li><strong>Networking:</strong> Strong understanding of TCP/IP, DNS, firewalls, and VPNs.</li>
            <li><strong>Incident Response:</strong> Experience with identifying, responding to, and mitigating security breaches.</li>
            <li><strong>Scripting & Automation:</strong> Writing scripts to automate security tasks using Python and Bash.</li>
            <li><strong>Web Application Security:</strong> Understanding common vulnerabilities like SQL injection, XSS, and CSRF.</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Penetration Testing - [Project Name]</h3>
                <p>This project involved conducting a penetration test on a vulnerable virtual machine, finding and exploiting vulnerabilities using tools like Metasploit, Burp Suite, and Nmap. I documented the entire process and presented a detailed report on the findings.</p>
                <a href="#">View Project</a>
            </div>
            <div class="project">
                <h3>Security Automation Script</h3>
                <p>Developed a Python script to automate the scanning of open ports on a network. This script helps security teams identify potential vulnerabilities more efficiently.</p>
                <a href="#">View Project</a>
            </div>
            <div class="project">
                <h3>CTF Challenge - [Challenge Name]</h3>
                <p>Participated in a CTF challenge where I was tasked with exploiting a web server vulnerability. I was able to escalate privileges and gain root access, demonstrating my skills in web application security.</p>
                <a href="#">View Challenge</a>
            </div>
            <div class="project">
                <h3>Incident Response Plan</h3>
                <p>Created a detailed incident response plan for a simulated data breach. The plan includes step-by-step procedures for identifying the breach, containing the damage, and recovering from the incident.</p>
                <a href="#">View Plan</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <div class="contact-info">
            <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn Profile</a></p>
            <p>GitHub: <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 [Your Name]. All rights reserved.</p>
    </footer>

</body>
</html>
