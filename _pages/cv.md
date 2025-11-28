---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.S. in Applied Mathematics**, Emory University, May 2026 (expected)
  * GPA: 4.0

Research Experience
======
* **Oak Ridge National Laboratory** (Summer 2025)
  * Research Intern, Mentor: Dr. Guannan Zhang
  * Developed stochastic optimal control approaches using conditional diffusion models to solve Bayesian inverse problems
  * Researched hybrid methods combining diffusion posterior sampling with SOC techniques
  * Implemented multiple SOC solvers: adjoint matching, finite element method, neural ODEs, neural-FBSDE

* **Emory University** (Ongoing)
  * Undergraduate Researcher with Prof. Lars Ruthotto & Prof. Levon Nurbekyan
  * Working on algorithms for high-dimensional stochastic optimal control
  * Exploring connections between flow matching, score-based models, mean field games, and control theory

* **Emory University REU - Computational Mathematics for Data Science** (Summer 2024)
  * Undergraduate Researcher, Advisor: Dr. Deepanshu Verma
  * Investigated methods to enhance variational autoencoders using conditional normalizing flows
  * Built and trained VAE models using Pyro with PyTorch

* **Emory University** (Ongoing)
  * Undergraduate Researcher with Prof. Matthias Chung
  * Working on variational sparse paired autoencoders for inverse problems

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Technical Skills
======
* **Languages:** Python, Java, C#, R, HTML/CSS
* **Scientific Computing & Frameworks:** PyTorch, Pyro, FEniCS, NumPy, SciPy, Matplotlib
* **Tools:** Git, MATLAB, VS Code, LaTeX, SLURM

Relevant Coursework
======
* **Graduate:** Topics in Computational Mathematics (Generative Modeling), Matrix Analysis, Numerical Analysis, Real Analysis, Numerical PDEs
* **Undergraduate:** Mathematical Statistics, Nonlinear Optimization, Linear Algebra (proof-based), Differential Equations, PDEs, Data Structures and Algorithms

Awards & Honors
======
* Chair's Achievement Award, Emory Math Department (2025)
* Dean's List, Emory University (2023-2025)
