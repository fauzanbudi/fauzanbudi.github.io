---
layout: default
title: Portfolio
permalink: /portfolio
---

<style>
  .portfolio-list a {
    font-size: 0.90rem;
    color: blue;
    text-decoration: underline;
  }
  .portfolio-list li ul {
    font-size: 0.90rem;
  }
  .portfolio-list > li {
    margin-bottom: 1.25rem;
  }
</style>

<section>
  <h3>Portfolio</h3>

  <ul class="portfolio-list">

    <li>
      <div class="course-name">Predicting 30-Day Readmission After Cardiac Surgery Using MIMIC-IV Dataset (R Shiny dashboard)</div>
      <div class="course-terms">
        <a href="https://fauzanbudi.shinyapps.io/cardiac_surgery_readmission/" target="_blank" rel="noopener noreferrer">Link to Dashboard</a>
        <br />
        <a href="https://fauzanbudi.github.io/2026/05/13/cardiac-surgery-readmission/" target="_blank" rel="noopener noreferrer">Link to Analysis Report</a>
        <br />
        <a href="https://github.com/fauzanbudi/shiny_cardiac_surgery_readmission/blob/main/fauzan_BIOSTAT_203B_212A_Final.qmd" target="_blank" rel="noopener noreferrer">Link to github repo</a>
        <br />
      </div>
      <ul>
        <li>Built a data pipeline from Physionet BigQuery EHR data, combining hospital admission, ICU vitals, labs, and EKG tables across 500 million rows and 50 GB.</li>
        <li>Ran and evaluated prediction models in R, achieving ROC AUC values around 0.65.</li>
        <li>Developed a Shiny exploratory dashboard for cohort EDA, hyperparameter tuning, admission-discharge-transfer analysis, and historical ICU vitals plots.</li>
      </ul>
    </li>

    <li>
      <div class="course-name">Chronic Disease and Physical Inactivity Epidemiology Model Explorer (Python Dash dashboard)</div>
      <div class="course-terms">
        <a href="https://dash-chronics-sdoh-and-physical-inactivity-823269868852.us-central1.run.app/" target="_blank" rel="noopener noreferrer">Link to Dashboard</a>
        <br />
        <a href="https://github.com/fauzanbudi/dash_chronics_sdoh_and_physical_inactivity" target="_blank" rel="noopener noreferrer">Link to github repo</a>
        <br />
      </div>
      <ul>
        <li>Built an interactive Dash application using the CDC BRFSS dataset to analyze how social determinants of health influence physical inactivity in chronic-condition populations.</li>
        <li>Deployed the app on Google Cloud Run with cohort building by chronic condition, BMI, sex, and income, plus model training and evaluation workflows.</li>
        <li>Integrated Gemini AI to generate model narratives, identify key risk drivers, and surface public health recommendations.</li>
      </ul>
    </li>

    <li>
      <div class="course-name">Analysis report: SDOH and Physical activity amongst people with diabetes</div>
      <div class="course-terms">
        <a href="https://fauzanbudi.github.io/2026/07/15/brfss-sdoh-physical-inactivity/" target="_blank" rel="noopener noreferrer">Link to Analysis Report</a>
        <br />
        <a href="https://github.com/fauzanbudi/diabetes-physical-activity-sdoh-brfss" target="_blank" rel="noopener noreferrer">Link to github repo</a>
      </div>
    </li>

    <li>
      <div class="course-name">Predicting Glioma Grade from Gene Mutation Profiles (Python Streamlit Dashboard)</div>
      <div class="course-terms">
        <a href="https://glioma-212b-final.streamlit.app/" target="_blank" rel="noopener noreferrer">Link to Dashboard</a>
      </div>
    </li>


    <li>
      <div class="course-name">Tableau Public</div>
      <div class="course-terms">
        <a href="https://public.tableau.com/app/profile/fauzan.budi.prasetya/vizzes" target="_blank" rel="noopener noreferrer">public.tableau.com/app/profile/fauzan.budi.prasetya/vizzes</a>
      </div>
    </li>

  </ul>

</section>
