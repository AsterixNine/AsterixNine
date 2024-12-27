<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      background: #0d1117;
      color: #c9d1d9;
    }

    .header {
      text-align: center;
      margin-bottom: 40px;
      background: linear-gradient(45deg, #1f6feb, #238636);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .stats-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-bottom: 40px;
    }

    .languages-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin-bottom: 40px;
    }

    .category-card {
      background: #161b22;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      border: 1px solid #30363d;
    }

    .category-card h2 {
      color: #58a6ff;
      margin-top: 0;
      border-bottom: 2px solid #30363d;
      padding-bottom: 10px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #30363d;
    }

    th {
      color: #58a6ff;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 40px;
    }

    .social-links a {
      transition: transform 0.2s;
    }

    .social-links a:hover {
      transform: translateY(-3px);
    }

    .animate-gradient {
      background-size: 200% 200%;
      animation: gradient 15s ease infinite;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  </style>
</head>
<body>
  <div class="header animate-gradient">
    <h1>🌟 ASTERIX NINE STAR 🌟</h1>
  </div>

  <div class="stats-container">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=AsterixNine&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  </div>

  <div class="languages-grid">
    <div class="category-card">
      <h2>💻 Programming</h2>
      <table>
        <tr><th>Language</th><th>Version</th></tr>
        <tr><td>Java (Oracle)</td><td>19.0.2</td></tr>
        <tr><td>JavaScript</td><td>ES6</td></tr>
        <tr><td>C/C#/C++</td><td>Latest</td></tr>
        <tr><td>Python</td><td>3.10.0</td></tr>
        <tr><td>Ruby</td><td>3.1.0</td></tr>
      </table>
    </div>

    <div class="category-card">
      <h2>🌐 Web Technologies</h2>
      <table>
        <tr><th>Technology</th><th>Version</th></tr>
        <tr><td>HTML</td><td>5</td></tr>
        <tr><td>CSS</td><td>3</td></tr>
        <tr><td>Markdown</td><td>Latest</td></tr>
      </table>
    </div>
  </div>

  <div class="social-links">
    <a href="https://www.youtube.com/@asterixninestar" target="_blank">
      <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
    </a>
    <a href="https://instagram.com/miguel.stap/" target="_blank">
      <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
    </a>
    <a href="mailto:contato@AsterixNine">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
    </a>
  </div>
</body>
</html>
