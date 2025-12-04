<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Seyi Adeyemi | Data Analyst</title>
  <style>
    body {
      margin: 0;
      font-family: "Inter", sans-serif;
      background: #f9f9f9;
      color: #222;
      line-height: 1.6;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #1a1a1a, #333);
      color: white;
      padding: 110px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
      margin: 0;
      font-weight: 700;
    }

    .hero p {
      font-size: 1.25rem;
      max-width: 700px;
      margin: 20px auto 0;
      opacity: 0.9;
    }

    /* Section Container */
    .container {
      max-width: 900px;
      margin: 60px auto;
      padding: 0 20px;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 10px;
      font-weight: 700;
    }

    .subtle-joke {
      font-size: 0.9rem;
      color: #777;
      margin-bottom: 25px;
    }

    /* Skills */
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      margin-top: 25px;
    }

    .skill-card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      border: 1px solid #e5e5e5;
      box-shadow: 0 3px 10px rgba(0,0,0,0.05);
      transition: transform .2s, box-shadow .2s;
    }

    .skill-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 6px 16px rgba(0,0,0,0.1);
    }

    .skill-card p {
      margin: 5px 0 0;
      color: #444;
      font-size: 0.95rem;
    }

    /* Projects */
    .projects {
      margin-top: 40px;
    }

    .project-card {
      background: white;
      padding: 25px;
      border-radius: 12px;
      border: 1px solid #e5e5e5;
      box-shadow: 0 3px 10px rgba(0,0,0,0.05);
      margin-bottom: 25px;
      transition: transform .2s, box-shadow .2s;
    }

    .project-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 6px 16px rgba(0,0,0,0.1);
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 35px;
      margin-top: 40px;
      background: #f0f0f0;
      font-size: 0.95rem;
      color: #555;
    }

  .social-icon:hover { opacity: 0.7; }
</style>
</head>
<style>
  /* Dark/Light Mode Toggle */
  .theme-toggle {
    position: fixed;
    top: 20px;
    right: 20px;
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 30px;
    padding: 10px 18px;
    cursor: pointer;
    font-size: 0.9rem;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  }

  body.dark-mode {
    background: #1a1a1a;
    color: white;
  }

  body.dark-mode .container,
  body.dark-mode .project-card,
  body.dark-mode .skill-card {
    background: #222 !important;
    border-color: #444;
    color: white;
    box-shadow: none;
  }

  /* Fade Animations */
  .fade-in {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeIn 0.8s forwards;
  }

  @keyframes fadeIn {
    to { opacity: 1; transform: translateY(0); }
  }
</style>
<body>
  <section class="hero">
    <h1>Seyi Adeyemi</h1>
    <p>Data Analyst • Turning Data Into Decisions With Precision and Clarity</p>
  </section>

  

  <div class="container">

    <!-- About Section -->
    <h2>About Me</h2>
    <p>
      I'm a data analyst who enjoys transforming confusing data into clear insights, cleaner pipelines, and dashboards people actually understand.
      I specialise in SQL, Python, visualisation, and explaining analytics to humans who don't speak "data" for a living.
    </p>
    <p class="subtle-joke">I spend 80% of my time cleaning data. The remaining 20% is pretending it was clean all along.</p>

    <!-- Skills Section -->
    <h2>Skills</h2>
    <p class="subtle-joke">A completely normal amount of Excel knowledge. No, I won't fix your spreadsheets for free.</p>

    <div class="skills-grid">
      <div class="skill-card">
        <strong>SQL</strong>
        <p>The queries always work… eventually.</p>
      </div>
      <div class="skill-card">
        <strong>Python</strong>
        <p>For when Excel cries.</p>
      </div>
      <div class="skill-card">
        <strong>Data Visualisation</strong>
        <p>Makes charts that won’t scare managers.</p>
      </div>
      <div class="skill-card">
        <strong>Data Cleaning</strong>
        <p>My real full‑time job.</p>
      </div>
      <div class="skill-card">
        <strong>Dashboarding</strong>
        <p>Power BI, Looker, Tableau — pick your fighter.</p>
      </div>
    </div>

    <!-- Projects Section -->
    <div class="projects">
      <h2>Projects</h2>
      <p class="subtle-joke">Real projects below. No AI hallucinations, I promise.</p>

      <div class="project-card">
        <h3>1. Sales Analytics Dashboard</h3>
        <p>
          An interactive dashboard built with Power BI, designed to help leadership understand revenue trends, acquisition patterns, and churn.
        </p>
      </div>

      <div class="project-card">
        <h3>2. Customer Churn Prediction Model</h3>
        <p>
          A classification model using Python + Scikit-Learn to predict which customers are most likely to churn.
          Includes feature engineering, model evaluation, and a deployable pipeline.
        </p>
      </div>

      <div class="project-card">
        <h3>3. SQL Case Study: E‑Commerce Analytics</h3>
        <p>
          A series of SQL queries exploring user behaviour, purchase cycles, and funnel drop-off.
          Heavy use of CTEs and window functions because… why not.
        </p>
      </div>
    </div>
  </div>

  
  <div style="text-align:center; margin-top:40px;">
    <a href="Seyi_Adeyemi_CV.pdf" download style="background:#333; color:white; padding:12px 22px; border-radius:8px; text-decoration:none; font-size:1rem;">Download CV</a>
  </div>

  <footer>
    Built with HTML, CSS, and a perfectly reasonable amount of coffee.
  </footer>

<button class="theme-toggle" onclick="toggleTheme()">Toggle Theme</button>

<script>
  // Theme Toggle
  function toggleTheme() {
    document.body.classList.toggle('dark-mode');
  }

  // Fade-in animation
  const elements = document.querySelectorAll('.skill-card, .project-card, .container p, h2');
  elements.forEach((el, index) => {
    el.classList.add('fade-in');
    el.style.animationDelay = `${index * 0.15}s`;
  });
</script>
</body>
</html>
