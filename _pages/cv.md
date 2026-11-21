---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Optional: upload your resume PDF to /files/ as resume.pdf and uncomment the next line -->
<!-- [Download my resume (PDF)](/files/resume.pdf){: .btn .btn--primary} -->

Education
======
* **B.S. Mechanical Engineering**, University of California, San Diego (in progress, junior transfer)
  * Coursework: MAE 3 (Intro to Engineering Graphics & Design), MAE 8 (MATLAB Programming)
* **Transfer coursework**, _[Your previous college]_, Ventura, CA

Engineering Teams
======
* **Project Daedalus**, UCSD Rocket Propulsion Lab

Certifications
======
* SOLIDWORKS Certified Associate (CSWA)

Skills
======
* **CAD & design:** SOLIDWORKS, tolerancing & GD&T, assemblies, 3ds Max
* **Fabrication:** 3D printing (FDM), rapid prototyping, hand assembly
* **Programming:** MATLAB

Projects
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
