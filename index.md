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
  <h4>Interactive Market Revenue Dashboard</h4>
<div style="position: relative; width: 100%; padding-bottom: 65%; height: 0; overflow: hidden; border: 1px solid #e2e8f0; border-radius: 6px; margin-top: 1rem;">
  <iframe 
    src="<div class='tableauPlaceholder' id='viz1795475900628' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;po&#47;portfolioDashboards&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='portfolioDashboards&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;po&#47;portfolioDashboards&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1795475900628');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='977px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>?:showVizHome=no&:embed=true" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" 
    allowfullscreen>
  </iframe>
</div>
</div>

<div class="section-label">Product & Project Management</div>
<div class="corp-card">
  <h3>Technical Project Delivery & Agile Execution</h3>
  <div class="pill-row">
    <span class="pill">Scope Management</span>
    <span class="pill">Agile / Scrum</span>
    <span class="pill">Stakeholder Communication</span>
    <span class="pill">Roadmap & Timeline Tracking</span>
  </div>

  <h4>Case Study: TigerSpot Campus Routing Prototype (Deloitte Innovation Challenge)</h4>
  <ul>
    <li><strong>Scope & Timeline:</strong> Led a cross-functional student team through a compressed multi-week sprint cycle to deliver an AI-driven campus parking and traffic routing prototype using SCDOT data.</li>
    <li><strong>Resource & Constraint Management:</strong> Prioritized core MVP features (real-time lot congestion modeling and executive analytics dashboard) within strict academic and compute constraints, preventing scope creep ahead of final pitch deadlines.</li>
    <li><strong>Key Deliverables:</strong> Delivered an interactive routing prototype, cleaned traffic dataset, and executive presentation deck to consulting judges.</li>
  </ul>

  <h4>Enterprise Analytics Capstone Consultant (Spring 2027)</h4>
  <ul>
    <li><strong>Stakeholder Alignment:</strong> Partnering with enterprise industry sponsors to translate ambiguous business problems into scoped technical milestones, sprint backlogs, and measurable KPIs.</li>
    <li><strong>End-to-End Governance:</strong> Managing data pipeline architecture, validation benchmarks, and executive readouts from initial discovery through final handoff.</li>
  </ul>

  <h4>Case Study: Freelance Web & Technical Consulting (Client Delivery)</h4>
  <ul>
    <li><strong>Scope & Contract Governance:</strong> Managed end-to-end client engagements from initial discovery through deployment—drafting clear project scopes, milestone schedules, and fixed-budget deliverables to prevent scope creep.</li>
    <li><strong>Agile Execution & Stakeholder Alignment:</strong> Ran iterative two-week feedback sprints with non-technical business owners, translating operational requirements into functional web deployments without missed deadlines.</li>
    <li><strong>Constraint & Risk Management:</strong> Balanced zero-cost hosting architectures and strict client timelines by standardizing modular front-end templates and automated deployment pipelines.</li>
    <li><strong>Featured Deployment:</strong> <a href="YOUR_PUBLIC_CLIENT_URL">Live Client Application</a> <em>(Additional client engagements omitted due to confidentiality agreements)</em>.</li>
  </ul>
</div>

<div class="section-label">Contact & Profiles</div>
<div class="corp-card" style="padding: 1.25rem 2rem;">
  <p style="margin: 0;">
    <a href="https://www.linkedin.com/in/milka-ndubuisi/">LinkedIn</a> &nbsp;&bull;&nbsp;
    <a href="https://public.tableau.com/app/profile/milka.ndubuisi/vizzes">Tableau Public</a> &nbsp;&bull;&nbsp;
    <a href="mailto:bogumin@clemson.com">Email</a>
  </p>
</div>