---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<p class="page__lead">
Zhilang Qiu, PhD, is a Postdoctoral Research Fellow in the Laboratory for High-Field Imaging and Translational Neuroscience and the Advanced MRI/MRS Core at McLean Hospital / Harvard Medical School. Trained in biomedical engineering and magnetic resonance imaging, he develops advanced MRI and MR spectroscopy techniques to probe brain biology, physiology, structure, and function with high precision.
</p>

His work focuses on pushing the limits of scan efficiency, sensitivity, and specificity through new modeling approaches, encoding strategies, and reconstruction methods. He applies these methodological innovations to the study of neuropsychiatric disorders, including Alzheimer's disease, schizophrenia, and depression, aiming to uncover hidden neurobiological processes that contribute to disease mechanisms, developmental trajectories, biomarker discovery, and treatment response.

<div class="tag-row">
  <span class="tag">Glymphatic MRI</span>
  <span class="tag">³¹P MRSI</span>
  <span class="tag">MR Fingerprinting</span>
  <span class="tag">Wave-CAIPI &amp; Parallel Imaging</span>
  <span class="tag">Quantitative &amp; Diffusion MRI</span>
  <span class="tag">Neuropsychiatric Disorders</span>
</div>

<p class="link-row">
  <a class="btn-pill" href="{{ base_path }}/cv/"><i class="fas fa-file-alt" aria-hidden="true"></i> CV</a>
  <a class="btn-pill" href="{{ site.author.googlescholar }}"><i class="fas fa-graduation-cap" aria-hidden="true"></i> Google Scholar</a>
  <a class="btn-pill" href="{{ site.author.researchgate }}"><i class="ai ai-researchgate" aria-hidden="true"></i> ResearchGate</a>
  <a class="btn-pill" href="https://www.linkedin.com/in/{{ site.author.linkedin }}"><i class="fab fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
  <a class="btn-pill" href="mailto:{{ site.author.email }}"><i class="fas fa-envelope" aria-hidden="true"></i> Email</a>
</p>

## Current Research

<div class="cards">
  <div class="card">
    <div class="card__kicker">Direction 1</div>
    <h3 class="card__title">Glymphatic MRI for noninvasive measurement of glymphatic function in neuropsychiatric disorders</h3>
    <p>Developing advanced MRI techniques to noninvasively probe the glymphatic system and its role in brain physiology and pathology. By leveraging innovative acquisition strategies, quantitative modeling, and robust reconstruction methods, I aim to improve sensitivity and specificity for imaging fluid transport and clearance pathways in the brain.</p>
    <p>This work seeks to push the limits of scan efficiency and quantitative accuracy, enabling reliable characterization of glymphatic function in vivo, with application to neuropsychiatric and neurodegenerative disorders: disease mechanisms, progression, and treatment response.</p>
  </div>
  <div class="card">
    <div class="card__kicker">Direction 2</div>
    <h3 class="card__title">³¹P magnetization transfer MR spectroscopic imaging for cerebral energy metabolism</h3>
    <p>Developing advanced ³¹P MR spectroscopic imaging (MRSI) techniques to noninvasively assess cerebral energy metabolism and associated metabolic exchange processes. By integrating magnetization transfer strategies with optimized acquisition, modeling, and reconstruction methods, I aim to improve sensitivity, spatial resolution, and quantitative accuracy in multinuclear MR spectroscopy.</p>
  </div>
</div>

## Previous Research

<div class="cards">
  <div class="card">
    <div class="card__kicker">SIAT, Chinese Academy of Sciences</div>
    <h3 class="card__title">Advanced acquisition and reconstruction for fast 3D parallel MRI</h3>
    <p>Fast, high-resolution 3D imaging without compromising image quality, centered on integrating wave encoding with parallel imaging and new reconstruction frameworks to improve conditioning under highly undersampled acquisitions.</p>
    <p>Contributions include multiple wave-encoded imaging techniques (Wave-CAIPI-based methods, wave encoding with virtual conjugate coils, and aliasing-free reduced field-of-view parallel imaging) spanning Cartesian and non-Cartesian schemes, with theoretical modeling, parameter optimization, and practical implementation.</p>
  </div>
  <div class="card">
    <div class="card__kicker">Case Western Reserve University</div>
    <h3 class="card__title">Multidimensional MR fingerprinting for simultaneous relaxation and diffusion quantification</h3>
    <p>Integrating diffusion encoding into the MRF framework to jointly estimate T1, T2, and diffusion in a single acquisition. Rather than suppressing motion-induced phase errors in SSFP-based diffusion with hardware-intensive or SNR-costly strategies, I model them explicitly within the MRF signal model.</p>
    <p>In parallel, I developed self-calibrated subspace reconstruction combining low-rank modeling, matrix completion, and incoherent sampling to handle severe undersampling while capturing phase variations.</p>
  </div>
</div>

## Experience &amp; Education

<ul class="timeline">
  <li>
    <span class="timeline__date">2025 &ndash; now</span>
    <div><strong>Postdoctoral Research Fellow</strong><br>McLean Hospital &middot; Department of Psychiatry, Harvard Medical School</div>
  </li>
  <li>
    <span class="timeline__date">2023 &ndash; 2025</span>
    <div><strong>Research Scientist</strong><br>Department of Biomedical Engineering, Case Western Reserve University</div>
  </li>
  <li>
    <span class="timeline__date">2021 &ndash; 2023</span>
    <div><strong>Postdoctoral Scholar</strong><br>Department of Biomedical Engineering, Case Western Reserve University</div>
  </li>
  <li>
    <span class="timeline__date">2015 &ndash; 2021</span>
    <div><strong>PhD, Pattern Recognition and Intelligent Systems</strong><br>University of Chinese Academy of Sciences &middot; research at SIAT, Shenzhen</div>
  </li>
  <li>
    <span class="timeline__date">2011 &ndash; 2015</span>
    <div><strong>BEng, Biomedical Engineering</strong><br>Southern Medical University, Guangzhou</div>
  </li>
</ul>

## Recent Publications

{% assign pubs = site.publications | sort: "date" | reverse %}
<ul class="pub-list">
  {% for post in pubs limit: 5 %}{% include pub-entry.html %}{% endfor %}
</ul>
<p><a href="{{ base_path }}/publications/">All publications &rarr;</a></p>
