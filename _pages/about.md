---
permalink: /
title: "Amirrea's Page"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Amirrea's Page</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Poppins:wght@600&display=swap" rel="stylesheet">
  
  <!-- Font Awesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- CSS Styles -->
  <style>
    /* CSS Variables for Theme Management */
    :root {
      --primary-color: #3498db;
      --secondary-color: #2c3e50;
      --accent-color: #e74c3c;
      --light-bg: #f9f9f9;
      --dark-bg: #2c3e50;
      --text-color: #333;
      --light-text: #ecf0f1;
      --font-family-body: 'Roboto', sans-serif;
      --font-family-heading: 'Poppins', sans-serif;
      --transition-speed: 0.3s;
      --max-width: 1200px;
      --nav-height: 70px;
      --shadow-color: rgba(0, 0, 0, 0.1);
    }
    
    /* Global Styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    
    body {
      font-family: var(--font-family-body);
      line-height: 1.6;
      color: var(--text-color);
      background-color: var(--light-bg);
      transition: background-color var(--transition-speed), color var(--transition-speed);
    }
    
    a {
      color: var(--primary-color);
      text-decoration: none;
      transition: color var(--transition-speed);
    }
    
    a:hover {
      color: #1d6fa5;
    }
    
    h1, h2, h3 {
      font-family: var(--font-family-heading);
      color: var(--secondary-color);
    }
    
    /* Dark Mode Styles */
    body.dark-mode {
      background-color: #121212;
      color: #e0e0e0;
    }
    
    body.dark-mode a {
      color: #90caf9;
    }
    
    body.dark-mode nav {
      background-color: #1f1f1f;
    }
    
    body.dark-mode header {
      background: url('https://your-image-url.com/header-bg-dark.jpg') no-repeat center center/cover;
    }
    
    body.dark-mode .card {
      background-color: #1f1f1f;
      box-shadow: 0 4px 8px rgba(255,255,255,0.1);
    }
    
    /* Navigation Bar */
    nav {
      background-color: var(--secondary-color);
      box-shadow: 0 2px 4px var(--shadow-color);
      position: sticky;
      top: 0;
      z-index: 1000;
      transition: background-color var(--transition-speed);
      height: var(--nav-height);
    }
    
    .nav-container {
      max-width: var(--max-width);
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 100%;
      padding: 0 20px;
    }
    
    .logo a {
      color: var(--light-text);
      font-size: 1.8em;
      font-weight: 700;
      text-decoration: none;
      transition: color var(--transition-speed);
    }
    
    .nav-links {
      display: flex;
      align-items: center;
    }
    
    .nav-links a {
      color: #bdc3c7; /* Lighter shade for better contrast */
      padding: 10px 15px;
      margin: 0 5px;
      border-radius: 4px;
      transition: background-color var(--transition-speed), color var(--transition-speed);
      font-weight: 500;
      font-size: 1em;
    }
    
    .nav-links a:hover {
      background-color: var(--primary-color);
      color: #fff;
    }
    
    /* Dark Mode Toggle */
    .dark-mode-toggle {
      margin-left: 20px;
      cursor: pointer;
      font-size: 1.2em;
      color: var(--light-text);
      transition: color var(--transition-speed);
    }
    
    .dark-mode-toggle:hover {
      color: var(--accent-color);
    }
    
    /* Header Section */
    header.header {
      background: url('https://your-image-url.com/header-bg.jpg') no-repeat center center/cover;
      color: #fff;
      text-align: center;
      padding: 150px 20px;
      position: relative;
      transition: background-image var(--transition-speed);
    }
    
    header.header.dark-mode {
      background: url('https://your-image-url.com/header-bg-dark.jpg') no-repeat center center/cover;
    }
    
    header.header h1 {
      font-size: 3.5em;
      margin-bottom: 20px;
      text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
      animation: fadeInDown 1s ease-out;
    }
    
    header.header p {
      font-size: 1.5em;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
      animation: fadeInUp 1s ease-out;
    }
    
    /* Animations */
    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    /* Section Styles */
    section {
      max-width: var(--max-width);
      margin: 60px auto;
      padding: 0 20px;
    }
    
    section h2 {
      font-size: 2.5em;
      margin-bottom: 30px;
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    
    section h2::after {
      content: '';
      width: 50px;
      height: 4px;
      background-color: var(--primary-color);
      position: absolute;
      left: 0;
      bottom: 0;
      border-radius: 2px;
    }
    
    /* Cards for Lists */
    .card {
      background: #fff;
      padding: 25px 30px;
      margin-bottom: 30px;
      border-radius: 15px;
      box-shadow: 0 8px 16px var(--shadow-color);
      transition: transform var(--transition-speed), box-shadow var(--transition-speed);
    }
    
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 24px var(--shadow-color);
    }
    
    body.dark-mode .card {
      background-color: #1f1f1f;
      box-shadow: 0 8px 16px rgba(255,255,255,0.05);
    }
    
    /* Education & Research */
    ul {
      list-style-type: none;
    }
    
    ul li {
      margin-bottom: 15px;
      font-size: 1.1em;
      position: relative;
      padding-left: 20px;
    }
    
    ul li::before {
      content: "•";
      position: absolute;
      left: 0;
      color: var(--primary-color);
      font-size: 1.2em;
      top: 0;
    }
    
    /* Courses Table */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    
    table, th, td {
      border: 1px solid #ddd;
    }
    
    th, td {
      padding: 14px;
      text-align: left;
      transition: background-color var(--transition-speed);
      font-size: 1em;
    }
    
    th {
      background-color: var(--primary-color);
      color: #fff;
      font-weight: 600;
    }
    
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
    
    tr:hover {
      background-color: #ddd;
    }
    
    /* Projects */
    .projects ul li {
      font-size: 1.1em;
      margin-bottom: 15px;
      position: relative;
      padding-left: 20px;
    }
    
    .projects ul li::before {
      content: "🔹";
      position: absolute;
      left: 0;
      top: 0;
    }
    
    /* Hobbies Section */
    .hobbies-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      margin-top: 30px;
    }
    
    .hobby {
      background: linear-gradient(135deg, #f0f0f0, #ffffff);
      padding: 25px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 8px 16px var(--shadow-color);
      transition: transform var(--transition-speed), box-shadow var(--transition-speed), background 0.3s ease;
    }
    
    .hobby:hover {
      transform: translateY(-10px);
      box-shadow: 0 16px 32px var(--shadow-color);
      background: linear-gradient(135deg, #e0e0e0, #f9f9f9);
    }
    
    .hobby i {
      font-size: 3em;
      margin-bottom: 15px;
      transition: color var(--transition-speed);
    }
    
    .hobby:hover i {
      color: var(--primary-color);
    }
    
    .hobby h3 {
      font-size: 1.5em;
      margin-bottom: 10px;
      color: var(--secondary-color);
    }
    
    .hobby p {
      font-size: 1em;
      color: #555;
      transition: color var(--transition-speed);
    }
    
    body.dark-mode .hobby {
      background: #1f1f1f;
      box-shadow: 0 8px 16px rgba(255,255,255,0.05);
    }
    
    body.dark-mode .hobby p {
      color: #ccc;
    }
    
    /* Footer */
    footer {
      background-color: var(--secondary-color);
      color: var(--light-text);
      text-align: center;
      padding: 30px 20px;
      transition: background-color var(--transition-speed), color var(--transition-speed);
    }
    
    footer a {
      color: var(--light-text);
      margin: 0 15px;
      font-size: 1.2em;
      transition: color var(--transition-speed);
    }
    
    footer a:hover {
      color: var(--primary-color);
    }
    
    footer p {
      margin-top: 15px;
      font-size: 0.95em;
    }
    
    /* Responsive Design */
    @media (max-width: 768px) {
      .nav-container {
        flex-direction: column;
        align-items: flex-start;
        height: auto;
      }
      
      .nav-links {
        flex-direction: column;
        width: 100%;
      }
      
      .nav-links a {
        width: 100%;
        padding: 10px 20px;
      }
      
      .dark-mode-toggle {
        margin: 10px 0;
      }
      
      header.header {
        padding: 100px 20px;
      }
      
      header.header h1 {
        font-size: 2.5em;
      }
      
      header.header p {
        font-size: 1.2em;
      }
      
      .hobbies-container {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  
  <!-- Navigation Bar -->
  <nav>
    <div class="nav-container">
      <div class="logo">
        <a href="/">Amirrea</a>
      </div>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#research">Research Interests</a>
        <a href="#courses">Courses</a>
        <a href="#projects">Projects</a>
        <a href="#hobbies">Hobbies</a>
        <span class="dark-mode-toggle" id="dark-mode-toggle" aria-label="Toggle Dark Mode">
          <i class="fas fa-moon"></i>
        </span>
      </div>
    </div>
  </nav>
  
  <!-- Header Section -->
  <header class="header">
    <h1>Welcome to my Page!</h1>
    <p>4th-year BSc Student in Electrical Engineering at Sharif University of Technology</p>
  </header>
  
  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>
        Hi, I'm Amirreza. I'm a 4th-year BSc student in Electrical Engineering at Sharif University of Technology, minoring in Applied Mathematics. I have a keen interest in Optimization and Machine Learning, specifically Reinforcement Learning.
      </p>
      <p>
        Feel free to reach out via the contact information and social media links in the footer. If you have any questions or suggestions, don't hesitate to contact me.
      </p>
      <p>
        You can view a summary of my resume below or check my <a href="https://amirrezavelae.github.io/cv/" target="_blank">CV</a> for more detailed information about my background and experiences.
      </p>
    </div>
  </section>
  
  <!-- Education Section -->
  <section id="education">
    <h2>🎓 Education</h2>
    <div class="card">
      <ul>
        <li><strong>Allameh Jafari High School (NODET)</strong> - Graduated in 2021</li>
        <li><strong>Sharif University of Technology</strong> - Expected graduation in 2026</li>
      </ul>
    </div>
  </section>
  
  <!-- Research Interests Section -->
  <section id="research">
    <h2>🔍 Research Interests</h2>
    <div class="card">
      <ul>
        <li>Machine Learning</li>
        <li>Reinforcement Learning</li>
        <li>Optimization</li>
        <li>Game Theory</li>
        <li>High Dimensional Statistics and Probability</li>
        <li>Random Walks and Percolation</li>
      </ul>
    </div>
  </section>
  
  <!-- Courses Section -->
  <section id="courses">
    <h2>📚 Selected Advanced Courses</h2>
    <div class="card">
      <table>
        <thead>
          <tr>
            <th>Course</th>
            <th>Grade</th>
            <th>Status</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Machine Learning</td>
            <td>19.5/20.0</td>
            <td>Completed</td>
          </tr>
          <tr>
            <td>Signal and System</td>
            <td>19.2/20.0</td>
            <td>Completed</td>
          </tr>
          <tr>
            <td>Mathematical Methods in Engineering (Linear Algebra)</td>
            <td>19.8/20.0</td>
            <td>Completed</td>
          </tr>
          <tr>
            <td>Game Theory</td>
            <td>17.8/20</td>
            <td>Completed</td>
          </tr>
          <tr>
            <td>Optimization</td>
            <td>17/20</td>
            <td>Completed</td>
          </tr>
          <tr>
            <td>Reinforcement Learning <span style="color:red;">*</span></td>
            <td>20/20</td>
            <td>Graduated Course</td>
          </tr>
          <tr>
            <td>Deep Learning <span style="color:red;">*</span></td>
            <td>17.2/20.0</td>
            <td>Graduated Course</td>
          </tr>
          <tr>
            <td>Random Walks and Percolation <span style="color:red;">*</span></td>
            <td>—</td>
            <td>Audited</td>
          </tr>
          <tr>
            <td>Stochastic Processes</td>
            <td>—</td>
            <td>Self-Studied</td>
          </tr>
          <tr>
            <td>Convex Optimization II <span style="color:red;">*</span></td>
            <td>—</td>
            <td>Currently Enrolled</td>
          </tr>
          <tr>
            <td>Optimal Control <span style="color:red;">*</span></td>
            <td>—</td>
            <td>Currently Enrolled</td>
          </tr>
          <tr>
            <td>High Dimensional Probability <span style="color:red;">*</span></td>
            <td>—</td>
            <td>Currently Enrolled</td>
          </tr>
          <tr>
            <td>Non-Convex Optimization <span style="color:red;">*</span></td>
            <td>—</td>
            <td>Currently Enrolled</td>
          </tr>
          <tr>
            <td>Online Learning <span style="color:red;">*</span></td>
            <td>—</td>
            <td>Currently Auditing</td>
          </tr>
        </tbody>
      </table>
      <p><span style="color:red;">*</span> Indicates a Graduated Course</p>
    </div>
  </section>
  
  <!-- Projects Section -->
  <section id="projects">
    <h2>💡 Selected Projects</h2>
    <div class="card">
      <ul>
        <li>
          <strong>Policy Planning in Large Language Models</strong> (Ongoing) - 
          <a href="https://scholar.google.com/citations?user=yiZk6coAAAAJ&hl=en" target="_blank">Advisor: Prof. Mohammad Aliannejadi</a>
        </li>
        <li>
          <strong>L2D in Bayesian Neural Networks</strong> - 
          <a href="https://charusaie.github.io/" target="_blank">Advisor: Amin Charusaie</a> & 
          <a href="https://www.samirasamadi.com/" target="_blank">Prof. Samira Samadi</a>
        </li>
      </ul>
    </div>
  </section>
  
  <!-- Hobbies Section -->
  <section id="hobbies">
    <h2>🎨 Hobbies</h2>
    <div class="hobbies-container">
      
      <!-- Chess -->
      <div class="hobby">
        <i class="fas fa-chess-knight" style="color:#2c3e50;"></i>
        <h3>♟️ Chess</h3>
        <p>
          I enjoy playing chess. If you'd like to play with a beginner, feel free to connect:
          <a href="https://link.chess.com/friend/SiXm6d" target="_blank">Chess.com</a>
        </p>
      </div>
      
      <!-- Music -->
      <div class="hobby">
        <i class="fab fa-spotify" style="color:#1db954;"></i>
        <h3>🎵 Music</h3>
        <p>
          I'm exploring Spotify. Share your favorite playlists or 
          <a href="https://open.spotify.com/user/31ydjo3ivzw7kyuih26z6kbyy6n4" target="_blank">follow me</a>.
          I especially love non-English music!
        </p>
      </div>
      
      <!-- Letterboxd -->
      <div class="hobby">
        <i class="fas fa-film" style="color:#e74c3c;"></i>
        <h3>🎬 Letterboxd</h3>
        <p>
          I love tracking and reviewing movies. Check out my profile or 
          <a href="https://letterboxd.com/amirrezza/" target="_blank">follow me</a> for recommendations.
        </p>
      </div>
      
      <!-- Duolingo -->
      <div class="hobby">
        <i class="fas fa-language" style="color:#27ae60;"></i>
        <h3>🌐 Duolingo</h3>
        <p>
          I'm learning Turkish and Russian as my fourth and fifth languages. Connect with me on 
          <a href="https://www.duolingo.com/profile/amirVreza" target="_blank">Duolingo</a>!
        </p>
      </div>
      
    </div>
  </section>
  
  <!-- Footer Section -->
  <footer>
    <p>
      <a href="https://github.com/amirrezavelae" target="_blank"><i class="fab fa-github"></i> GitHub</a> | 
      <a href="https://www.linkedin.com/in/amirreza-velae-22166321a/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a> | 
      <a href="mailto:amirrezavelae@gmail.com"><i class="fas fa-envelope"></i> Email</a>
    </p>
    <p>&copy; 2025 Amirrea. All rights reserved.</p>
  </footer>
  
  <!-- JavaScript for Dark Mode Toggle -->
  <script>
    const toggle = document.getElementById('dark-mode-toggle');
    const body = document.body;
    
    toggle.addEventListener('click', () => {
      body.classList.toggle('dark-mode');
      if(body.classList.contains('dark-mode')) {
        toggle.innerHTML = '<i class="fas fa-sun"></i>';
      } else {
        toggle.innerHTML = '<i class="fas fa-moon"></i>';
      }
    });
  </script>
  
</body>
</html>
