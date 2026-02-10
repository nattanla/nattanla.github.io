---
layout: default
---

<div class="two-column">
  <div class="column card">
    <h2>📊 Projects</h2>

    <div class="project-box">
      <h3>💳 Fraud & Scam Detection</h3>
      <p><strong>Problem:</strong> Analysed scam data to identify fraud patterns and at-risk victim groups.</p>
      <ul>
        <li>Developed models (Logistic Regression, XGBoost).</li>
        <li>Clustered data to identify high-risk groups.</li>
      </ul>
      <a href="https://github.com/nattanla/fraud-scam-detection/blob/main/README.md" class="btn">View Project →</a>
    </div>

    <div class="project-box">
      <h3>🏠 HDB Resale Price Prediction</h3>
      <p><strong>Problem:</strong> Predictive models to estimate HDB resale prices across Singapore.</p>
      <ul>
        <li>Built Linear Regression and XGBoost models.</li>
        <li>Performed cleaning and feature engineering.</li>
      </ul>
      <a href="https://github.com/nattanla/hdb_resale_prediction/blob/main/README.md" class="btn">View Project →</a>
    </div>
  </div>

  <div class="column card">
    <h2>📈 Analytics & Insights</h2>
    
    <div class="project-box">
      <h3>🗳️ Election Analytics</h3>
      <p><strong>Problem:</strong> Interactive dashboard for U.S. election voting trends.</p>
      <ul>
        <li>Designed KPI cards and maps in Power BI.</li>
        <li>Used DAX for competitiveness metrics.</li>
      </ul>
      <a href="https://github.com/nattanla/US_election/blob/main/README.md" class="btn">View Project →</a>
    </div>

    <div class="quote-box">
      <blockquote>
        “Data tells stories — I help organisations read them.”
      </blockquote>
    </div>
  </div>
</div>

<style>
  /* Container Setup */
  .two-column {
    display: flex;
    gap: 25px;
    align-items: stretch; /* Makes both columns same height */
  }

  /* Column structure */
  .column {
    flex: 1; 
    min-width: 300px; /* Prevents columns from getting too narrow */
    display: flex;
    flex-direction: column;
  }

  /* Card Style for the columns */
  .card {
    background: #ffffff;
    padding: 25px;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    min-height: 600px; /* Sets a fixed minimum height */
  }

  /* Individual Project Spacing */
  .project-box {
    margin-bottom: 30px;
    padding-bottom: 20px;
    border-bottom: 1px solid #f0f0f0;
  }
  
  .project-box:last-child { border-bottom: none; }

  /* Buttons */
  .btn {
    display: inline-block;
    background: #0366d6;
    color: white !important;
    padding: 8px 16px;
    border-radius: 6px;
    text-decoration: none;
    font-size: 0.9em;
    font-weight: 500;
  }
  
  .btn:hover { background: #0255b3; }

  /* Typography */
  h2 { font-size: 1.5em; border-bottom: 2px solid #0366d6; padding-bottom: 5px; margin-bottom: 20px; }
  h3 { color: #0366d6; margin-top: 10px; font-size: 1.2em; }
  ul { padding-left: 20px; margin-bottom: 15px; }
  
  .quote-box {
    margin: 20px 0;
    padding: 15px;
    background: #f6f8fa;
    border-radius: 8px;
    border-left: 5px solid #0366d6;
  }

  /* Responsive Fix */
  @media (max-width: 768px) {
    .two-column { flex-direction: column; }
    .card { min-height: auto; }
  }
</style>
