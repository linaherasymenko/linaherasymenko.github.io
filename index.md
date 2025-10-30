---
layout: single
title: ""  # прибирає дубль імені
excerpt: "Data Analyst Portfolio – Dashboards, Tableau, Google Sheets & Excel, Power BI, SQL"
author_profile: true
classes: wide
breadcrumbs: false
header:
  overlay_color: "#5e1a1a"
markdown: kramdown
kramdown:
  parse_block_html: true
---

<style>
/* ==== GLOBAL FIXES (форс-override теми) ==== */
body { background:#f6f1ed !important; }
.masthead { background-color:#5e1a1a !important; } /* верхня смуга */
.page__content { background:transparent !important; }

/* Сайдбар (аватар + посилання) */
.sidebar .author__avatar img,
.author__avatar img {
  width:110px !important;
  height:auto !important;
  border-radius:50% !important;
}
.sidebar .author__urls a,
.author__urls a {
  color:#7c2f3b !important;
  font-weight:700 !important;
  font-size:1.1rem !important;
  letter-spacing:0.2px !important;
}
.sidebar .author__urls a:hover,
.author__urls a:hover { color:#5e1a1a !important; text-decoration:underline !important; }

/* Трохи ширше тіло сторінки */
.page .page__inner-wrap { max-width:1240px !important; }

/* ==== КАРТКИ ПРОЄКТІВ ==== */
.project-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(380px, 1fr));
  gap:28px;
  margin-top:1.25rem;
}
.project-card{
  background:#fff;
  border:1px solid #e7e3e9;
  border-radius:16px;
  box-shadow:0 8px 22px rgba(24,16,32,.06), 0 2px 6px rgba(24,16,32,.04);
  transition:transform .18s ease, box-shadow
