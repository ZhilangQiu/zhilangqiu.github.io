---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv" markdown="1">

Education
======
* **Doctor of Philosophy** <span class="cv-date">09/2015 – 06/2021</span>
  * University of Chinese Academy of Sciences, Beijing, China
  * Major: Pattern Recognition and Intelligent System
  * Dissertation: *Fast Three-Dimensional Magnetic Resonance Imaging*
  * Research conducted at the Paul C. Lauterbur Research Centre for Biomedical Imaging, Shenzhen Institutes of Advanced Technology (SIAT), Chinese Academy of Sciences

* **Bachelor of Engineering** <span class="cv-date">09/2011 – 06/2015</span>
  * Southern Medical University, Guangzhou, China
  * Major: Biomedical Engineering
  * Ranked 2nd out of 330 students in Biomedical Engineering

Experience
======
* **Postdoctoral Research Fellow** <span class="cv-date">03/2025 – Present</span>
  * Division of Psychotic Disorders, McLean Hospital
  * McLean Imaging Center, McLean Hospital
  * Department of Psychiatry, Harvard Medical School, Boston, MA, USA
  * Research focus: Glymphatic MRI, ¹H and ³¹P MRSI, and translational MR in psychiatry

* **Research Scientist** <span class="cv-date">12/2023 – 03/2025</span>
  * Department of Biomedical Engineering, Case Western Reserve University, Cleveland, OH, USA
  * Research focus: MR fingerprinting, quantitative MRI, and diffusion MRI

* **Postdoctoral Scholar** <span class="cv-date">10/2021 – 10/2023</span>
  * Department of Biomedical Engineering, Case Western Reserve University, Cleveland, OH, USA
  * Research focus: MR fingerprinting, quantitative MRI, and diffusion MRI

Publications
======
{% assign pubs = site.publications | sort: "date" | reverse %}
<ul class="pub-list">{% for post in pubs %}{% include pub-entry.html %}{% endfor %}</ul>

Talks & Presentations
======
{% assign talks = site.talks | sort: "date" | reverse %}
<ul class="talk-list">{% for post in talks %}{% include talk-entry.html %}{% endfor %}</ul>

Awards & Honors
======
* **Second Place, MR in Psychiatry Study Group Award** <span class="cv-date">2026</span>
  * MR in Psychiatry Study Group, ISMRM

* **Trainee Educational Stipend** <span class="cv-date">2018, 2019, 2020</span>
  * International Society for Magnetic Resonance in Medicine (ISMRM)

* **President's Scholarship Special Prize** <span class="cv-date">2020</span>
  * Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences

* **Director's Innovation Fund Student Award** <span class="cv-date">2020</span>
  * Institute of Biomedical and Health Engineering, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences

* **Excellent Student Award** <span class="cv-date">2019</span>
  * University of Chinese Academy of Sciences

Service
======
* **Conference Reviewer**: ISMRM & ISMRT Annual Meeting & Exhibition (2023, 2024, 2026)
* **Ad hoc Journal Reviewer**: *Frontiers in Neurology* (2026), *Medical Physics* (2025)

Memberships
======
* International Society for Magnetic Resonance in Medicine (ISMRM), Trainee Member (2018 – Present)

</div>
