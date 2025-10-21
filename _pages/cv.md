---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
classes: cv-page
---

{% include base_path %}

<!-- ===== CV Styles (scoped) ===== -->
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=Merriweather:wght@700&display=swap" rel="stylesheet">

<style>
.cv-page{
  --text:#0f1220;
  --muted:#616979;
  --line:rgba(15,18,32,.12);
  --accent:#0b72ff;
  --bg-pill:#f2f6ff;
  --bd-pill:#cfe0ff;
  font-family:"Inter",system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  color:var(--text);
  font-size:13.5px;
  line-height:1.7;
}
.cv-page h2{
  font:800 20px/1.3 "Inter";
  margin:1.2rem 0 .5rem;
}
.cv-page h3{
  font:800 15px/1.35 "Inter";
  margin:.9rem 0 .35rem;
}
.cv-page .kicker{
  display:inline-block;
  font:800 12px/1 "Inter";
  letter-spacing:.18em;
  text-transform:uppercase;
  color:var(--accent);
  background:linear-gradient(90deg,#eaf2ff,transparent 70%);
  padding:.36rem .55rem .3rem;
  border-radius:999px;
  border:1px solid var(--bd-pill);
}
.cv-page .section{ margin:1.2rem 0 1.1rem; }
.cv-page .sep{ height:2px; background:var(--line); margin:1rem 0 1rem; border-radius:2px; }

/* two-column lists where useful */
.cv-page .twocol {
  display:grid; grid-template-columns:repeat(2,minmax(0,1fr)); gap:.6rem 1rem;
}
@media (max-width: 820px){ .cv-page .twocol{ grid-template-columns:1fr; } }

/* item blocks */
.cv-page .item{ padding:.5rem 0 .45rem; border-bottom:1px solid var(--line); }
.cv-page .item:last-child{ border-bottom:none; }
.cv-page .meta{ color:var(--muted); }

/* publication style */
.cv-page .ref-list{ list-style:none; margin:0; padding:0; }
.cv-page .ref-item{ padding:.6rem 0; border-bottom:1px dashed var(--line); }
.cv-page .ref-item:last-child{ border-bottom:none; }
.cv-page .title a{ color:var(--text); text-decoration:none; border-bottom:1px solid rgba(11,114,255,.28); }
.cv-page .title a:hover{ border-bottom-color:var(--accent); color:var(--accent); }
.cv-page .journal{ font-family:"Merriweather",Georgia,"Times New Roman",serif; font-weight:700; font-style:italic; }
.cv-page .me{ font-weight:800; background:linear-gradient(transparent 70%, rgba(11,114,255,.15) 0); padding:0 .02em; }

/* badges */
.cv-page .badge{
  display:inline-block; font:700 11px/1 "Inter"; color:var(--accent);
  background:var(--bg-pill); border:1px solid var(--bd-pill);
  padding:.38rem .55rem; border-radius:999px; margin-left:.4rem;
}
.cv-page .chips{ display:flex; flex-wrap:wrap; gap:.35rem; margin-top:.3rem; }
.cv-page .chip{ font:600 11px/1 "Inter"; color:#1e2732; background:#f7f9ff; border:1px solid #e3ecff; padding:.38rem .55rem; border-radius:999px; }

/* timeline for conferences */
.cv-page .timeline{ list-style:none; margin:0; padding:0; }
.cv-page .timeline li{ padding:.55rem 0; border-left:3px solid var(--line); margin-left:.65rem; position:relative; }
.cv-page .timeline li::before{
  content:""; position:absolute; left:-7px; top:.8rem; width:10px; height:10px; border-radius:50%; background:var(--accent);
  box-shadow:0 0 0 3px #eaf2ff;
}

/* compact lists */
.cv-page ul{ margin:.4rem 0 .8rem 1.2rem; }
.cv-page li{ margin:.25rem 0; }

/* link look */
.cv-page a{ color:var(--accent); text-decoration:none; border-bottom:1px solid rgba(11,114,255,.28); }
.cv-page a:hover{ border-bottom-color:var(--accent); }

</style>

<div class="cv-page">

<!-- =====================
     EDUCATION
===================== -->
<div class="section">
  <span class="kicker">Education</span>
  <h2>Degrees</h2>

  <div class="item">
    <strong>MHS in Epidemiology</strong>, Johns Hopkins University, Baltimore, USA <span class="meta">Aug 2021 – May 2023</span><br>
    <em>Thesis:</em> The association of blood urea nitrogen with incident heart failure in the community (ARIC Study).<br>
    <em>Coursework:</em> Statistical machine learning, Causal inference, Analysis of Longitudinal Data, Data Science for Public Health, Molecular Epidemiology & Biomarkers in Public Health, etc.
  </div>

  <div class="item">
    <strong>B.S. in Chemical Biology</strong>, Northwest A&F University, Yangling, China <span class="meta">Sep 2017 – Jun 2021</span><br>
    <em>Thesis:</em> Large-scale Data Analytics for Biopharmaceuticals.<br>
    <em>Coursework:</em> Linear Algebra I, Probability Theory, Chemical Biology, Proteins and Enzymes, etc.
  </div>
</div>

<div class="sep"></div>

<!-- =====================
     WORK EXPERIENCE
===================== -->
<div class="section">
  <span class="kicker">Experience</span>
  <h2>Professional & Research Positions</h2>

  <div class="item">
    <strong>Research Data Coordinator</strong> <span class="meta">08/2023 – Present · Full-time</span><br>
    Johns Hopkins Welch Center for Prevention, Epidemiology, and Clinical Research, Baltimore, MD<br>
    • Data analysis across proteomics/biomarkers, nutrition surveys, hypertension control, peripheral artery disease, and more.<br>
    • Reproducible pipelines in R/Python for cohort studies and clinical trials; manuscript/abstract support.
  </div>

  <div class="item">
    <strong>Research Assistant</strong> <span class="badge">Remote</span> <span class="meta">05/2025 – Present · Part-time</span><br>
    Vanke School of Public Health, Tsinghua University, Beijing, China<br>
    • Lead analyses using Chinese perinatal survey data on maternal nutrition and environmental exposures.<br>
    • Manuscript preparation and interpretation for perinatal outcomes.
  </div>

  <div class="item">
    <strong>Student Teaching Assistant</strong> <span class="meta">2022 – 2023</span><br>
    Johns Hopkins Bloomberg School of Public Health, Baltimore, MD<br>
    • Principles of Clinical Epidemiology (Oct–Dec 2022; Mar 2023), Methods and Applications of Cohort Studies (Mar 2023). Tutoring and grading for ~20 students per class.
  </div>

  <div class="item">
    <strong>Student Research Assistant</strong> <span class="meta">04/2022 – 05/2023 · Part-time</span><br>
    Johns Hopkins Bloomberg School of Public Health, Baltimore, MD<br>
    • Covidence-based reviews on COVID-19 disruptions to diabetes/hypertension care in LAC region.<br>
    • Survival analyses for ARIC visit 1 and surveillance data.
  </div>

  <div class="item">
    <strong>Student Research Assistant</strong> <span class="meta">06/2019 – 06/2021 · Part-time</span><br>
    Northwest A&F University, Yangling, Shaanxi, China<br>
    • Laboratory and analytical support across natural products and microbiome projects.
  </div>

  <div class="item">
    <strong>Undergraduate Intern</strong> <span class="meta">01/2020 – 03/2020 · Full-time</span><br>
    Research Center for Eco-Environmental Sciences, Chinese Academy of Sciences, Beijing, China<br>
    • Synthesized Au-Pd nano-level catalysts for pollutant adsorption; contributed to ACS ES&T Engineering publication.
  </div>
</div>

<div class="sep"></div>

<!-- =====================
     RESEARCH EXPERIENCE
===================== -->
<div class="section">
  <span class="kicker">Research</span>
  <h2>Focus Areas & Ongoing Projects</h2>

  <h3>Biomarker</h3>
  <ul>
    <li><strong>Coronary artery calcification & cardiovascular outcomes — machine learning</strong><br>
        Build prediction models on CAC density and volume using elastic net and random forest; quantify gains over clinical baselines via discrimination and reclassification; account for competing risk with Fine–Gray.</li>
    <li><strong>Proteomics & valvular calcification (ARIC & MESA)</strong><br>
        Discovery in ARIC and replication in MESA to identify proteins linked to aortic/mitral calcification; multiple-testing control, pathway summaries, and incremental prediction.</li>
    <li><strong>Valvular calcification & valvular dysfunction</strong><br>
        CT-derived calcification related to echocardiographic function (e.g., aortic stenosis) using spline-based linear/logistic models; AUC, calibration, and sensitivity checks.</li>
  </ul>

  <h3>Nutrition</h3>
  <ul>
    <li><strong>Healthy food procurement — Nepal school survey</strong><br>
        LMM, mixed-effects logistic, and CLMM to evaluate pre- to post-policy changes in food environments; policy-ready summaries and visuals.</li>
    <li><strong>Low-sodium salt substitute — Bangladesh trial (antihypertensive users)</strong><br>
        Questionnaire design, REDCap build and documentation; feasibility and safety monitoring to inform implementation.</li>
    <li><strong>Low-sodium salt substitute — research prioritization</strong><br>
        Priority-setting survey across stakeholders; synthesize responses and co-write research roadmap.</li>
    <li><strong>Natural product polysaccharides & microbiome</strong><br>
        Effects of botanical polysaccharides (e.g., goji berry, angelica sinensis) on microbiome and metabolic outcomes; published in <span class="journal">Int J Biol Macromol</span>.</li>
  </ul>

  <h3>Hypertension</h3>
  <ul>
    <li><strong>Arm position & blood pressure — randomized crossover</strong><br>
        Paired t-test and LMM to quantify measurement error from positioning; published in <span class="journal">JAMA Intern Med</span>.</li>
    <li><strong>Public setting & noise effects on blood pressure</strong><br>
        Crossover analyses of ambient noise/public environment; published in <span class="journal">Ann Intern Med</span>.</li>
    <li><strong>Community-based HEARTS pilot — Bangladesh</strong><br>
        Medication changes, retention, BP control, and trajectories; analysis and reporting for scale-up.</li>
  </ul>

  <h3>Peripheral Artery Disease</h3>
  <ul>
    <li><strong>PAD in Hispanics — prevalence & risk factors</strong><br>
        Multimodality estimates with stratified/interaction analyses; subgroup outputs for clinical relevance.</li>
    <li><strong>New PAD diagnostic criteria — validity</strong><br>
        Compare sensitivity, specificity, and agreement against existing thresholds; ROC-based metrics and guidance on cut-points.</li>
    <li><strong>KDIGO kidney measures & PAD outcomes</strong><br>
        Independent and interaction effects using KDIGO categories; stratified/interaction models with clear effect displays.</li>
  </ul>
</div>

<div class="sep"></div>

<!-- =====================
     PUBLICATIONS
===================== -->
<div class="section">
  <span class="kicker">Publications</span>
  <h2>Peer-reviewed Articles</h2>

  <ol class="ref-list">
    <li class="ref-item">
      <span class="authors"><span class="me">Liu H</span>, Zhao D, Sabit A, Pathiravasan CH, Ishigami J, Charleston J, Miller ER 3rd, Matsushita K, Appel LJ, Brady TM.</span><br>
      <span class="title"><a href="https://doi.org/10.1001/jamainternmed.2024.5213" target="_blank" rel="noopener">Arm Position and Blood Pressure Readings: The ARMS Crossover Randomized Clinical Trial</a></span>. <span class="journal">JAMA Intern Med</span>. 2024 Oct 7:e245213.
    </li>

    <li class="ref-item">
      <span class="authors"><span class="me">Liu H</span>, Ishigami J, Mathews L, Konety S, Hall M, Chang PP, Ndumele C, Rosamond W, Matsushita K.</span><br>
      <span class="title"><a href="https://doi.org/10.1253/circj.CJ-24-0502" target="_blank" rel="noopener">Association of Blood Urea Nitrogen With Incident Heart Failure in the Community — The ARIC Study</a></span>. <span class="journal">Circ J</span>. 2024 Dec 12.
    </li>

    <li class="ref-item">
      <span class="authors">Ishigami J, <span class="me">Liu H</span>, Zhao D, Sabit A, Pathiravasan CH, Charleston J, Miller ER 3rd, Appel LJ, Brady TM.</span><br>
      <span class="title"><a href="https://doi.org/10.7326/ANNALS-24-00873" target="_blank" rel="noopener">Effects of Noise and Public Setting on Blood Pressure Readings — A Randomized Crossover Trial</a></span>. <span class="journal">Ann Intern Med</span>. 2025 Feb;178(2):149-156.
    </li>

    <li class="ref-item">
      <span class="authors">Zou S, <span class="me">Liu H</span>, Mok Y, Gami A, Chen LY, Budoff M, Blaha MJ, Matsushita K.</span><br>
      <span class="title"><a href="https://doi.org/10.1016/j.jcmg.2025.05.014" target="_blank" rel="noopener">Calcified Coronary Lesion Number and Risk of Cardiovascular Disease in the 75-and-Older Population — The ARIC Study</a></span>. <span class="journal">JACC Cardiovasc Imaging</span>. 2025 Jul 3:S1936-878X(25)00270-0.
    </li>

    <li class="ref-item">
      <span class="authors">Yang Y, Chang Y, Wu Y, <span class="me">Liu H</span>, Liu Q, Kang Z, Wu M, Yin H, Duan J.</span><br>
      <span class="title"><a href="https://doi.org/10.1016/j.ijbiomac.2021.05.209" target="_blank" rel="noopener">A homogeneous polysaccharide from Lycium barbarum — Structural characterizations, anti-obesity effects and impacts on gut microbiota</a></span>. <span class="journal">Int J Biol Macromol</span>. 2021 Jul 31;183:2074-2087.
    </li>

    <li class="ref-item">
      <span class="authors">Yuan A, Zhao H, Shan W, Sun JF, Deng J, <span class="me">Liu H</span>, Liu R, Liu JF.</span><br>
      <span class="title"><a href="https://doi.org/10.1021/acsestengg.1c00108" target="_blank" rel="noopener">The Binding Strength of Reactive H* — A Neglected Key Factor in Rh-Catalyzed Environmental Hydrodefluorination Reaction</a></span>. <span class="journal">ACS ES&amp;T Engineering</span>. 2021;1(6):1036-1045.
    </li>

    <li class="ref-item">
      <span class="authors">Ogungbe O, Jabakhanji SB, Mehta R, McCaffrey J, Byrne D, Hurley S, Rosman L, Bansah EC, Ibukun F, Quarshie IA, Lord K, Lu Y, Wang Y, Rayani A, <span class="me">Liu H</span>, Joseph A, Escobosa A, Nyamuame I, Lee J, Meng N, Jehanzeb I, Akinyemi T, Nohara S, Mediano MFF, Yeboah-Kordieh Y, de Sousa C, Farhat J, de Mello RB, Taeed T, Appel LJ, Angell SY, Gregg EW, Matsushita K.</span><br>
      <span class="title"><a href="https://doi.org/10.1186/s12913-025-12760-3" target="_blank" rel="noopener">Disruption to diabetes and hypertension care during the COVID-19 pandemic in Latin America and the Caribbean and mitigation approaches — a scoping review</a></span>. <span class="journal">BMC Health Serv Res</span>. 2025 May 8;25(1):660.
    </li>
  </ol>

  <h3>Statistical Package</h3>
  <div class="item">
    <span class="authors"><span class="me">Liu H</span>, et&nbsp;al.</span>
    <span class="title"><a href="https://doi.org/10.32614/CRAN.package.compareCstat" target="_blank" rel="noopener">compareCstat — Compare C-Statistics (Concordance) Between Survival Models</a></span>. <span class="journal">CRAN</span>. R package, 2025 Jun.
  </div>
</div>

<div class="sep"></div>

<!-- =====================
     ABSTRACTS & CONFERENCES
===================== -->
<div class="section">
  <span class="kicker">Conferences</span>
  <h2>Abstracts & Presentations</h2>

  <ul class="timeline">
    <li>
      <strong>AHA Scientific Sessions 2025</strong>, New Orleans, LA <span class="meta">2024 (program year labeling)</span><br>
      Poster — <em>Coronary Calcium Density Parameters Improve Cardiovascular Risk Prediction beyond Agatston Score in Adults 75 and Older (ARIC)</em>. Abstract 4372707.
    </li>
    <li>
      <strong>EPI–Lifestyle 2025</strong>, New Orleans, LA <span class="meta">2025</span><br>
      Poster — <em>Extra-Coronary Calcification and Risk of Incident CVD in Adults 75 and Older (ARIC)</em>. <span class="journal">Circulation</span>. 2025;151(Suppl 1).
    </li>
    <li>
      <strong>AHA Scientific Sessions 2024</strong>, Chicago, IL <span class="meta">2024</span><br>
      Moderate Digital Poster — <em>Independent Associations of Coronary Calcium Density and Volume with Incident Cardiovascular Events in Adults 75+ (ARIC)</em>. <span class="journal">Circulation</span>. 2024;150(Suppl 1):A4141338.<br>
      Moderate Digital Poster — <em>Prevalence and Risk Factors of PAD Identified by Multimodalities in Hispanics</em>. <span class="journal">Circulation</span>. 2024;150(Suppl 1):A4144462.<br>
      Poster — <em>Coronary Calcified Plaque Number and CVD Risk in Adults 75+ (ARIC)</em>. <span class="journal">Circulation</span>. 2024;150(Suppl 1):A4141410.
    </li>
    <li>
      <strong>EPI–Lifestyle 2024</strong>, Chicago, IL <span class="meta">2024</span><br>
      Moderate Poster — <em>Effects of Arm Position and Support on the Accuracy of Blood Pressure Readings: The ARMS Trial</em>. <span class="journal">Circulation</span>. 2024;149(Suppl 1):MP08.<br>
      Poster — <em>Effects of Environment and Noise on Blood Pressure Readings: The Decibel(s) Trial</em>. <span class="journal">Circulation</span>. 2024;149(Suppl 1):P319.<br>
      Poster — <em>Disruptions to Diabetes and Hypertension Care During COVID-19 and Recovery Approaches in LAC</em>. <span class="journal">Circulation</span>. 2024;149(Suppl 1):P153.
    </li>
    <li>
      <strong>Hypertension Scientific Sessions 2024</strong>, Chicago, IL <span class="meta">2024</span><br>
      Poster — <em>Diagnosis and Treatment of Hypertension by Non-Physician Health Workers under Remote Supervision (CB-HEARTS pilot)</em>. <span class="journal">J Hypertens</span>. 2024;42(Suppl 3):e68.
    </li>
    <li>
      <strong>EPI–Lifestyle 2023</strong>, Boston, MA <span class="meta">2023</span><br>
      Poster — <em>The Association of Blood Urea Nitrogen with Incident Heart Failure (ARIC)</em>. <span class="journal">Circulation</span>. 2023;147(Suppl 1):P176.
    </li>
  </ul>
</div>

<div class="sep"></div>

<!-- =====================
     IN PROGRESS
===================== -->
<div class="section">
  <span class="kicker">Works in progress</span>
  <h2>In Progress</h2>

  <div class="item"><strong>Machine learning to improve risk prediction with CAC density in adults 75+</strong>. <span class="meta">Manuscript</span></div>
  <div class="item"><strong>Association between large-scale proteomics and valvular calcification (ARIC)</strong>. <span class="meta">Manuscript</span></div>
  <div class="item"><strong>Trans-fat elimination guidance in school healthy food procurement (Nepal)</strong>. <span class="meta">Abstract</span></div>
  <div class="item"><strong>New peripheral artery disease diagnostic criteria — validity</strong>. <span class="meta">Manuscript</span></div>
  <div class="item"><strong>Kidney measures and PAD identified by multimodalities in Hispanics</strong>. <span class="meta">Manuscript</span></div>
  <div class="item"><strong>Prevalence and risk factors of PAD identified by multimodalities in Hispanics</strong>. <span class="meta">Manuscript</span></div>
  <div class="item"><strong>CT-derived aortic/mitral valvular calcification & echo function (ARIC)</strong>. <span class="meta">Manuscript</span></div>
  <div class="item"><strong>Community-Based HEARTS to control hypertension in Bangladesh</strong>. <span class="meta">Abstract</span></div>
  <div class="item"><strong>Low-sodium salt substitute and serum potassium among hypertensive patients</strong>. <span class="meta">In preparation</span></div>
</div>

<div class="sep"></div>

<!-- =====================
     CERTIFICATES & SKILLS
===================== -->
<div class="section">
  <span class="kicker">Credentials</span>
  <h2>Certificates</h2>
  <div class="twocol">
    <div class="item">Pharmacoepidemiology and Drug Safety — Johns Hopkins University</div>
    <div class="item">CS50: Introduction to Computer Science — Harvard University</div>
  </div>

  <h2>Skills & Exams</h2>
  <div class="item">
    <strong>Software</strong> — R, Python, SQL, Stata, REDCap
    <div class="chips">
      <span class="chip">tidyverse</span><span class="chip">survival</span><span class="chip">caret</span><span class="chip">git</span>
    </div>
  </div>
  <div class="item">
    <strong>TOEFL</strong> — 105 <span class="meta">(R 27, L 28, S 25, W 25)</span>
  </div>
  <div class="item">
    <strong>GRE</strong> — 324 <span class="meta">(Q 167, V 157, AWA 4.0)</span>
  </div>
</div>

</div>
