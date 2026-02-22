---
show: true
width: 8
date: 2025-01-13 00:01:00 +0800
---
<div class="p-4">
  <h2>Academic Highlights</h2>
  <hr />

  <div class="grid3">
    <!-- =======================
         Conference Presentations (LEFT, scrollable)
         ======================= -->
    <section class="card talks">
      <h3>Conference Presentations</h3>
      <div class="muted">Selected talks &amp; workshop presentations</div>
      <!-- Scroll area -->
      <div class="scrollbox">
        <div class="item">
          <div class="title">Learning Robust Treatment Rules for Censored Data</div>
          <div class="meta">June 2025 · Zhuhai</div>
          <div class="desc">International Chinese Statistical Association China Conference 2025 (ICSA 2025)</div>
        </div>
        <div class="item">
          <div class="title">Community Detection in Multilayer Networks with Complex Inhomogeneity</div>
          <div class="meta">June 2025 · Tokyo</div>
          <div class="desc">The 2025 Workshop on Statistical Network Analysis and Beyond (SNAB 2025)</div>
        </div>
        <div class="item">
          <div class="title">Proxy-aided Demand Learning with an Application on Various Pricing Problems</div>
          <div class="meta">July 2024 · Beijing</div>
          <div class="desc">7th International Conference on Econometrics and Statistics (EcoSta 2024)</div>
        </div>
        <div class="item">
          <div class="title">Proxy-aided Demand Learning with an Application on Various Pricing Problems</div>
          <div class="meta">June 2024 · Wuhan</div>
          <div class="desc">International Chinese Statistical Association China Conference 2024 (ICSA 2024)</div>
        </div>
        <div class="item">
          <div class="title">Optimal Individualized Decision-Making with Proxies</div>
          <div class="meta">June 2023 · Chengdu</div>
          <div class="desc">International Chinese Statistical Association China Conference 2023 (ICSA 2023)</div>
        </div>
        <div class="item no-border">
          <div class="title">Learning Optimal Treatment Regime with Proxies</div>
          <div class="meta">December 2022 · London</div>
          <div class="desc">15th International Conference of the ERCIM WG on Computational and Methodological Statistics (CMStatistics 2022)</div>
        </div>
      </div>
    </section>
    <!-- =========
         Teaching (MIDDLE)
         ========= -->
    <section class="card teach">
      <h3>Teaching</h3>
      <div class="muted">Teaching assistant roles</div>
      <div class="mini">
        <div class="title">Tutor for ST3131: Applied Regression Analysis</div>
        <div class="meta">Spring 2025</div>
      </div>
      <div class="mini">
        <div class="title">Student Helper for ST5188: Advanced Data Science Project</div>
        <div class="meta">Spring 2025</div>
      </div>
      <div class="mini">
        <div class="title">Student Helper for ST5188: Advanced Data Science Project</div>
        <div class="meta">Fall 2024</div>
      </div>
      <div class="mini">
        <div class="title">Tutor for ST2334: Probability and Statistics</div>
        <div class="meta">Spring 2024</div>
      </div>
      <div class="mini">
        <div class="title">Student Helper for ST5188: Statistical Research Project</div>
        <div class="meta">Spring 2024</div>
      </div>
      <div class="mini">
        <div class="title">Student Helper for ST5188: Statistical Research Project</div>
        <div class="meta">Fall 2023</div>
      </div>
    </section>
    <!-- =======
         Service (RIGHTMOST)
         ======= -->
    <section class="card serv">
      <h3>Service</h3>
      <div class="muted">Peer review &amp; community support</div>
      <ul class="plain">
        <li>Reviewer for NeurIPS</li>
        <li>Reviewer for <i>Biostatistics &amp; Epidemiology</i></li>
        <li>Reviewer for <i>Biometrical Journal</i></li>
        <li>Reviewer for <i>American Journal of Epidemiology</i></li>
      </ul>
    </section>
  </div>
</div>

<style>
  /* 3 columns: talks | teaching | service */
  .grid3{
    margin-top: 14px;
    display: grid;
    gap: 14px;
    grid-template-columns: 2fr 1fr 1fr;
    grid-template-areas: "talks teach serv";
    align-items: start;
  }
  .talks{ grid-area: talks; }
  .teach{ grid-area: teach; }
  .serv{ grid-area: serv; }

  /* Tablet: talks full width, then teaching + service */
  @media (max-width: 1100px){
    .grid3{
      grid-template-columns: 1fr 1fr;
      grid-template-areas:
        "talks talks"
        "teach serv";
    }
  }

  /* Mobile: stack */
  @media (max-width: 700px){
    .grid3{
      grid-template-columns: 1fr;
      grid-template-areas:
        "talks"
        "teach"
        "serv";
    }
  }

  .card{
    background: #fff;
    border: 1px solid #e5e7eb;
    border-radius: 14px;
    padding: 14px 14px 12px;
    box-shadow: 0 8px 24px rgba(17,24,39,.06);
  }
  .card h3{
    margin: 0 0 6px;
    font-size: 16px;
    color: #2c3e50;
  }
  .muted{
    color: #6b7280;
    font-size: 13px;
    margin-bottom: 10px;
  }

  /* Scroll wheel inside presentations */
  .scrollbox{
    max-height: 68vh;         /* adjust: 60–75vh depending on taste */
    overflow-y: auto;
    padding-right: 6px;       /* space for scrollbar */
    overscroll-behavior: contain;
    -webkit-overflow-scrolling: touch;
    scrollbar-gutter: stable;
  }

  .item{ padding: 10px 0; border-bottom: 1px dashed #e5e7eb; }
  .item.no-border{ border-bottom: none; }

  .mini{ padding: 10px 0; border-bottom: 1px dashed #e5e7eb; }
  .mini:last-child{ border-bottom: none; }

  .title{ font-weight: 700; color: #1a5276; font-size: 14px; line-height: 1.25; }
  .meta{ margin-top: 3px; color: #6b7280; font-style: italic; font-size: 12.5px; }
  .desc{ margin-top: 4px; color: #374151; font-size: 13.5px; line-height: 1.35; }

  .plain{ margin: 8px 0 0; padding-left: 18px; color: #374151; }
  .plain li{ margin: 6px 0; }
</style>




