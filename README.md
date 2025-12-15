<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>GitHub Profile Preview</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f6f8fa;
      color: #24292e;
      margin: 0;
      padding: 40px;
    }
    .container {
      max-width: 900px;
      margin: auto;
      background: #ffffff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.08);
    }
    h1, h2, h3 {
      text-align: center;
    }
    .badges img {
      margin: 6px;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: #fafbfc;
      border-radius: 14px;
      padding: 25px;
      text-align: center;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 12px 25px rgba(0,0,0,0.12);
    }
    .card img {
      width: 72px;
      margin-bottom: 15px;
    }
    .footer {
      text-align: center;
      margin-top: 40px;
      font-style: italic;
      color: #57606a;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>👋 Hi, I’m Seyi Adeyemi</h1>
    <h3>I turn raw data into insights, dashboards, and decisions 📊</h3>

    <div class="badges" style="text-align:center; margin: 25px 0;">
      <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
      <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" />
      <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
    </div>

    <h2>🧠 About Me</h2>
    <p style="max-width:700px; margin: 20px auto; text-align:center; line-height:1.6;">
      I’m a data analyst who enjoys turning <strong>raw, messy data</strong> into clear insights that people can actually use.<br/><br/>
      I focus on understanding the <em>story behind the numbers</em>, cleaning and structuring data so analysis is reliable, and building dashboards that help stakeholders make better decisions.<br/><br/>
      I’m naturally curious, detail-oriented, and slightly obsessed with making things easier to understand — whether that’s a report, a dashboard, or a spreadsheet.
    </p>

    <h2>📂 Featured Projects</h2>

   <a href="https://seyi-adeyemi.github.io/cust-segmentation/" style="text-decoration:none; color:inherit;">
  <div class="card">
    <h3>Customer Segmenation Analysis: Excel to PowerBI</h3>
    <p><strong>Impact:</strong> Supported leadership with real-time, data-driven insights for strategic decisions.</p>
  </div>
</a>

<a href="https://seyi-adeyemi.github.io/sales_insight/" style="text-decoration:none; color:inherit;">
  <div class="card">
   <h3>Sales and Customer Insight using Python</h3>
<p><strong>Impact:</strong> Improved business performance and operational efficiency.</p>
<p>Exploratory data analysis using Pandas & NumPy.</p>
  </div>
</a>



    <div class="footer">
      ⭐ If you like my work, consider starring a repo, the data enjoys the attention.
    </div>
  </div>
</body>
</html>
