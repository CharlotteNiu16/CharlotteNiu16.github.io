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

My work sits at the intersection of **causal inference, clinical biostatistics, and biomedical data science**. I am broadly interested in statistical problems motivated by real clinical and biomedical questions, especially when the answer is difficult to recover from observed data alone.

My current research includes methodological work on causal mediation with negative controls, Bayesian modeling for high-dimensional biomedical data, and collaborative statistical analyses in oncology and pediatric endocrinology.

<div style="
  background: #f5f8fc;
  border-left: 4px solid #4d6f91;
  padding: 14px 18px;
  margin: 22px 0 18px 0;
  border-radius: 6px;
  line-height: 1.6;
">
  <strong>🎓 Ph.D. Opportunities — Fall 2027</strong><br>
  I am currently seeking Ph.D. opportunities in <strong>biostatistics and related quantitative health fields</strong>. If you think our research interests overlap, I would be very happy to connect and introduce myself.
</div>

[**Curriculum Vitae**](/cv/)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**Email**](mailto:run30@pitt.edu)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**GitHub**](https://github.com/CharlotteNiu16)

---

# 🔬 Research Interests

<div style="margin: 0.6em 0 1.0em 0;">
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Causal Inference</span>
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Clinical Biostatistics</span>
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Biomedical Data Science</span>
  <span style="display:inline-block; background:#e8f0fb; color:#2b5a95; padding:6px 12px; border-radius:999px; margin:4px 8px 4px 0; font-size:0.95em; font-weight:600;">Statistical Methodology</span>
</div>

<div style="
  background:#f7f9fc;
  border-left:4px solid #b8cbe3;
  padding:16px 18px;
  border-radius:8px;
  margin: 0 0 1.2em 0;
  line-height:1.7;
">
  I am especially interested in statistical questions where the scientific problem is easy to state but difficult to answer from observed data. In particular, I am drawn to settings where methods must balance <strong>identification, robustness, interpretability, and practical usefulness</strong>.
</div>

- <strong>Causal inference under unmeasured confounding.</strong><br>
  How can we identify and estimate meaningful causal effects when important confounders are not fully observed? What kinds of negative-control or design-based information can help?

- <strong>Statistical methods for real clinical questions.</strong><br>
  How can statistical analyses remain both methodologically rigorous and clinically interpretable, especially in observational studies and time-to-event settings?

- <strong>High-dimensional biomedical data.</strong><br>
  How can Bayesian or other structured statistical methods improve feature recovery, latent structure discovery, and downstream interpretation in single-cell and other high-dimensional biological data?

- <strong>When methods work—and when they do not.</strong><br>
  I am particularly interested in understanding why a method performs well in one setting but fails in another, and what that reveals about assumptions, robustness, and practical deployment.

---

# 🧪 Current Research

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/causal-mediation-negative-controls.png' | relative_url }}" alt="Diagram of causal mediation with negative controls, identification, estimation, and robustness">
  </div>
  <div class="paper-box-text" markdown="1">

## Causal Mediation with Negative Controls and Difference-in-Differences

*University of Pittsburgh · with [Dr. Qiong Wu](https://www.publichealth.pitt.edu/directory/qiong-wu)*

I study causal mediation in settings with unmeasured confounding, focusing on how negative-control information and related difference-in-differences structures can support identification and estimation of direct and indirect effects.

My work includes methodological derivations, estimator implementation, and simulation-based evaluation. In the latest formal study, I evaluated **27 scenarios across 27,000 Monte Carlo replications** to examine robustness, interval coverage, and failure under different assumptions.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/bayesian-factor-models.png' | relative_url }}" alt="Guided sparse factor analysis workflow for single-cell perturbation data">
  </div>
  <div class="paper-box-text" markdown="1">

## Bayesian Factor Models for High-Dimensional Biomedical Data

*University of Pittsburgh School of Medicine · with [Dr. Qiyiwen Zhang](https://people.dom.pitt.edu/people/qiyiwen-zhang-phd)*

I am studying Bayesian latent-factor methods for high-dimensional biomedical data, with an initial focus on **guided sparse factor analysis (GSFA)** for single-cell perturbation studies.

My current work centers on reproducing and benchmarking GSFA on real and simulated data, understanding its practical behavior, and using those results to motivate further methodological development.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/oncology-survival-analysis.png' | relative_url }}" alt="Oncology outcomes and time-to-event survival analysis workflow">
  </div>
  <div class="paper-box-text" markdown="1">

## Collaborative Clinical Biostatistics — Oncology

*University of Pittsburgh / UPMC · with [Dr. Hong Wang](https://www.publichealth.pitt.edu/directory/hong-wang)*

I collaborate with clinical investigators on oncology studies involving response and time-to-event outcomes. My work includes analysis-dataset and endpoint construction, survival analysis, statistical summaries, and investigator-facing reporting.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/pediatric-diabetes.png' | relative_url }}" alt="Study of cardiometabolic risk after youth-onset type 1 diabetes">
  </div>
  <div class="paper-box-text" markdown="1">

## Collaborative Clinical Biostatistics — Pediatric Endocrinology

*University of Pittsburgh / UPMC · with [Dr. Qiong Wu](https://www.publichealth.pitt.edu/directory/qiong-wu)*

I analyze sex differences in cardiometabolic risk following youth-onset type 1 diabetes, with work spanning cohort construction, missing-data and attrition assessment, logistic regression, and interaction analyses.

The project has given me experience translating a clinical question into an interpretable statistical analysis using longitudinal patient data.

  </div>
</div>

<div class="paper-box research-card">
  <div class="paper-box-image">
    <img src="{{ '/images/research/foundation-models-critical-care.png' | relative_url }}" alt="Scoping review of foundation models in emergency and critical care">
  </div>
  <div class="paper-box-text" markdown="1">

## Foundation Models in Emergency and Critical Care

*University of Minnesota · with [Dr. Feng Xie](https://cse.umn.edu/datascience/feng-xie)*

I contribute to a scoping review on the clinical utility, decision-making role, implementation, and research gaps of foundation models in emergency and critical care.

The review synthesizes **49 eligible studies** under PRISMA-ScR / JBI guidance and has been submitted to *Critical Care*.

  </div>
</div>

---

# 📝 Publications & Research Writing

### Published

- **Niu, R.**, & Xia, J. (2025).<br>
  *Vitamin and Mineral Combined in Diabetes: Modulating HbA1c Across Different Demographics.*<br>
  Applied and Computational Engineering, 132, 257–268.

- **Niu, R.** (2024).<br>
  *The Role of Plasma Trace Elements in Hypertension Among Elderly Populations in China: A Cross-Sectional Analysis Using CLHLS Data.*<br>
  Theoretical and Natural Science, 70, 18–23.

### Submitted

- *Mapping the Clinical Utility of Foundation Models in Emergency and Critical Care: A Scoping Review of Decision-Making, Implementation, and Research Gaps.*<br>
  Co-author. Submitted to *Critical Care*, 2026.

---

# 🎓 Education

- **University of Pittsburgh**<br>
  M.S. in Biostatistics, expected May 2027<br>
  Pittsburgh, Pennsylvania

- **Xi’an Jiaotong-Liverpool University / University of Liverpool**<br>
  B.S. in Biomedical Statistics, Honours, 2025<br>
  Suzhou, China

---

# 💼 Selected Experience

- **University of Pittsburgh / UPMC**

  **Biostatistics Research Assistant / Research Collaborator** · April 2026–Present

  Collaborative statistical research in causal inference, oncology, pediatric endocrinology, and high-dimensional biomedical data.

- **Tasly Pharma**

  **Biostatistics Intern / SAS Programmer** · Summer 2024

  Supported Phase II/III clinical-study workflows through SAS programming, clinical-data cleaning and validation, endpoint derivation, and review of statistical analysis and reporting materials.

- **Tianjin Fourth Center Hospital**

  **Medical Records / Information Department Intern** · Summer 2023

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
Last updated September 2026 · Pittsburgh, PA
</small>
