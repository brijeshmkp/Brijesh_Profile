# Brijesh_ Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brijesh Kumar Patel - Portfolio</title>
  <style>
    :root {
      --bg: #f9fafb;
      --text: #111;
      --accent: #004080;
      --dark-bg: #111;
      --dark-text: #f0f0f0;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: var(--bg);
      color: var(--text);
      scroll-behavior: smooth;
      transition: background 0.3s, color 0.3s;
    }
    body.dark {
      background: var(--dark-bg);
      color: var(--dark-text);
    }
    header {
      background: var(--accent);
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      text-align: center;
      margin-top: 10px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: var(--accent);
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: var(--accent);
      margin-bottom: 10px;
    }
    ul {
      padding-left: 20px;
    }
    .btn {
      padding: 10px 20px;
      background: var(--accent);
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .btn:hover {
      opacity: 0.9;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: var(--accent);
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>Brijesh Kumar Patel</h1>
    <p>Email Marketing & Deliverability Specialist</p>
    <button class="btn" onclick="window.print()">📄 Download Resume</button>
    <button class="btn" onclick="toggleDark()">🌓 Dark Mode</button>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>I am an experienced email marketing professional with over 3.3+ years of expertise in managing and optimizing email campaigns across various industries. Skilled in DNS setup, domain warmup, and deliverability tools like SendGrid, Instantly, and Mailshake. Passionate about crafting email systems that scale and convert.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Single & Bulk Email Verification System</li>
      <li>Blacklist Monitoring Dashboard</li>
      <li>Email Syntax Validator & Duplicate Cleaner</li>
      <li>Real-time Email Validation API</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Email Setup, Deliverability Audit</li>
      <li>SPF, DKIM, DMARC configuration</li>
      <li>Campaign tools: Mailshake, Klenty, Smartlead</li>
      <li>DNS & Domain Reputation Management</li>
      <li>Lead Generation & Outreach Strategy</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:brijeshpatelja1@gmail.com">brijeshpatelja1@gmail.com</a></p>
    <p>Location: Noida, Uttar Pradesh</p>
    <p>Phone: +91 8948624147</p>
  </section>

  <footer>
    &copy; 2025 Brijesh Kumar Patel · All rights reserved.
  </footer>

  <script>
    function toggleDark() {
      document.body.classList.toggle('dark');
    }
  </script>
</body>
</html>

