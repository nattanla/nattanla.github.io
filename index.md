---
layout: default
---

<div class="two-column">
  <div class="column">
    <h2>📊 Projects</h2>

    <h3>💳 Fraud & Scam Detection</h3>
    <p><strong>Problem:</strong> Analysed scam data to identify fraud patterns and at-risk victim groups.</p>
    <ul>
      <li>Developed models (Logistic Regression, XGBoost).</li>
      <li>Clustered data to identify high-risk groups.</li>
    </ul>
    <a href="https://github.com/nattanla/fraud-scam-detection/blob/main/README.md">View Full Project →</a>

    <br><br>

    <h3>🏠 HDB Resale Price Prediction</h3>
    <p><strong>Problem:</strong> Predictive models to estimate HDB resale prices across Singapore.</p>
    <ul>
      <li>Built Linear Regression and XGBoost models.</li>
      <li>Performed cleaning and feature engineering.</li>
    </ul>
    <a href="https://github.com/nattanla/hdb_resale_prediction/blob/main/README.md">View Full Project →</a>
  </div>

  <div class="column">
    <h3>🗳️ Election Analytics</h3>
    <p><strong>Problem:</strong> Interactive dashboard for U.S. election voting trends.</p>
    <ul>
      <li>Designed KPI cards and maps in Power BI.</li>
      <li>Used DAX for competitiveness metrics.</li>
    </ul>
    <a href="https://github.com/nattanla/US_election/blob/main/README.md">View Full Project →</a>

    <hr>

    <blockquote>
      “Data tells stories — I help organisations read them.”
    </blockquote>
    
    <h3>🛠 Tools & Stack</h3>
    <ul>
      <li><strong>Python:</strong> Pandas, Scikit-learn</li>
      <li><strong>SQL:</strong> Data Extraction</li>
      <li><strong>Viz:</strong> Power BI, Tableau</li>
    </ul>
  </div>
</div>

<style>
  .two-column {
    display: flex;
    gap: 40px;
    align-items: flex-start;
  }
  .column {
    flex: 1;
  }
  /* Fixes the text crowding */
  h3 { margin-top: 0; color: #0366d6; }
  ul { padding-left: 20px; }
  li { margin-bottom: 5px; }
  blockquote { font-style: italic; color: #666; border-left: 3px solid #eee; padding-left: 15px; }
  
  @media (max-width: 768px) {
    .two-column { flex-direction: column; }
  }
</style>
