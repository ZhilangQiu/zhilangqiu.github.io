---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* ===== Blue Theme for Section Headings ===== */
.page__title { color: #1565C0; }
.page__content h1, .page__content h2 { color: #1565C0; }

/* ===== Intro Highlight ===== */
.intro-highlight {
  background: linear-gradient(135deg, #e3f2fd 0%, #f5f9ff 100%);
  border-left: 4px solid #1565C0;
  padding: 1em 1.2em;
  border-radius: 0 8px 8px 0;
  margin-bottom: 1.5em;
  line-height: 1.7;
}
.intro-highlight a { color: #1565C0; font-weight: 600; }

/* ===== Timeline ===== */
.timeline { position: relative; padding-left: 28px; margin: 0.5em 0 1.5em 0; }
.timeline::before {
  content: '';
  position: absolute;
  left: 6px;
  top: 4px;
  bottom: 4px;
  width: 2px;
  background: #bbdefb;
}
.timeline-item { position: relative; margin-bottom: 1.5em; }
.timeline-item::before {
  content: '';
  position: absolute;
  left: -25px;
  top: 5px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #1565C0;
  border: 2px solid #e3f2fd;
}
.timeline-item.current::before {
  background: #1565C0;
  box-shadow: 0 0 0 3px rgba(21, 101, 192, 0.2);
}
.timeline-title {
  font-weight: 700;
  color: #1565C0;
  font-size: 1.02em;
  margin-bottom: 0.1em;
}
.timeline-meta {
  color: #666;
  font-size: 0.88em;
  margin-bottom: 0.3em;
}
.timeline-desc {
  font-size: 0.95em;
  line-height: 1.6;
  color: #333;
}

/* ===== Education Cards ===== */
.edu-card {
  background: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1em 1.2em;
  margin-bottom: 1em;
  transition: box-shadow 0.2s;
}
.edu-card:hover { box-shadow: 0 2px 12px rgba(21,101,192,0.10); }
.edu-degree {
  font-weight: 700;
  color: #1565C0;
  font-size: 1.02em;
}
.edu-school { color: #333; font-weight: 600; }
.edu-dates { color: #888; font-size: 0.85em; }
.edu-detail { color: #666; font-size: 0.9em; margin-top: 0.3em; line-height: 1.5; }

/* ===== Publication List ===== */
.pub-list { list-style: none; padding: 0; margin: 0.5em 0; counter-reset: pub; }
.pub-item {
  position: relative;
  padding: 0.8em 0 0.8em 0;
  border-bottom: 1px solid #f0f0f0;
  line-height: 1.6;
}
.pub-item:last-child { border-bottom: none; }
.pub-title { font-weight: 600; color: #222; }
.pub-authors { font-size: 0.92em; color: #555; }
.pub-authors .me { color: #1565C0; font-weight: 700; }
.pub-venue { font-size: 0.9em; color: #888; font-style: italic; }
.pub-badge {
  display: inline-block;
  background: #e3f2fd;
  color: #1565C0;
  font-size: 0.75em;
  font-weight: 700;
  padding: 2px 8px;
  border-radius: 4px;
  margin-left: 6px;
  vertical-align: middle;
}

/* ===== Research Direction Cards ===== */
.research-card {
  background: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1em 1.2em;
  margin-bottom: 1em;
  border-top: 3px solid #1565C0;
}
.research-card h4 {
  color: #1565C0;
  margin-top: 0;
  margin-bottom: 0.5em;
  font-size: 1em;
}
.research-card p {
  font-size: 0.93em;
  line-height: 1.65;
  color: #444;
}

/* ===== Profile Links ===== */
.profile-links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 1em 0;
}
.profile-link {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 6px 14px;
  background: #e3f2fd;
  color: #1565C0 !important;
  border-radius: 20px;
  font-size: 0.9em;
  font-weight: 600;
  text-decoration: none !important;
  transition: background 0.2s, box-shadow 0.2s;
}
.profile-link:hover {
  background: #bbdefb;
  box-shadow: 0 2px 8px rgba(21,101,192,0.15);
  text-decoration: none !important;
}

/* ===== Section Divider ===== */
.section-subtitle {
  color: #999;
  font-size: 0.85em;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  margin-bottom: 0.8em;
}

/* ===== Award Items ===== */
.award-item {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  padding: 0.6em 0;
  border-bottom: 1px solid #f0f0f0;
}
.award-item:last-child { border-bottom: none; }
.award-name { font-weight: 600; color: #333; }
.award-org { font-size: 0.9em; color: #666; }
.award-year { color: #1565C0; font-weight: 600; font-size: 0.9em; white-space: nowrap; margin-left: 1em; }

/* ===== Service Items ===== */
.service-item {
  padding: 0.4em 0;
  font-size: 0.95em;
  color: #444;
}
.service-role { font-weight: 600; color: #333; }
</style>

<div class="intro-highlight">
Zhilang Qiu, PhD, is a <strong>Postdoctoral Research Fellow</strong> in the <a href="https://www.mcleanhospital.org/">Division of Psychotic Disorders</a> and the McLean Imaging Center at <strong>McLean Hospital</strong>, and the Department of Psychiatry at <strong>Harvard Medical School</strong>. He develops advanced MRI and MR spectroscopy techniques to probe brain biology, physiology, structure, and function with high precision. His current research focuses on Glymphatic MRI, <sup>1</sup>H and <sup>31</sup>P MRSI, and translational MR in psychiatry. Dr. Qiu applies these innovations to advance the study of neuropsychiatric disorders, including Alzheimer's disease, schizophrenia, and depression, aiming to uncover hidden neurobiological processes that contribute to disease mechanisms, developmental trajectories, biomarker discovery, and treatment response.
</div>

<div class="profile-links">
  <a class="profile-link" href="https://scholar.google.com/citations?user=tmgnYv4AAAAJ"><i class="fas fa-graduation-cap"></i> Google Scholar</a>
  <a class="profile-link" href="https://www.researchgate.net/profile/Zhilang-Qiu"><i class="fab fa-researchgate"></i> ResearchGate</a>
  <a class="profile-link" href="https://www.linkedin.com/in/zhilang-qiu-b73965134"><i class="fab fa-linkedin"></i> LinkedIn</a>
  <a class="profile-link" href="https://pubmed.ncbi.nlm.nih.gov/?term=Zhilang+Qiu"><i class="fas fa-book-medical"></i> PubMed</a>
  <a class="profile-link" href="https://github.com/ZhilangQiu"><i class="fab fa-github"></i> GitHub</a>
</div>

Experience
======

<div class="timeline">

  <div class="timeline-item current">
    <div class="timeline-title">Postdoctoral Research Fellow</div>
    <div class="timeline-meta">Division of Psychotic Disorders &amp; McLean Imaging Center, McLean Hospital<br>Department of Psychiatry, Harvard Medical School &middot; 03/2025 &ndash; Present</div>
    <div class="timeline-desc">Research focus: Glymphatic MRI, <sup>1</sup>H and <sup>31</sup>P MRSI, and translational MR in psychiatry.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-title">Research Scientist</div>
    <div class="timeline-meta">Case Western Reserve University &middot; 12/2023 &ndash; 03/2025</div>
    <div class="timeline-desc">Research focus: MR fingerprinting, quantitative MRI, and diffusion MRI.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-title">Postdoctoral Scholar</div>
    <div class="timeline-meta">Case Western Reserve University &middot; 10/2021 &ndash; 10/2023</div>
    <div class="timeline-desc">Research focus: MR fingerprinting, quantitative MRI, and diffusion MRI.</div>
  </div>

</div>

Education
======

<div class="edu-card">
  <div class="edu-degree">Doctor of Philosophy</div>
  <div class="edu-school">University of Chinese Academy of Sciences (Beijing, China)</div>
  <div class="edu-dates">09/2015 &ndash; 06/2021</div>
  <div class="edu-detail">Major: Pattern Recognition and Intelligent System<br>Dissertation: Fast Three-Dimensional Magnetic Resonance Imaging<br>Research conducted at Shenzhen Institutes of Advanced Technology (SIAT), Chinese Academy of Sciences.</div>
</div>

<div class="edu-card">
  <div class="edu-degree">Bachelor of Engineering</div>
  <div class="edu-school">Southern Medical University (Guangzhou, China)</div>
  <div class="edu-dates">09/2011 &ndash; 06/2015</div>
  <div class="edu-detail">Major: Biomedical Engineering<br>Ranked 2nd out of 330 students in Biomedical Engineering.</div>
</div>

Selected Publications
======

<p class="section-subtitle">First-author &amp; co-first-author journal articles (# co-first)</p>

<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">Self-calibrated Subspace Reconstruction for Multidimensional MR Fingerprinting for Simultaneous Relaxation and Diffusion Quantification</div>
  <div class="pub-authors"><span class="me">Qiu Z</span>, Hu S, Zhao W, Sakaie K, Sun JE, Griswold MA, Jones DK, Ma D</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2024; 91: 1978&ndash;93 <span class="pub-badge">First Author</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Highly Accelerated Parallel MRI Using Wave Encoding and Virtual Conjugate Coils</div>
  <div class="pub-authors"><span class="me">Qiu Z</span>, Jia S, Su S, Zhu Y, Liu X, Zheng H, Liang D, Wang H</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2021; 86: 1345&ndash;1359 <span class="pub-badge">First Author</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Aliasing-free Reduced Field-of-view Parallel Imaging</div>
  <div class="pub-authors">Jia S#, <span class="me">Qiu Z</span>#, Zhang L, Wang H, Yang G, Liu X, Liang D, Zheng H</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2022; 87: 1574&ndash;1582 <span class="pub-badge">Co-first Author</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Parameter Optimization Framework on Wave Gradients of Wave-CAIPI Imaging</div>
  <div class="pub-authors">Wang H#, <span class="me">Qiu Z</span>#, Su S, Jia S, Li Y, Zheng H, Liang D</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2020; 83: 1659&ndash;1672 <span class="pub-badge">Co-first Author</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Accelerated 3D bSSFP Using a Modified Wave-CAIPI Technique with Truncated Wave Gradients</div>
  <div class="pub-authors">Su S#, <span class="me">Qiu Z</span>#, Luo C, Shi C, Wan L, Zhu Y, Li Y, Liu X, Zheng H, Liang D, Wang H</div>
  <div class="pub-venue">IEEE Transactions on Medical Imaging, 2021; 40: 48&ndash;58 <span class="pub-badge">Co-first Author</span></div>
</li>

</ul>

<p class="section-subtitle">Selected co-authored publications</p>

<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">Deep Learning&ndash;Based Structural Brain Age Estimation in Bipolar Disorder and Schizophrenia</div>
  <div class="pub-authors">Weerasekera A, Zhou S, Wang C, <span class="me">Qiu Z</span>, Stein A, et al.</div>
  <div class="pub-venue">Human Brain Mapping, 2026; 47(3): e70479</div>
</li>

<li class="pub-item">
  <div class="pub-title">Assessing Repeatability and Confounding Factors of MRF for Quantitative Liver Imaging</div>
  <div class="pub-authors">Lu L, Stephans K, <span class="me">Qiu Z</span>, Tirumani S, Chen Y</div>
  <div class="pub-venue">Medical Physics, 2025; 52(7): e17932</div>
</li>

<li class="pub-item">
  <div class="pub-title">Efficient Pulse Sequence Design Framework for High-Dimensional MR Fingerprinting Scans</div>
  <div class="pub-authors">Hu S, <span class="me">Qiu Z</span>, Adams RJ, Zhao W, Boyacioglu R, Calvetti D, McGivney D, Ma D</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2024; 92: 1600&ndash;1616</div>
</li>

</ul>

<p style="text-align: center; margin-top: 0.5em;">
<a href="https://scholar.google.com/citations?user=tmgnYv4AAAAJ" style="color: #1565C0; font-weight: 600;">View all 14 journal articles &amp; 26 conference papers on Google Scholar &rarr;</a>
</p>

Selected Presentations
------

<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">Glymphatic Dysfunction and Lifespan Trajectories Across Neuropsychiatric Disorders Revealed by DTI-ALPS</div>
  <div class="pub-venue">ISMRM &amp; ISMRT Annual Meeting, Cape Town, South Africa, 2026 <span class="pub-badge">Power Pitch</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Modeling Phase Errors for Robust and Efficient Multidimensional MR Fingerprinting for Simultaneous Relaxation and Diffusion Mapping</div>
  <div class="pub-venue">ISMRM &amp; ISMRT Annual Meeting, Singapore, 2024 <span class="pub-badge">Oral Presentation</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Simultaneous Quantification of Relaxation and Diffusion Using MR Fingerprinting with Self-Calibrated Subspace Reconstruction</div>
  <div class="pub-venue">ISMRM &amp; ISMRT Annual Meeting, Toronto, Canada, 2023 <span class="pub-badge">Oral Presentation</span></div>
</li>

</ul>

Awards
------

<div>

<div class="award-item">
  <div><span class="award-name">Second Place, MR in Psychiatry Study Group Award</span><br><span class="award-org">MR in Psychiatry Study Group, ISMRM</span></div>
  <div class="award-year">2026</div>
</div>

<div class="award-item">
  <div><span class="award-name">Trainee Educational Stipend</span><br><span class="award-org">International Society for Magnetic Resonance in Medicine (ISMRM)</span></div>
  <div class="award-year">2018, 2019, 2020</div>
</div>

<div class="award-item">
  <div><span class="award-name">President's Scholarship Special Prize</span><br><span class="award-org">Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences</span></div>
  <div class="award-year">2020</div>
</div>

<div class="award-item">
  <div><span class="award-name">Director's Innovation Fund Student Award</span><br><span class="award-org">Institute of Biomedical and Health Engineering, SIAT, Chinese Academy of Sciences</span></div>
  <div class="award-year">2020</div>
</div>

<div class="award-item">
  <div><span class="award-name">Excellent Student Award</span><br><span class="award-org">University of Chinese Academy of Sciences</span></div>
  <div class="award-year">2019</div>
</div>

</div>

Current Research Directions
------

<div class="research-card">
<h4>Glymphatic MRI for Noninvasive Measurement of Glymphatic Function in Neuropsychiatric Disorders</h4>
<p>Developing advanced MRI techniques to noninvasively probe the glymphatic system and its role in brain physiology and pathology. By leveraging innovative acquisition strategies, quantitative modeling, and robust reconstruction methods, this work aims to improve sensitivity and specificity for imaging fluid transport and clearance pathways in the brain. These methodological advances are applied to the study of neuropsychiatric and neurodegenerative disorders, with the goal of uncovering previously inaccessible physiological processes related to disease mechanisms, progression, and treatment response.</p>
</div>

<div class="research-card">
<h4><sup>31</sup>P Magnetization Transfer MR Spectroscopic Imaging for Cerebral Energy Metabolism</h4>
<p>Developing advanced <sup>31</sup>P MR spectroscopic imaging (MRSI) techniques to noninvasively assess cerebral energy metabolism and associated metabolic exchange processes. By integrating magnetization transfer strategies with optimized acquisition, modeling, and reconstruction methods, this work aims to improve sensitivity, spatial resolution, and quantitative accuracy in multinuclear MR spectroscopy.</p>
</div>

Past Research Directions
------

<div class="research-card">
<h4>Advanced Acquisition and Reconstruction Methods for Fast 3D Parallel MRI</h4>
<p>Developed advanced MRI acquisition and reconstruction strategies to enable fast, high-resolution 3D imaging without compromising image quality. This work integrates wave encoding with parallel imaging and innovative reconstruction frameworks to improve conditioning under highly undersampled acquisitions. Contributions include Wave-CAIPI&ndash;based methods, reduced field-of-view parallel imaging, and virtual conjugate coil reconstruction &mdash; addressing aliasing artifacts, reconstruction burden, and workflow efficiency across Cartesian and non-Cartesian acquisition schemes.</p>
</div>

<div class="research-card">
<h4>Multidimensional MR Fingerprinting for Simultaneous Relaxation and Diffusion Quantification</h4>
<p>Advanced multidimensional MR fingerprinting (MRF) methodologies to enable simultaneous and robust quantification of relaxation and diffusion parameters within a single acquisition. Developed explicit phase error modeling approaches within the MRF framework to improve robustness against motion-induced artifacts, and self-calibrated subspace reconstruction methods integrating low-rank modeling, matrix completion, and incoherent sampling to enable accurate joint estimation of T1, T2, and diffusion parameters.</p>
</div>

Service
------

<div class="service-item"><span class="service-role">Conference Reviewer:</span> ISMRM &amp; ISMRT Annual Meeting &amp; Exhibition, 2023, 2024, 2026</div>
<div class="service-item"><span class="service-role">Ad hoc Journal Reviewer:</span> Frontiers in Neurology (2026), Medical Physics (2025)</div>
<div class="service-item"><span class="service-role">Member:</span> International Society of Magnetic Resonance in Medicine (ISMRM), 2018 &ndash; Present</div>
