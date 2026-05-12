---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a 4th-year undergraduate in Computational Mathematics at Peking University. I am going to become a PhD in Applied Mathematics at Columbia University.
My research lies at the intersection of high-dimensional PDEs, scientific computing, stochastic dynamics, and non-equilibrium Markov processes. I build theory-backed algorithms and scale them to high-dimensional experiments.
Here is my [CV](resume/resume.pdf).

# 📝 Publications

For a complete and up-to-date list, visit my [Google Scholar profile](https://scholar.google.com/citations?user=QX64w3MAAAAJ&hl=en).

# 🎖 Honors and Awards
*(to be filled / updated)*

# 📖 Education
- *Sep 2022 - Jun 2026*, **Peking University (PKU)**, B.S. in Computational Mathematics  
- *Aug 2026 -*, **Columbia University**, PhD. in Applied Mathematics

# 💬 Invited Talks
*(to be updated when scheduled)*

# 💻 Internships
*(to be updated)*

# 🔬 Research Experience

**Sharp hypocoercive convergence estimates for nonequilibrium dynamics** — *Jul 2025 – Present*  
Supervisors: [Prof. Jianfeng Lu](https://sites.math.duke.edu/~jianfeng/) (Duke), [Prof. Bowen Li](https://www.cityu.edu.hk/stfprofile/bowenli.htm) (CityU)  
Designed a novel gapped-DMS method for sharp hypocoercive estimate of convergence rate. A preview on underdamped Langevin can be found here ([arXiv](https://arxiv.org/abs/2604.10068)). We are building a general nonequilibrium version that establish the square root and perturbation threshold explicitly, and potentially there would also be a time discrete version as well.

**Simulation-Calibrated Algorithm for High-Dimensional PDEs (SCaSML)** — *Jun 2024 – Apr 2025*  
Supervisors: [Prof. Yiping Lu](https://2prime.github.io/) (Northwestern), Dr. Yan Sun (Georgia Tech)  
Proposed SCaSML, a simulation-calibrated pipeline correcting PINN bias via Multilevel Picard-style estimators with provably improved complexity scaling on 100d+ benchmarks. ([arXiv](https://arxiv.org/abs/2504.16172))

**Continuous-State Contextual Bandit with Pessimism Regularization** — *Aug 2024 – Nov 2025*  
Supervisor: [Prof. Ying Jin](https://ying531.github.io/) (Harvard)  
Extended pessimism regularization to continuous state/action spaces with function approximation, proving regret guarantees without uniform-overlap assumptions.

**Flow-Calibrated Stochastic Control for Transition Path Sampling** — *Feb 2024 – Jun 2024*  
Supervisors: [Prof. Yiping Lu](https://2prime.github.io/) (Courant), [Dr. Dinghuai Zhang](https://zdhnarsil.github.io/) (Mila)  
Reformulated transition-path sampling as stochastic optimal control and developed continuous SAC and GFlowNet variants guided by flow-based calibration.

**Unbiased Square-Root Convergent Estimation for High-Dimensional Semilinear Parabolic PDEs** — *Sep 2023 – Feb 2024*  
Supervisor: [Prof. Yiping Lu](https://2prime.github.io/) (Courant)  
Developed an unbiased estimator combining Multilevel Picard iteration with randomized MLMC, establishing unbiasedness and variance bounds.

# 📚 Academic Activities
- Graduate course: Combinatorics (Score: 92), [Prof. Chunwei Song](https://www.math.pku.edu.cn/teachers/csong/index.html) — Spring 2023  
- Graduate course: Statistical Learning (Score: 93), [Prof. Kedian Mou](https://scholar.google.com.hk/citations?user=H7QUCUwAAAAJ&hl=en) — Fall 2023  
- Graduate course: High Dimensional Probability, [Prof. Zhihua Zhang](https://www.math.pku.edu.cn/teachers/zhzhang/) — Fall 2024  
- Graduate course: Optimization Methods, [Prof. Zaiwen Wen](http://faculty.bicmr.pku.edu.cn/~wenzw/index.html) — Fall 2024  
- Graduate course: Applied Stochastic Analysis, [Prof. Tiejun Li](https://www.math.pku.edu.cn/teachers/litj/) — Fall 2024  
- Seminars: Blowup in fluid equations; Stochastic optimal control (organizer: Dr. Xinhan Duan); LLM & Scientific Computing (Prof. Zaiwen Wen)  
- Summer school: Beauty of Theoretical Computer Science (NJU) — Summer 2024

# 🌐 Social Activities
- Academic & Innovation Department, SMS Student Union — Spring 2023  
- English Debate Club — Summer 2024

# 💻 Skills / Hobbies
- **Programming Languages:** Python, MATLAB, \LaTeX, Markdown  
- **Numerical & Scientific Computing Tools:** PyTorch, TensorFlow, JAX, NumPy, DeepXDE, WandB  
- **Numerical / Math Techniques:** Multilevel Picard, MLMC, Krylov solvers, reduced-order modelling, hypocoercivity, concentration inequalities, optimal transport  
- **Hobbies:** Animation, program design  
- **Languages:** Mandarin (native), English (fluent)

---


