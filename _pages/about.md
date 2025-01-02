---
permalink: /
title: "Amirrea's Page"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Amirrea's Page</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@600&display=swap" rel="stylesheet">
  
  <!-- Font Awesome for Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- CSS Styles -->
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }
    
    a {
      color: #3498db;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    
    a:hover {
      color: #1d6fa5;
    }
    
    h1, h2, h3 {
      font-family: 'Montserrat', sans-serif;
      color: #2c3e50;
    }
    
    /* Navigation Bar */
    nav {
      background-color: #2c3e50;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    
    .nav-container {
      max-width: 1200px;
      margin: 0 auto;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
    }
    
    .nav-links {
      display: flex;
      flex-wrap: wrap;
    }
    
    .nav-links a {
      color: #ecf0f1;
      padding: 14px 20px;
      text-align: center;
      transition: background 0.3s ease;
    }
    
    .nav-links a:hover {
      background-color: #34495e;
    }
    
    /* Header Section */
    .header {
      background: url('https://your-image-url.com/header-bg.jpg') no-repeat center center/cover;
      color: #fff;
      text-align: center;
      padding: 100px 20px;
    }
    
    .header h1 {
      font-size: 3em;
      margin-bottom: 10px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }
    
    .header p {
      font-size: 1.2em;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
    }
    
    /* Section Styles */
    section {
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
    }
    
    section h2 {
      font-size: 2em;
      margin-bottom: 20px;
      border-bottom: 2px solid #3498db;
      display: inline-block;
      padding-bottom: 5px;
    }
    
    /* Education & Research */
    ul {
      list-style-type: none;
      padding: 0;
    }
    
    ul li {
      background: #fff;
      margin-bottom: 10px;
      padding: 15px;
      border-radius: 5px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
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
      padding: 12px;
      text-align: left;
    }
    
    th {
      background-color: #3498db;
      color: #fff;
    }
    
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
    
    /* Projects */
    .projects ul li {
      background: #fff;
      margin-bottom: 10px;
      padding: 15px;
      border-radius: 5px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    }
    
    /* Hobbies */
    .hobbies-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    
    .hobby {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .hobby:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    
    .hobby img {
      width: 50px;
      height: 50px;
      margin-bottom: 15px;
    }
    
    .hobby h3 {
      margin-bottom: 10px;
      font-size: 1.5em;
    }
    
    .hobby p {
      font-size: 0.95em;
      color: #555;
    }
    
    /* Footer */
    footer {
      background-color: #2c3e50;
      color: #ecf0f1;
      text-align: center;
      padding: 20px;
    }
    
    footer a {
      color: #ecf0f1;
      margin: 0 10px;
      font-size: 1.2em;
    }
    
    footer a:hover {
      color: #3498db;
    }
    
    /* Responsive Design */
    @media (max-width: 768px) {
      .nav-links {
        flex-direction: column;
        width: 100%;
      }
      
      .nav-links a {
        text-align: left;
        padding: 10px 20px;
      }
      
      .header {
        padding: 60px 20px;
      }
      
      .header h1 {
        font-size: 2.5em;
      }
      
      .hobbies-container {
        flex-direction: column;
        align-items: center;
      }
      
      .hobby {
        width: 80%;
      }
    }
  </style>
</head>
<body>
  
  <!-- Navigation Bar -->
  <nav>
    <div class="nav-container">
      <div class="logo">
        <a href="/" style="color: #ecf0f1; font-size: 1.5em; font-weight: bold; text-decoration: none;">Amirrea</a>
      </div>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#research">Research Interests</a>
        <a href="#courses">Courses</a>
        <a href="#projects">Projects</a>
        <a href="#hobbies">Hobbies</a>
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
    <p>
      Hi, I'm Amirreza. I'm a 4th-year BSc student in Electrical Engineering at Sharif University of Technology, minoring in Applied Mathematics. I have a keen interest in Optimization and Machine Learning, specifically Reinforcement Learning.
    </p>
    <p>
      Feel free to reach out via the contact information and social media links in the footer. If you have any questions or suggestions, don't hesitate to contact me.
    </p>
    <p>
      You can view a summary of my resume below or check my <a href="https://amirrezavelae.github.io/cv/" target="_blank">CV</a> for more detailed information about my background and experiences.
    </p>
  </section>
  
  <!-- Education Section -->
  <section id="education">
    <h2>🎓 Education</h2>
    <ul>
      <li><strong>Allameh Jafari High School (NODET)</strong> - Graduated in 2021</li>
      <li><strong>Sharif University of Technology</strong> - Expected graduation in 2026</li>
    </ul>
  </section>
  
  <!-- Research Interests Section -->
  <section id="research">
    <h2>🔍 Research Interests</h2>
    <ul>
      <li>Machine Learning</li>
      <li>Reinforcement Learning</li>
      <li>Optimization</li>
      <li>Game Theory</li>
      <li>High Dimensional Statistics and Probability</li>
      <li>Random Walks and Percolation</li>
    </ul>
  </section>
  
  <!-- Courses Section -->
  <section id="courses">
    <h2>📚 Selected Advanced Courses</h2>
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
  </section>
  
  <!-- Projects Section -->
  <section id="projects">
    <h2>💡 Selected Projects</h2>
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
  </section>
  
  <!-- Hobbies Section -->
  <section id="hobbies">
    <h2>🎨 Hobbies</h2>
    <div class="hobbies-container">
      
      <!-- Chess -->
      <div class="hobby">
        <i class="fas fa-chess-knight fa-3x" style="color:#2c3e50;"></i>
        <h3>♟️ Chess</h3>
        <p>
          I enjoy playing chess. If you'd like to play with a beginner, feel free to connect:
          <a href="https://link.chess.com/friend/SiXm6d" target="_blank">Chess.com</a>
        </p>
      </div>
      
      <!-- Music -->
      <div class="hobby">
        <i class="fab fa-spotify fa-3x" style="color:#1db954;"></i>
        <h3>🎵 Music</h3>
        <p>
          I'm exploring Spotify. Share your favorite playlists or 
          <a href="https://open.spotify.com/user/31ydjo3ivzw7kyuih26z6kbyy6n4" target="_blank">follow me</a>.
          I especially love non-English music!
        </p>
      </div>
      
      <!-- Letterboxd -->
      <div class="hobby">
        <i class="fas fa-film fa-3x" style="color:#e74c3c;"></i>
        <h3>🎬 Letterboxd</h3>
        <p>
          I love tracking and reviewing movies. Check out my profile or 
          <a href="https://letterboxd.com/amirrezza/" target="_blank">follow me</a> for recommendations.
        </p>
      </div>
      
      <!-- Duolingo -->
      <div class="hobby">
        <i class="fas fa-language fa-3x" style="color:#27ae60;"></i>
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
  
</body>
</html>
