---
layout: single
title: ""
excerpt: "Data Analyst Portfolio – Dashboards, Tableau, Google Sheets & Excel, Power BI, SQL"
author_profile: true
classes: wide
breadcrumbs: false
search: false
header:
  overlay_color: "#5e1a1a"
markdown: kramdown
kramdown:
  parse_block_html: true
---

<style>
/* === ФОН + ШАПКА === */
body { background:#f6f1ed !important; }                    /* теплий фон */
.masthead, .masthead__inner-wrap { background:#5e1a1a !important; }
.masthead { box-shadow:0 4px 14px rgba(0,0,0,.15); }
.page__content { background:transparent !important; }

/* прибрати пошук/порожній блок у шапці */
.masthead input, .masthead form,
.masthead .site-search, .masthead .search,
.masthead .search__toggle, .masthead .search__drawer,
.masthead .search-wrapper, .masthead .align-right { display:none !important; }
.masthead + .initial-content, .page__header + .initial-content { margin-top:0 !important; }

/* === ЗАГОЛОВОК + ПІДПИС (центр) === */
.page__title, .page__meta, .page__lead, .archive__item-title, .page__header { text-align:center !important; }
.page__title { font-size:2.1rem !important; font-weight:700 !important; margin-bottom:.4rem !important; }
.page__lead  { display:block !important; color:#f2e6e3 !important; font-size:1.15rem !important;
               font-weight:500 !important; letter-spacing:.3px !important; line-height:1.4 !important; margin-top:0 !important; }

/* === САЙДБАР === */
.author__avatar img{ width:120px !important; height:auto !important; border-radius:50% !important; box-shadow:0 3px 10px rgba(0,0,0,.1); }
.author__urls a{ color:#7a2431 !important; font-weight:700 !important; font-size:1.15rem !important; letter-spacing:.3px !important;
                 display:inline-block !important; margin-bottom:6px !important; }
.author__urls a:hover{ color:#5e1a1a !important; text-decoration:underline !important; }

/* === ШИРИНА КОНТЕНТУ === */
.page .page__inner-wrap { max-width:1320px !important; }

/* === КАРТКИ ПРОЄКТІВ — БІЛЬШІ + БІЛЬШЕ ВІДСТАНІ === */
.project-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(420px, 1fr));  /* ширші */
  gap:36px;                                                    /* більше повітря */
  margin-top:1.8rem;
}
.project-card{
  background:#fff; border:1px solid #e7e3e9; border-radius:18px;
  box-shadow:0 8px 22px rgba(24,16,32,.06), 0 2px 6px rgba(24,16,32,.04);
  transition:transform .18s ease, box-shadow .18s ease, border-color .18s ease;
  overflow:hidden; padding-bottom:4px;
}
.project-card:hover{ transform:translateY(-4px); box-shadow:0 16px 36px rgba(24,16,32,.12), 0 4px 12px rgba(24,16,32,.06); border-color:#d6c9d4; }
.project-card img{ width:100%; height:300px; object-fit:cover; display:block; background:#faf9fb; }
.project-card-content{ padding:22px 22px 26px; }
.project-card-content h3{ margin:0 0 10px; font-size:1.25rem; line-height:1.4; color:#2e2a30; }
.project-card-content p{ font-size:1rem; color:#524d57; margin:6px 0 0; }

/* === РОЗДІЛЮВАЧІ === */
.page__content hr{ border:0; height:1px; background:#e9e4ee; margin:24px 0; }
</style>

<div class="container-wide" markdown="1">

## Hi there 👋 I'm Lina

I'm a **Data Analyst** passionate about turning data into stories and interactive dashboards.  
My focus is on **data visualization, reporting, and delivering insights** that support decision making.

---

## 🛠 Skills

- **Tableau & Looker Studio** – interactive dashboards, visual storytelling  
- **Power BI** – business reporting & performance tracking  
- **Google Sheets & Excel** – data cleaning, automation, reporting  
- **BigQuery & SQL** – data extraction and transformation  

---

## 📂 Featured Projects

<div class="project-grid">

  <div class="project-card">
    <img src="https://github.com/linaherasymenko/ab-test-discount-subscription/blob/main/test_results.png?raw=true" alt="A/B Test Case Study">
    <div class="project-card-content">
      <h3>🧪 A/B Test Case Study</h3>
      <p>Analyzed the impact of a 50% discount on user conversions using Python and statistical methods (t-test, chi-square).  
      <br><strong>Tools:</strong> Python, Tableau, Stats  
      <br><a href="https://github.com/linaherasymenko/ab-test-discount-subscription">View on GitHub →</a></p>
    </div>
  </div>

  <div class="project-card">
    <img src="https://github.com/linaherasymenko/tableau-revenue-analysis-dashboard/blob/main/revenue_new.png?raw=true" alt="Revenue Dashboard – Tableau">
    <div class="project-card-content">
      <h3>📉 Revenue Analysis Dashboard – Tableau</h3>
      <p>Interactive dashboard showing monthly revenue trends by region and category.  
      <br><strong>Tools:</strong> Tableau, SQL  
      <br><a href="https://github.com/linaherasymenko/tableau-revenue-analysis-dashboard">View on GitHub →</a></p>
    </div>
  </div>

  <div class="project-card">
    <img src="https://github.com/linaherasymenko/user-retention-activity-analysis/blob/main/weekly_dauwau_dynamics.png?raw=true" alt="User Activity – Google Sheets">
    <div class="project-card-content">
      <h3>📈 User Activity – Google Sheets</h3>
      <p>Analyzed user activity and retention with custom formulas and cohort views.  
      <br><strong>Tools:</strong> Google Sheets  
      <br><a href="https://github.com/linaherasymenko/user-retention-activity-analysis">View on GitHub →</a></p>
    </div>
  </div>

  <div class="project-card">
    <img src="https://github.com/linaherasymenko/E-commerce-Conversion-Analysis-Looker-Studio-BigQuery-/blob/main/ecommerce_funnel.png?raw=true" alt="E-commerce Funnel – Looker & BigQuery">
    <div class="project-card-content">
      <h3>🛒 E-commerce Funnel – Looker & BigQuery</h3>
      <p>Funnel to analyze drop-offs and conversions across platforms.  
      <br><strong>Tools:</strong> BigQuery, Looker Studio  
      <br><a href="https://github.com/linaherasymenko/E-commerce-Conversion-Analysis-Looker-Studio-BigQuery-">View on GitHub →</a></p>
    </div>
  </div>

  <div class="project-card">
    <img src="https://github.com/linaherasymenko/Sales-Payment-Analysis-Dashboard-Power-BI-/blob/main/sales_payment_power_BI.png?raw=true" alt="Sales & Payment – Power BI">
    <div class="project-card-content">
      <h3>💳 Sales & Payment – Power BI</h3>
      <p>Power BI dashboard for payments, sales and revenue performance by segment.  
      <br><strong>Tools:</strong> Power BI, Excel  
      <br><a href="https://github.com/linaherasymenko/Sales-Payment-Analysis-Dashboard-Power-BI-">View on GitHub →</a></p>
    </div>
  </div>

</div>

---

## 🌱 Currently Learning

- Advanced Power BI techniques  
- Python for data pipelines  
- English for Data Analytics

</div>
