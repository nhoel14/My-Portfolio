<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Noel Baroga | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #f4f6f9;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #6a0dad, #4b0082);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    nav {
      background: #4b0082;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
    }

    h2 {
      color: #6a0dad;
      margin-bottom: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }

    .images-grid {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }

    .images-grid img {
      width: 48%;
      border-radius: 8px;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      background: #6a0dad;
      color: white;
      padding: 10px 15px;
      border-radius: 6px;
      font-weight: bold;
      text-decoration: none;
    }

    footer {
      text-align: center;
      background: #222;
      color: white;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>

<body>

<header>
  <h1>Noel Baroga</h1>
  <p>BSCS Student | Web Development & Data Projects</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <div class="card">
    <p>I am a student passionate about web development and data analysis.</p>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="card">
    <h3>Practice Task 2</h3>
    <p>Data analysis dashboard project.</p>

    <div class="images-grid">
      <img src="images/PRactice task 2 Analyze.png">
      <img src="images/Dashboard Nhoel.png">
    </div>

    <a href="files/PracticeTask2_Tuazon_Ranniel (1).xlsx" class="btn" target="_blank">
      Download Excel
    </a>
  </div>

  <div class="card">
    <h3>Midterm Task 1</h3>
    <p>Database ERD and modeling.</p>

    <div class="images-grid">
      <img src="images/erd midterm task 1.png">
    </div>

    <a href="files/midterm task 1.xlsx" class="btn" target="_blank">
      Download Excel
    </a>
  </div>

  <div class="card">
    <h3>Midterm Task 2</h3>
    <p>Power Query data preparation.</p>

    <a href="files/Midterm Lab Task 2. Data Preparation and Modeling using Power Query_Tuazon_Ranniel.pdf" class="btn" target="_blank">
      View PDF
    </a>
  </div>

</section>

<footer>
  <p>© 2026 Noel Baroga</p>
</footer>

</body>
</html>
