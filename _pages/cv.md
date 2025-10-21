---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

<!-- ===== CV PAGE (self-contained styles) ===== -->
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">

<style>
.cv-page{
  --text:#0e1116;
  --muted:#616979;
  --line:rgba(14,17,22,.10);
  --accent:#0b72ff;
  --accent-2:#5b8cff;
  font-family:"Inter", system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif;
  color:var(--text);
  font-size:13.5px;
  line-height:1.72;
}

/* Section heading – biggest */
.cv-page h2{
  font-size:22px;
  line-height:1.28;
  margin:1.1rem 0 .7rem;
}

/* Subsection title */
.cv-page h3{
  font-size:14.5px;
  line-height:1.35;
  margin:.5rem 0 .35rem;
}

/* Blue kicker label (now larger than h3) */
.cv-page .kicker{
  display:inline-block;
  font-weight:800;
  font-size:16px;
  letter-spacing:.16em;
  text-transform:uppercase;
  color:var(--accent);
  background:linear-gradient(90deg, #eaf2ff, transparent 70%);
  padding:.40rem .65rem .32rem;
  border-radius:999px;
  border:1px solid #cfe0ff;
  margin:.15rem 0 .5rem;
}

/* Simple rows and lists */
.cv-page ul{ margin:.35rem 0 .9rem 1.2rem; }
.cv-page li{ margin:.22rem 0; }
.cv-page .muted{ color:var(--muted); }

/* Divider */
.cv-page .sep{ height:1px; background:var(--line); margin:1.2rem 0; }

/* Timeline list without dots (fix overlap) */
.cv-page .timeline{ list-style:none; margin:0; padding:0; }
.cv-page .timeline li{
  position:relative;
  border-left:2px solid var(--line);   /* keep vertical guide; remove if unwanted */
  margin-left:.4rem;
  padding:.35rem 0 .75rem 1rem;        /* left padding prevents title overlap */
}
.cv-page .timeline li::before{ display:none !important; } /* remove blue dot */

/* Meeting title line */
.cv-page .meeting{
  font-weight:800;
}
.cv-page .place,
.cv-page .year{
  color:var(--muted);
  font-weight:600;
}

/* Fine print */
.cv-page small{ color:var(--muted); }
</style>

<div class="cv-page">

<!-- =======================
     Education
======================= -->
<h2>Education</h2>

<p><strong>MHS, Epidemiology</strong>, Johns Hopkins Bloomberg School of Public Health, USA (2021–2023)<br>
<em>Thesis:</em> Association of Blood Urea Nitrogen with Incident Heart Failure (ARIC Study) — Advisor: Kunihiro Matsushita</p>

<p><strong>B.S., Chemical Biology</strong>, Northwest A&amp;F University, China (2017–2021)<br>
<em>Thesis:</em> Large-scale Data Analytics for Biopharmaceuticals</p>

<div class="sep"></div>

<!-- =======================
     Professional Experience
======================= -->
<h2>Professional Experience</h2>

<h3>Research Data Coordinator</h3>
<p><em>Johns Hopkins Welch Center for Prevention, Epidemiology and Clinical Research</em> (2023–Present)</p>
<ul>
  <li>Lead statistical analyses for cardiovascular imaging, proteomics, and global health projects.</li>
  <li>Develop reproducible pipelines in R/Python for cohort studies and clinical trials.</li>
  <li>Coordinate with clinicians and methodologists to produce manuscripts, abstracts, and presentations.</li>
</ul>

<h3>Research Assistant (Remote)</h3>
<p><em>Tsinghua University, Vanke School of Public Health</em> (2025–Present)</p>
<ul>
  <li>Conduct epidemiologic analyses on maternal nutrition and environmental exposure datasets.</li>
  <li>Lead manuscript drafting and interpretation of results.</li>
</ul>

<h3>Teaching Assistant</h3>
<p><em>Johns Hopkins Bloomberg School of Public Health</em> (2022–2023)</p>
<ul>
  <li>Courses: Principles of Clinical Epidemiology; Methods and Applications of Cohort Studies.</li>
  <li>Delivered review sessions, graded assignments, and supported data analysis workshops (~20 students/class).</li>
</ul>

<div class="sep"></div>

<!-- =======================
     Research Focus
======================= -->
<h2>Research Focus</h2>
<ul>
  <li>Cardiovascular epidemiology</li>
  <li>Imaging, digital and blood biomarkers (coronary calcification, wearables, proteomics, metabolomics)</li>
  <li>Machine learning for risk prediction</li>
  <li>Global health interventions in hypertension</li>
</ul>

<div class="sep"></div>

<!-- =======================
     Honors & Awards
======================= -->
<h2>Honors &amp; Awards</h2>
<ul>
  <li><strong>Epidemiology Program Tuition Scholarship</strong>, Johns Hopkins University (2021–2023)</li>
  <li><strong>Undergraduate Scholarship</strong>, Northwest A&amp;F University (2019–2020)</li>
  <li><strong>JAMA Internal Medicine Publication</strong>, first-author clinical trial (2024)</li>
</ul>

<div class="sep"></div>

<!-- =======================
     Publications (selected)
======================= -->
<h2>Publications (Selected)</h2>
<p class="muted">See the Publications page for the complete list.</p>

<ol>
  <li><strong>First-Author Clinical Trial Publications</strong>
    <ul>
      <li>Arm Position and Blood Pressure Readings: ARMS Trial. <em>JAMA Intern Med</em>, 2024.</li>
      <li>Association of Blood Urea Nitrogen with Incident Heart Failure. <em>Circ J</em>, 2024.</li>
    </ul>
  </li>
  <li><strong>Second-Author Contributions</strong>
    <ul>
      <li>Effects of Noise and Public Setting on BP Readings. <em>Ann Intern Med</em>, 2025.</li>
      <li>Coronary Calcified Lesion Number and CVD Risk. <em>JACC Cardiovasc Imaging</em>, 2025.</li>
    </ul>
  </li>
</ol>

<div class="sep"></div>

<!-- =======================
     Abstracts & Presentations
======================= -->
<h2>Abstracts &amp; Presentations</h2>

<!-- Blue label larger than item title; no dots overlapping titles -->
<div class="kicker">Poster</div>
<ul class="timeline">
  <li>
    <div class="meeting">AHA Scientific Sessions <strong>2025</strong>, <span class="place">New Orleans, LA</span> <span class="year">2024 (preview)</span></div>
    <em>Coronary Calcium Density Parameters Improve Risk Prediction</em>. Abstract 4372707.
  </li>
  <li>
    <div class="meeting">EPI–Lifestyle <strong>2025</strong>, <span class="place">New Orleans, LA</span></div>
    <em>Extra-Coronary Calcification and Risk of Incident Events</em>.
  </li>
  <li>
    <div class="meeting">AHA Scientific Sessions <strong>2024</strong>, <span class="place">Chicago, IL</span></div>
    <em>Coronary Calcium Density &amp; Volume — Independent Associations</em>.
  </li>
</ul>

<div class="sep"></div>

<!-- =======================
     Selected Research Projects
======================= -->
<h2>Selected Research Projects</h2>

<h3>Proteomics &amp; Valvular Calcification Pipeline (ARIC &amp; MESA)</h3>
<ul>
  <li>Identify protein signatures associated with aortic and mitral valve calcification using 5,000+ biomarkers, control FDR, and replicate across cohorts.</li>
</ul>

<h3>Machine Learning for Coronary Calcium Density</h3>
<ul>
  <li>Elastic net and survival modeling to improve imaging-based risk prediction beyond clinical covariates.</li>
</ul>

<h3>Hypertension Control in Bangladesh</h3>
<ul>
  <li>Analytic framework for medication changes, retention, and BP control trajectories to guide program scale-up.</li>
</ul>

<div class="sep"></div>

<!-- =======================
     Technical Skills
======================= -->
<h2>Technical Skills</h2>
<p><strong>Software:</strong> R (tidyverse, survival, caret), Python, Stata, SQL<br>
<strong>Methods:</strong> Cox, mixed-effects, elastic net, spline regression, competing risk (Fine–Gray)<br>
<strong>Tools:</strong> REDCap, Git, Markdown, GitHub Pages</p>

<div class="sep"></div>

<!-- =======================
     Professional Service
======================= -->
<h2>Professional Service</h2>
<ul>
  <li>Contributor to R package <strong>compareCstat</strong> (CRAN 2025).</li>
  <li>Mentor for junior analysts at the Welch Center.</li>
</ul>

</div>
