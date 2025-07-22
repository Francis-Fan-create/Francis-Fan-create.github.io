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

I am a 3rd year undergraduate majoring in computational mathematics at Peking University.

My research interests include scientific machine learning, diffusion model, high dimensional PDE, contextual bandit and QMC.

Here is my [CV](My_Resume_2025_4.pdf).

# 🔥 News


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/scasml.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physics-Informed Inference-Time Scaling for Solving High-dimensional PDE via Simula-
tion Calibrated Scientific Machine Learning (SCaSML)](https://arxiv.org/abs/2504.16172)

Authors: **Zexi Fan**, Yan Sun, Shihao Yang, Yiping Lu

[**Project**](https://github.com/Francis-Fan-create/SCaSML.git) <strong><span class='show_paper_citations' data=''></span></strong>
- First inference-time PDE solver based on surrogate model with convergence improvement guarantee
- Numerical efficacy on multiple semi-linear gradient dependent PDE systems at high dimensions
</div>
</div>

# 🎖 Honors and Awards


# 📖 Educations
- *Sep 2022 - Present*, **Peking University(PKU)**, B.S. in Computational Mathematics
  - Major GPA: 3.6/4.0
  - Selected Courses: Abstract Algebra(93), Machine Learning(93), Advanced Algebra 2(90)
  - Advanced Mathematical Skills: Stochastic Analysis & Control, Scientific Machine Learning, PDE
  - GRE: (164+169+4)/(170+170+6) (Aug 2023)

# 💬 Invited Talks


# 💻 Internships


# 🔬 Research Experience
  
- **Unbiased Square Root Convergent Estimation for High-Dimensional Semilinear Parabolic Heat Equation** (Sep 2023 - Feb 2024)
  - Supervisors: [Prof. Yiping Lu](https://2prime.github.io/) at NYU
  - Proposed an estimator using Multilevel Picard Iteration and randomized Multilevel Monte Carlo
  - Proved the unbiasedness and bounded variance of the estimator
  
- **Flow Calibrated RL for Transition Path Sampling** (Feb 2024 - June 2024)([Seminar](https://www.overleaf.com/read/pzcgkgrjxpys#477484),[Report](Transition_Path_with_template.pdf))
  - Supervisors: [Prof. Yiping Lu](https://2prime.github.io/) and [Dr. Dinghuai Zhang](https://zdhnarsil.github.io/) at NYU, Mila
  - Proposed an algorithm for sampling distribution-to-distribution transition paths under the SDE framework
  - Developed continuous versions of Soft Actor-Crictic and GFlowNet by stochastic analysis
  - Implemented numerical experiments to confirm its efficacy
  
- **Simulation-Calibrated Scientific Machine Learning (SCaSML) for Solving High-Dimensional Partial Differential Equations** (June 2024 - April 2025)([Paper](SCaSML_framework_techreport.pdf))
  - Supervisors: [Prof. Yiping Lu](https://2prime.github.io/) and [Dr. Yan Sun](https://www.researchgate.net/scientific-contributions/Yan-Sun-2195551935) at Northwestern, Gatech
  - Developed simulation-based estimators to calibrate PINN error
  - Demonstrated SCaSML effectiveness through numerical experiments on multiple high dim PDEs
  
- **Continuous State Contextual Bandit with Pessimism Regularization** (August 2024 - Present)
  - Supervisors: [Prof. Ying Jin](https://ying531.github.io/) at Havard
  - Constructed an adaptation Pessimism Regularization for contextual bandit with continuous state space
  - Proved the suboptimality of the estimator does not require uniform overlapping assumption 

# 📚 Academic Activities
- Graduate course: Combinatorics, Score: 92, taught by [Prof. Chunwei Song](https://www.math.pku.edu.cn/teachers/csong/index.html) (Spring 2023)
- Graduate course: Machine learning, Score: 93, taught by [Prof. Kedian Mou](https://scholar.google.com.hk/citations?user=H7QUCUwAAAAJ&hl=en) (Fall 2023)
- Graduate course: Mathematical image processing, taught by [Prof. Bin Dong](http://faculty.bicmr.pku.edu.cn/~dongbin/) (Fall 2023)
- Graduate course: High Dimensional Probability, taught by [Prof. Zhihua Zhang](https://www.math.pku.edu.cn/teachers/zhzhang/) (Fall 2024)
- Graduate course: Optimization Methods, taught by [Prof. Zaiwen Wen](http://faculty.bicmr.pku.edu.cn/~wenzw/index.html) (Fall 2024)
- Graduate course: Applied Stochastic Analysis, taught by [Prof. Tiejun Li](https://www.math.pku.edu.cn/teachers/litj/) (Fall 2024)
- Seminar: Blowup in fluid equations, organized by [Prof. Jiajun Tong](http://faculty.bicmr.pku.edu.cn/~tongj/) & [Prof. De Huang](https://sites.google.com/view/de-huang/home) (Fall 2023)
- Seminar: Stochastic optimal control, organized by Dr. Xinhan Duan (Spring 2024)
- Seminar: Large Language Model and Scientific Computing, organized by [Prof. Zaiwen Wen](http://faculty.bicmr.pku.edu.cn/~wenzw/index.html) (Fall 2024)
- Summer school: Beauty of theoretical computer science, organized by NJU CS Dept. (Summer 2024)

# 🌐 Social Activities
- Academic & Innovation Department, SMS Student Union (Spring 2023)
- English Debate Club (Summer 2024)

# 💻 Skills/Hobbies
- **Programming Languages**: Python, Matlab, Latex, Markdown
- **Machine Learning Tools**: Pytorch, Tensorflow, Numpy, Jax, Wandb, DeepXDE
- **Hobbies**: Animation and Program Designing
- **Languages**: English and Chinese