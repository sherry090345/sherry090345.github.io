---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=Merriweather:wght@700&display=swap" rel="stylesheet">

<style>
  /* ===== Scoped Home Styles (bigger, clearer) ===== */
  #home{
    --text:#101318;
    --muted:#5e6472;
    --line:rgba(16,19,24,.12);
    --accent:#0b72ff;
    font-family:"Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    color:var(--text);
    font-size:13.5px;             /* larger desktop body */
    line-height:1.7;
    -webkit-text-size-adjust:100%;
  }

  /* headers */
  #home h1,#home h2,#home h3{
    font-size:17px;               /* larger desktop headers */
    line-height:1.35;
    font-weight:800;
    letter-spacing:.2px;
    margin:1.1rem 0 .65rem;
    color:var(--text);
  }

  /* rhythm & links */
  #home p{ margin:.55rem 0 .75rem; }
  #home a{ color:var(--accent); text-decoration:none; border-bottom:1px solid rgba(11,114,255,.28); }
  #home a:hover{ border-bottom-color:var(--accent); }

  /* lists */
  #home ul, #home ol{ margin:.45rem 0 .9rem 1.2rem; }
  #home li{ margin:.28rem 0; }

  /* separators */
  #home .sep{ height:1px; background:var(--line); margin:1.1rem 0; }

  /* journal emphasis */
  #home .journal{ font-family:"Merriweather", Georgia, "Times New Roman", serif; font-weight:700; font-style:italic; }

  /* ---- Publication cards ---- */
  #home .pubs{ display:flex; flex-direction:column; gap:.7rem; }
  #home .pub-card{
    display:grid;
    grid-template-columns: 120px 1fr;   /* thumbnail + content */
    gap:.8rem;
    border:1px solid var(--line);
    border-radius:10px;
    padding:.6rem;
    background:#fbfbfd;
  }
  #home .pub-card .thumb{
    width:120px; height:80px;           /* consistent thumbnail window */
    border-radius:8px; overflow:hidden; background:#f2f2f5;
    display:flex; align-items:center; justify-content:center;
  }
  #home .pub-card .thumb img{
    width:100%; height:100%; object-fit:cover; display:block;
  }
  #home .pub-card .title{
    margin:0 0 .15rem 0; line-height:1.45;
  }
  #home .pub-card .title a{
    color:var(--text); text-decoration:none; border-bottom:1px solid rgba(11,114,255,.25);
  }
  #home .pub-card .title a:hover{ color:var(--accent); border-bottom-color:var(--accent); }
  #home .pub-card .meta{ color:var(--muted); }
  #home .pub-card .authors{ margin-top:.25rem; }

  /* mobile */
  @media (max-width: 680px){
    #home{ font-size:12px; line-height:1.65; }
    #home h1, #home h2, #home h3{ font-size:15px; }
    #home .pub-card{
      grid-template-columns: 100px 1fr;
      padding:.55rem;
    }
    #home .pub-card .thumb{ width:100px; height:70px; }
  }
</style>

<div id="home">

<p>
I am currently a Research Data Coordinator at the Johns Hopkins Welch Center for Prevention, Epidemiology and Clinical Research. I completed my Master of Health Science in Epidemiology at the Johns Hopkins Bloomberg School of Public Health in 2023 and received my Bachelor’s degree in Chemical Biology from Northwest A&amp;F University in China in 2021. My research focuses on cardiovascular epidemiology, particularly biomarker discovery, coronary artery calcium imaging, and proteomic profiling to improve risk prediction and clinical care in aging populations.
</p>

<h2>Education</h2>

<ul>
  <li><strong>MHS in Epidemiology</strong>, Johns Hopkins Bloomberg School of Public Health, USA (2021–2023)<br>
      Thesis: Blood Urea Nitrogen and Incident Heart Failure (ARIC Study)
  </li>
  <li><strong>B.S. in Chemical Biology</strong>, Northwest A&amp;F University, China (2017–2021)<br>
      Thesis: Large-scale Data Analytics for Biopharmaceuticals
  </li>
</ul>

<div class="sep"></div>

<h2>Selected Publication</h2>

<div class="pubs">

  <!-- ARMS -->
  <div class="pub-card">
    <div class="thumb">
      <img src="/images/ARMS.png" alt="ARMS crossover trial figure">
    </div>
    <div class="content">
      <p class="title">
        <a href="https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2824754" target="_blank" rel="noopener">
          Arm Position and Blood Pressure Readings: The ARMS Crossover Randomized Clinical Trial
        </a>, <span class="journal">JAMA Intern Med.</span>
      </p>
      <p class="authors"><strong>Liu H,</strong> Zhao D, Sabit A, Pathiravasan CH, Ishigami J, Charleston J, Miller ER 3rd, Matsushita K, Appel LJ, Brady TM.</p>
    </div>
  </div>

  <!-- BUN & HF -->
  <div class="pub-card">
    <div class="thumb">
      <img src="/images/BUN.jpg" alt="BUN and heart failure illustration">
    </div>
    <div class="content">
      <p class="title">
        <a href="https://www.jstage.jst.go.jp/article/circj/89/10/89_CJ-24-0502/_article" target="_blank" rel="noopener">
          Association of Blood Urea Nitrogen With Incident Heart Failure in the Community — The ARIC Study
        </a>, <span class="journal">Circ J.</span>
      </p>
      <p class="authors"><strong>Liu H,</strong> Ishigami J, Mathews L, Konety S, Hall M, Chang PP, Ndumele C, Rosamond W, Matsushita K.</p>
    </div>
  </div>

  <!-- Noise/Public Setting -->
  <div class="pub-card">
    <div class="thumb">
      <img src="/images/deci.png" alt="Noise and public setting schematic">
    </div>
    <div class="content">
      <p class="title">
        <a href="https://www.acpjournals.org/doi/10.7326/ANNALS-24-00873?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed" target="_blank" rel="noopener">
          Effects of Noise and Public Setting on Blood Pressure Readings: A Randomized Crossover Trial
        </a>, <span class="journal">Ann Intern Med.</span>
      </p>
      <p class="authors">Ishigami J, <strong>Liu H,</strong> Zhao D, Sabit A, Pathiravasan CH, Charleston J, Miller ER 3rd, Matsushita K, Appel LJ, Brady TM.</p>
    </div>
  </div>

  <!-- Lycium barbarum -->
  <div class="pub-card">
    <div class="thumb">
      <img src="/images/goji.png" alt="Lycium barbarum polysaccharide graphic">
    </div>
    <div class="content">
      <p class="title">
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0141813021011934" target="_blank" rel="noopener">
          A homogeneous polysaccharide from <em>Lycium barbarum</em>: Structural characterizations, anti-obesity effects and impacts on gut microbiota
        </a>, <span class="journal">Int J Biol Macromol.</span>
      </p>
      <p class="authors">Yang Y, Chang Y, Wu Y, <strong>Liu H,</strong> Liu Q, Kang Z, Wu M, Yin H, Duan J.</p>
    </div>
  </div>

</div>

<div class="sep"></div>

<h2>Selected Ongoing Projects</h2>

<ul>
  <li><strong>Proteomics and Valvular Calcification (ARIC and MESA studies)</strong><br>
      Analyzing large-scale protein biomarkers to identify pathways associated with aortic and mitral valve calcification.
  </li>
  <li><strong>Machine Learning for Coronary Calcium Density</strong><br>
      Developing prediction models that integrate volume and density metrics to improve risk stratification in older adults.
  </li>
  <li><strong>School Food Environment Policy Evaluation in Nepal</strong><br>
      Assessing trans-fat reduction following municipal healthy food procurement policies using mixed-effects models.
  </li>
  <li><strong>Community-Based Hypertension Control in Bangladesh (CB-HEARTS)</strong><br>
      Evaluating population-level blood pressure control and medication trajectories using longitudinal data.
  </li>
</ul>

</div>
