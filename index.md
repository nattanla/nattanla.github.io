---
layout: default
---

<div class="project-container">
  
  <div class="project-card">
    <div class="project-header">
      <h2>💳 Fraud & Scam Detection (Python + Tableau)</h2>
    </div>
    <div class="project-body">
      <p><strong>Problem:</strong> Analysed scam data to identify fraud patterns and at-risk victim groups using machine learning and clustering.</p>
      <ul>
        <li>Developed fraud-risk models (<strong>Logistic Regression</strong>, <strong>Random Forest</strong>, <strong>XGBoost</strong>).</li>
        <li>Clustered Scamwatch data to identify high-risk groups with (<strong>K-Means</strong>, <strong>HDBSCAN</strong>).</li>
        <li>Visualised insights in Tableau dashboards for executive reporting.</li>
      </ul>
      <div class="project-footer">
        <span class="tag">Python</span> <span class="tag">Tableau</span> <span class="tag">Machine Learning</span>
        <a href="https://github.com/nattanla/fraud-scam-detection/blob/main/README.md" class="btn">View Full Project →</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h2>🏠 HDB Resale Price Prediction (Python, ML)</h2>
    </div>
    <div class="project-body">
      <p><strong>Problem:</strong> Built predictive models to estimate HDB resale prices and identify the key factors influencing property values across Singapore.</p>
      <ul>
        <li>Built <strong>Linear Regression</strong> and <strong>XGBoost</strong> models to predict housing prices.</li>
        <li>Performed data cleaning, feature engineering and model evaluation (MAE/RMSE).</li>
        <li>Identified key features influencing price variation for improved forecasting.</li>
      </ul>
      <div class="project-footer">
        <span class="tag">Python</span> <span class="tag">Pandas</span> <span class="tag">Regression</span>
        <a href="https://github.com/nattanla/hdb_resale_prediction/blob/main/README.md" class="btn">View Full Project →</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h2>🗳️ Election Analytics Dashboard (Power BI)</h2>
    </div>
    <div class="project-body">
      <p><strong>Problem:</strong> Created an interactive dashboard to analyse voting trends, party performance, and competitiveness across U.S. elections.</p>
      <ul>
        <li>Built an interactive dashboard analysing <strong>state & county election trends</strong>.</li>
        <li>Designed KPI cards, maps and charts to highlight party shifts.</li>
        <li>Used DAX to calculate vote margins and competitiveness metrics.</li>
      </ul>
      <div class="project-footer">
        <span class="tag">Power BI</span>
        <a href="https://github.com/nattanla/US_election/blob/main/README.md" class="btn">View Full Project →</a>
      </div>
      </ul>
    </div>
  </div>

  <div class="quote-card">
    <blockquote>
      “Data tells stories — I help organisations read them.”
    </blockquote>
  </div>

</div>

<style>
  /* Container structure */
  .project-container {
    max-width: 800px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 30px; /* Space between blocks */
  }

  /* Individual Card Styling */
  .project-card {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    transition: transform 0.2s ease;
  }

  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }

  .project-header {
    background: #f6f8fa;
    padding: 15px 25px;
    border-bottom: 1px solid #e1e4e8;
  }

  .project-header h2 {
    margin: 0;
    font-size: 1.3em;
    color: #0366d6;
    border: none;
  }

  .project-body {
    padding: 20px 25px;
  }

  .project-footer {
    margin-top: 20px;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
  }

  /* Tags & Buttons */
  .tag {
    background: #eef4ff;
    color: #0366d6;
    padding: 4px 10px;
    border-radius: 4px;
    font-size: 0.75em;
    font-weight: bold;
  }

  .btn {
    margin-left: auto;
    background: #24292e;
    color: white !important;
    padding: 8px 16px;
    border-radius: 6px;
    text-decoration: none;
    font-size: 0.85em;
  }

  .btn:hover { background: #0366d6; }

  /* Quote Styling */
  .quote-card {
    text-align: center;
    padding: 20px;
    font-style: italic;
    color: #586069;
  }
  
  blockquote { border: none; font-size: 1.1em; }

  /* List spacing */
  ul { padding-left: 20px; }
  li { margin-bottom: 8px; }
</style>
