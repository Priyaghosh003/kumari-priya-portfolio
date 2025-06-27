# kumari-priya-portfolio
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kumari Priya | Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    :root {
      --bg: #111111;
      --text: #f4f4f4;
      --primary: #ffffff;
      --accent: #1abc9c;
      --card: #1e1e1e;
      --shadow: rgba(0, 0, 0, 0.5);
    }
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    nav {
      background: #000;
      padding: 10px 20px;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: 500;
      padding: 6px 12px;
      border-radius: 5px;
    }
    nav a:hover {
      background: var(--accent);
      color: #000;
    }
    header, section {
      padding: 40px 20px;
      max-width: 960px;
      margin: auto;
    }
    h1, h2, h3 {
      color: var(--primary);
      margin-bottom: 20px;
    }
    .btn {
      display: inline-block;
      background: var(--accent);
      color: #000;
      padding: 10px 20px;
      margin-top: 10px;
      text-decoration: none;
      border-radius: 4px;
      font-weight: 600;
      box-shadow: 0 4px 6px var(--shadow);
    }
    .btn:hover {
      background: #16a085;
    }
    ul {
      padding-left: 20px;
    }
    section ul li {
      background: var(--card);
      margin: 8px 0;
      padding: 10px 15px;
      border-radius: 6px;
      box-shadow: 0 2px 4px var(--shadow);
    }
    .graphics {
      text-align: center;
      margin: 30px 0;
    }
    .graphics img {
      max-width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
    }
    footer {
      background: #000;
      color: #aaa;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#internship">Internship</a>
    <a href="#achievements">Achievements</a>
    <a href="#contact">Contact</a>
  </nav>

  <header id="home">
    <h1>Kumari Priya</h1>
    <p>Detail-oriented and motivated BCA student with experience in Python, robotics simulation, and software development.</p>
    <a class="btn" href="Kumari_Priya_Resume.pdf" download>Download Resume</a>
  </header>

  <section id="education">
    <h2>Education</h2>
    <ul>
      <li><strong>BCA</strong>, Bengaluru North University (2025) - 85%</li>
      <li><strong>12th (Science)</strong>, BSEB (2022) - 79.8%</li>
      <li><strong>10th</strong>, Gyan Bharti Public School, CBSE (2020) - 65.4%</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Technical Skills</h2>
    <ul>
      <li><strong>Languages:</strong> Python, Data Structures and Algorithms, ROS Framework</li>
      <li><strong>Tools:</strong> VS Code, PyCharm, Webots, Jupyter Notebook</li>
      <li><strong>Operating Systems:</strong> Windows, Linux</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <h3>Crime Reporting System</h3>
    <ul>
      <li>Developed a desktop application using Python, Tkinter, and SQLite.</li>
      <li>Features include secure login, evidence upload, real-time dashboard.</li>
      <li>Focused on GUI design and backend database integration.</li>
    </ul>
  </section>

  <section id="internship">
    <h2>Internship - Yspace (Mar 2025 – Jun 2025)</h2>
    <ul>
      <li>Python-Webots configuration and simulation of robotic movements.</li>
      <li>Converted real-world environments into virtual simulations.</li>
      <li>Wrote custom controller scripts and automated simulation testing.</li>
      <li>Worked in Agile sprints and team debugging sessions.</li>
    </ul>
  </section>

  <section id="achievements">
    <h2>Achievements & Activities</h2>
    <ul>
      <li>OOPs using Python (Bootcamp), Python with AI, Git version control</li>
      <li>Organized HP Omen Gaming Fest</li>
      <li>Drama Club core member</li>
      <li>Interests: Programming, Communication Systems, Human History</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:kripriya24572@gmail.com">iampriya123456789@gmail.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/kri-priya">linkedin.com/in/kri-priya</a></p>
    <p>GitHub: <a href="https://github.com/Priyaghosh003">github.com/Priyaghosh003</a></p>
    <p>Phone: 98877 95914</p>
  </section>

  <footer>
    <p>&copy; 2025 Kumari Priya. All rights reserved.</p>
  </footer>
</body>
</html>
