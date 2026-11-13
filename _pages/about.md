---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

# 👋 About Me {#about-me}

Hi! I’m **Ruijie Niu**, an M.S. student in **Biostatistics at the University of Pittsburgh School of Public Health**.

My research spans causal inference, Bayesian statistical modeling, and collaborative clinical data analysis. I have worked on causal mediation methods involving negative controls, Bayesian factor models for single-cell perturbation data, and statistical analyses of clinical outcomes. I am particularly interested in understanding the assumptions and limitations of statistical methods, investigating unexpected results, and developing approaches that can be useful in biomedical research.

<div style="
  background: #f5f8fc;
  border-left: 4px solid #4d6f91;
  padding: 14px 18px;
  margin: 22px 0 18px 0;
  border-radius: 6px;
  line-height: 1.6;
">
  <strong>🎓 Ph.D. Opportunities — Fall 2027</strong><br>
  I am seeking Ph.D. opportunities for Fall 2027 in biostatistics and related quantitative health sciences.
</div>

---

# 🔬 Research Interests

<div style="margin: 0.6em 0 1.0em 0;">
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Causal Inference and Mediation</span>
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Bayesian and Computational Statistics</span>
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Clinical and Biomedical Applications</span>
</div>

- **Causal Inference and Mediation:** Identification and estimation under unmeasured confounding; negative controls; difference-in-differences ideas; sensitivity to identifying assumptions.

- **Bayesian and Computational Statistics:** Bayesian latent-variable models; high-dimensional biomedical data; single-cell perturbation analysis; posterior computation and stability of statistical discoveries.

- **Clinical and Biomedical Applications:** Survival and longitudinal data analysis; incomplete follow-up; statistical collaboration and interpretation of biomedical evidence.

---

# 🧪 Current Research

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/causal-mediation-negative-controls.png' | relative_url }}" alt="Diagram of causal mediation with negative controls, identification, estimation, and robustness">
  </div>
  <div class="paper-box-text" markdown="1">

## Causal Mediation with Negative Controls and Difference-in-Differences

*University of Pittsburgh · with [Dr. Qiong Wu](https://www.publichealth.pitt.edu/directory/qiong-wu)*

I work with Professor Qiong Wu on causal mediation methods that use negative-control information and difference-in-differences ideas to address unmeasured confounding. My contributions include initial identification derivations, estimator implementation, and simulation-based evaluation for continuous mediators.

In our latest simulation study, we evaluated **ten scenarios with 2,000 Monte Carlo repetitions per scenario**. Under the specified valid assumptions, the negative-control estimators substantially reduced bias, and additional control pairs improved precision. Sensitivity analyses also showed that direct and indirect effects could become substantially biased under model misspecification, even when the total effect remained relatively close to its true value.

I have also implemented a separate systematic-bias calibration study. This work remains ongoing, and an empirical application using GLP-1-related data is being prepared.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/bayesian-factor-models.png' | relative_url }}" alt="Guided sparse factor analysis workflow for single-cell perturbation data">
  </div>
  <div class="paper-box-text" markdown="1">

## Bayesian Factor Modeling and Single-Cell Perturbation Analysis

*University of Pittsburgh School of Medicine · with [Dr. Qiyiwen Zhang](https://people.dom.pitt.edu/people/qiyiwen-zhang-phd)*

I work with Professor Qiyiwen Zhang on Bayesian factor models for high-dimensional genomic data. I began by studying RABFA derivations and reproducing GSFA simulations and single-cell CRISPR analyses.

During reproduction, I investigated repeated factor matching using the Hungarian algorithm and examined discrepancies in weak-effect estimation by comparing alternative posterior summaries. These analyses helped distinguish evaluation-related differences from potential model limitations. Additional experiments across random seeds raised questions about the stability of detected gene sets.

Our ongoing methodological work extends GSFA to model raw count data using a negative binomial likelihood while retaining its perturbation–factor–gene structure. My contributions include model derivations, sampling-code implementation, and simulation comparisons. Preliminary results are encouraging in some settings, although convergence and factor-recovery challenges remain in more complex scenarios.

I am exploring Poisson and Poisson-lognormal formulations and preparing the Methods and Supplementary Materials for this ongoing project.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/oncology-survival-analysis.png' | relative_url }}" alt="Oncology outcomes and time-to-event survival analysis workflow">
  </div>
  <div class="paper-box-text" markdown="1">

## Collaborative Clinical Biostatistics — Oncology

*University of Pittsburgh / UPMC · with [Dr. Hong Wang](https://www.publichealth.pitt.edu/directory/hong-wang)*

I collaborate with clinical investigators on oncology studies involving treatment response and time-to-event outcomes. Working within a statistical research team, I conduct survival analyses, prepare statistical summaries and figures, and deliver reports addressing investigators’ research questions.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/pediatric-diabetes.png' | relative_url }}" alt="Study of cardiometabolic risk after youth-onset type 1 diabetes">
  </div>
  <div class="paper-box-text" markdown="1">

## Collaborative Clinical Biostatistics — Pediatric Endocrinology

*University of Pittsburgh / UPMC · with [Dr. Qiong Wu](https://www.publichealth.pitt.edu/directory/qiong-wu)*

I collaborate on a longitudinal study of cardiometabolic outcomes following type 1 diabetes diagnosis. Working with an initial cohort of 542 patients, I reconciled follow-up records, incorporated corrected and supplemental clinical measurements, and examined missingness and follow-up availability.

I used piecewise linear mixed-effects models to investigate sex-specific changes in BMI z-score and lipid measures over time. The analyses suggested differences in early BMI z-score and HDL-C trajectories but did not provide evidence of sex differences in later slopes.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/foundation-models-critical-care.png' | relative_url }}" alt="Scoping review of foundation models in emergency and critical care">
  </div>
  <div class="paper-box-text" markdown="1">

## Foundation Models in Emergency and Critical Care

*University of Minnesota · with [Dr. Feng Xie](https://cse.umn.edu/datascience/feng-xie)*

I contribute to a scoping review examining the clinical utility of foundation models in emergency and critical care. I independently completed clinical-utility data extraction and classification for all 49 included studies, examining evidence maturity, clinical risk, workflow integration, and reported hallucination or safety-mitigation measures.

I also contributed to the synthesis and manuscript text for the Clinical Utility section.

**Manuscript status:** Under review at JMIR (2026).

  </div>
</div>

---

# 📝 Publications & Research Writing

### Published

- *Vitamin and Mineral Combined in Diabetes: Modulating HbA1c Across Different Demographics.*<br>
  **Niu, R.**, & Xia, J. (2025).<br>
  *Applied and Computational Engineering*, 132, 257–268. [DOI](https://doi.org/10.54254/2755-2721/2024.20798)

- *The Role of Plasma Trace Elements in Hypertension Among Elderly Populations in China: A Cross-Sectional Analysis Using CLHLS Data.*<br>
  **Niu, R.** (2024).<br>
  *Theoretical and Natural Science*, 70, 18–23. [DOI](https://doi.org/10.54254/2753-8818/2024.18203)

### Under Review

- *Mapping the Clinical Utility of Foundation Models in Emergency and Critical Care: A Scoping Review of Decision-Making, Implementation, and Research Gaps.*<br>
  Under review at JMIR, 2026. Contribution: clinical-utility data extraction, synthesis, and manuscript text.

---

# 🎓 Education

- **University of Pittsburgh, School of Public Health**<br>
  M.S. in Biostatistics, expected May 2027<br>
  Pittsburgh, Pennsylvania

- **Xi’an Jiaotong-Liverpool University / University of Liverpool**<br>
  B.Sc. (Hons) in Biomedical Statistics, July 2025<br>
  Suzhou, China

---

# 💼 Selected Experience

- **University of Pittsburgh / UPMC — Clinical Biostatistics**<br>
  **Biostatistics Research Assistant** · November 2025–Present<br>
  Oncology and pediatric endocrinology collaborations.

- **University of Pittsburgh, Biostatistics — Causal Mediation**<br>
  **Student Research Assistant** · January 2026–Present<br>
  Identification, estimation, and simulation for causal mediation with negative controls.

- **University of Pittsburgh, Medicine — Bayesian Factor Modeling**<br>
  **Graduate Research Collaborator** · June 2026–Present<br>
  Bayesian factor models for single-cell perturbation data.

- **Tasly Pharma**

  **Biostatistics Intern / SAS Programmer** · June–September 2024

  Supported Phase II/III clinical-study workflows through SAS programming, clinical-data cleaning and validation, endpoint derivation, and review of statistical analysis and reporting materials.

- **Tianjin Fourth Center Hospital**

  **Medical Records / Information Intern** · July–August 2023

  Worked with hospital information and medical-record workflows, including patient-document access, data verification, reporting support, and medication-information services.

---

# 🌱 A Little Beyond Statistics

***I do, fortunately, have a life outside R. This is probably healthy for both me and R.***

😂 Because I grew up in Tianjin, I feel a mild civic obligation to make conversations at least a little funny.

🌿 Since moving to Pennsylvania, I have also discovered that I like hiking—as long as nobody interprets “hiking” too aggressively. Streams, rocks, fresh air, flowers, birds, squirrels, chipmunks, deer, and suspicious-looking mushrooms are all welcome. Heroic elevation gain is optional.

🎶 Music has followed me through several phases of life. I grew up playing piano and erhu, spent years in a Chinese orchestra, later joined a choir, and still have a soft spot for choral music and musicals.

⚽ I have been a Lionel Messi fan since childhood. Since moving to the U.S., I have also been learning American sports one stadium—and occasionally one confusing rule—at a time.

🕵️ I have loved detective stories and logic puzzles since I was a kid. Sherlock Holmes was probably my first intellectual hero. I am not claiming that this caused my interest in causal inference, but the resemblance between “who actually caused what?” and “who actually did it?” has not escaped me.

🍳 I also enjoy cooking and baking, especially when I can reproduce something I have been craving and then feed it to other people. Cooking has one major methodological advantage over research: the feedback is usually much faster, and the output is often edible.

🍦 I remain firmly pro–mint chocolate ice cream. If it tastes like toothpaste, perhaps toothpaste simply borrowed an excellent flavor.

📸 I love portrait photography and styling. I enjoy choosing an outfit for a location, thinking about composition, and turning the whole thing into a visual idea. I plan travel outfits with a level of detail that would probably be excessive if I did not enjoy it so much.

🔮 I also have a statistically questionable hobby: tarot, Lenormand, and a little Chinese astrology, mostly for entertaining friends. I keep the confidence intervals elsewhere.

---

<small>
Last updated November 2026 · Pittsburgh, PA
</small>
