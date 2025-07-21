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
* Incoming Ph.D. Student at The University of Texas at Austin, Fall 2025
* M.S. Data Science, Columbia University, 2023
* B.S. Computer Science, The University of Texas at Austin, 2022

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Experience
======
* Summer 2023 - Current: **Cognizant AI Lab** - Data Scientist
  * Research and develop machine learning-based solutions to global challenges such as climate change using automatic decision-making methods such as evolutionary search
  * Contributor to Project Resilience - a collaboration with the UN to use AI for sustainable development

* Fall 2023: **Columbia University - Complex Resilient Intelligent Systems Lab** - Student Researcher
  * Analyzed weights of deep CNNs to identify alignment with an optimal maximum entropy distribution, then modified SGD to use this alignment to converge in less iterations.

* Summer 2022: **University of Texas at Austin - Stephen Yi Lab** - Student Researcher
  * Processed germline and somatic mutations and compared deleterious effects using statistical methods.

* Summer 2020: **Amazon - Devices Team** - SDE Intern
  * Designed camera setup and created real-time video stitching application for preliminary use in driving.

* Summer 2019: **Santa Clara County Technology Services and Solutions** - SDE Intern
  * Created handwriting reader to automatically process government forms, map services to help senior citizens find programs.

Skills
======
* Machine Learning
  * Numpy, Pandas, Scikit-Learn
* Deep Learning
  * PyTorch, Huggingface/Transformers, Tensorflow, Keras
* Visualization
  * Matplotlib, Plotly, Dash
* Software Engineering
  * Git, Docker, React, SQLAlchemy, Selenium, Gitlab CI/CD, AWS Deployment, Agile Methodologies
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
