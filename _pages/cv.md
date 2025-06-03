---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Electrical and Computer Engineering, Purdue University, 2028 (expected)
  * Supervised by Prof. [Muhammad Ashraful Alam](https://sites.google.com/view/alam-research-group/home)
    * Specializing in AI for Science
* MS in Electronic Engineering, Sogang University, 2014
  * Supervised by Prof. [Woo Young Choi](https://sites.google.com/view/snutidl) (Now at Seoul National University)
    * Specializing in Semiconductor Device Modeling and Simulation
* BS in Electronic Engineering, Sogang University, 2012

Work Experience
======
* (2017–Present) Staff Research Engineer, Advanced Simulation Group, CSE Team, Samsung Electronics
  * Develop, apply, and optimize machine learning algorithms for semiconductor device design and analysis
    * Symmetry- and geometry-aware representation learning of high-dimensional data like wafer map images.
    * A novel physics-driven neural differential equation model for learning dynamical systems. 
    * Real-time device and process simulation with deep neural networks. 
    * Automatic generation of DRAM design test vectors using deep reinforcement learning.
* (2017–2018) Research Engineer, Logic TCAD Group, CAE Team, Samsung Electronics
  * Analyzed gate stack structures of 7-nm fin transistors using theoretical approaches and numerical simulations.

Publications
======
<ul class="publication-list">
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Other Achievements
=====
* Filed 5 US patents and 9 pending US patent applications in AI and simulation technologies
* Serving as a reviewer for NeurIPS, ICML, ICLR, and AISTATS.
* Recognized with 7 Samsung technical awards, including two CEO-level commendations.
* Fully supported by Samsung Electronics for MS and Ph.D. studies.
