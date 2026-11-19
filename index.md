---
layout: default
---

<div class="section-label">Executive Summary & Core Competencies</div>
<div class="corp-card">
  <p style="margin-top: 0; font-size: 1.02rem; color: #334155;">
    Data & Business Analyst and Technical Strategist combining Computer Science and Business Administration at Clemson University. Experienced in large-scale data engineering, predictive modeling, and agile delivery for enterprise analytics across NYC, Boston, and Chicago.
  </p>
  <div class="pill-row">
    <span class="pill">Python (Pandas / Scikit-Learn)</span>
    <span class="pill">SQL & Relational Databases</span>
    <span class="pill">Tableau & Power BI</span>
    <span class="pill">Predictive Modeling</span>
    <span class="pill">Agile / Scrum Delivery</span>
    <span class="pill">Stakeholder Strategy</span>
  </div>
</div>

<div class="section-label">Data Analytics Case Studies</div>
<div class="corp-card">
  <h3>Modeling Revenue Determinants Across 687,000+ NY Businesses</h3>
  <div class="pill-row">
    <span class="pill">Python</span>
    <span class="pill">Random Forest</span>
    <span class="pill">Multiple Linear Regression</span>
    <span class="pill">Data Engineering</span>
  </div>

  <div class="kpi-grid">
    <div class="kpi-box">
      <div class="kpi-number">86.1%</div>
      <div class="kpi-label">Model R² (Up from 42.5%)</div>
    </div>
    <div class="kpi-box">
      <div class="kpi-number">676,016</div>
      <div class="kpi-label">Cleaned Business Records</div>
    </div>
    <div class="kpi-box">
      <div class="kpi-number">-54.9%</div>
      <div class="kpi-label">MAE Error Reduction</div>
    </div>
  </div>

  <h4>Business Objective</h4>
  <p>Identify structural determinants of annual revenue across New York State enterprises evaluating workforce scale, corporate subsidiary status, and registration types and proving why non-linear ensembles outperform traditional linear forecasting at scale.</p>

  <h4>Data Engineering & Pipeline Architecture</h4>
  <ul>
    <li><strong>Diagnosed Bimodal Missingness:</strong> Pruned features exceeding 90% missingness (secondary addresses) and eliminated redundant headquarters fields.</li>
    <li><strong>Engineered Structural Signals:</strong> Converted sparse categorical fields (such as <code>Subsidiary Code</code>) into binary indicators (<code>1</code>/<code>0</code>), transforming missingness into a measurable corporate-structure variable.</li>
    <li><strong>Preserved Sample Integrity:</strong> Applied constant imputation across fields missing 27–38% of records, retaining over 250,000 rows and filtering core predictors (less than 1.5% missingness) to <strong>676,016 clean observations</strong>.</li>
    <li><strong>Normalized Extreme Skew:</strong> Applied log transformations to <code>Yearly Revenue</code> and <code>Employee Total</code> to prevent mega-corporations from distorting weights while preserving valid $0 revenue startups and R&D entities.</li>
  </ul>

  <h4>Real-World Model Validation</h4>
  <table>
    <thead>
      <tr>
        <th>Company Profile</th>
        <th>Workforce</th>
        <th>Actual Revenue</th>
        <th>Linear Regression</th>
        <th>Random Forest</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>NYC Allied Holdings, LLC</strong> <em>(Early-Stage)</em></td>
        <td>0</td>
        <td>$0</td>
        <td>$157,096</td>
        <td><strong>$0</strong></td>
      </tr>
      <tr>
        <td><strong>W. W. Norton & Company, Inc.</strong> <em>(Mid-Market)</em></td>
        <td>500</td>
        <td>$180.77M</td>
        <td>$5,847</td>
        <td><strong>$124.54M</strong></td>
      </tr>
      <tr>
        <td><strong>BBDO Worldwide, Inc.</strong> <em>(Enterprise)</em></td>
        <td>10,000</td>
        <td>$617.00M</td>
        <td>$11.64M</td>
        <td><strong>$755.76M</strong></td>
      </tr>
    </tbody>
  </table>
</div>

<div class="section-label">Product & Project Management</div>
<div class="corp-card">
  <h3>Enterprise Analytics Capstone Consultant (Spring 2027)</h3>
  <div class="pill-row">
    <span class="pill">Client Consulting</span>
    <span class="pill">Sprint Planning</span>
    <span class="pill">Pipeline Architecture</span>
    <span class="pill">Cross-Functional Delivery</span>
  </div>
  <ul>
    <li><strong>Scope & Stakeholder Alignment:</strong> Partnering with industry sponsors to translate ambiguous business requirements into structured technical deliverables and sprint milestones.</li>
    <li><strong>Technical Execution Management:</strong> Coordinating data engineering workflows, validation benchmarks, and executive readouts from discovery through final deployment.</li>
  </ul>
</div>

<div class="section-label">Contact & Profiles</div>
<div class="corp-card" style="padding: 1.25rem 2rem;">
  <p style="margin: 0;">
    <a href="https://www.linkedin.com/in/milka-ndubuisi/">LinkedIn</a> &nbsp;&bull;&nbsp;
    <a href="your-tableau-url">Tableau Public</a> &nbsp;&bull;&nbsp;
    <a href="mailto:bogumin@clemson.com">Email</a>
  </p>
</div>