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
</style>

<div class="intro-highlight">
Zhilang Qiu, PhD, is a <strong>Postdoctoral Research Fellow</strong> in the <a href="https://www.mcleanhospital.org/">Laboratory for High-Field Imaging and Translational Neuroscience</a> and the Advanced MRI/MRS Core at <strong>McLean Hospital / Harvard Medical School</strong>. He develops advanced MRI and MR spectroscopy techniques to probe brain biology, physiology, structure, and function with high precision. His work focuses on pushing the limits of scan efficiency, sensitivity, and specificity through new modeling approaches, encoding strategies, and reconstruction methods. Dr. Qiu applies these innovations to advance the study of neuropsychiatric disorders, including Alzheimer's disease, schizophrenia, and depression, aiming to uncover hidden neurobiological processes that contribute to disease mechanisms, developmental trajectories, biomarker discovery, and treatment response.
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
    <div class="timeline-meta">McLean Hospital &amp; Harvard Medical School &middot; 2025 &ndash; Present</div>
    <div class="timeline-desc">Development and translation of advanced multimodal neuroimaging techniques, including MRI and MR spectroscopy (MRS), to investigate neuropsychiatric disorders such as Alzheimer's disease, schizophrenia, and depression.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-title">Research Scientist</div>
    <div class="timeline-meta">Case Western Reserve University &middot; 2023 &ndash; 2025</div>
    <div class="timeline-desc">Research centered on MR Fingerprinting (MRF), quantitative MRI, and diffusion MRI. Advanced quantitative and multiparametric MRI methodologies.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-title">Postdoctoral Researcher</div>
    <div class="timeline-meta">Case Western Reserve University &middot; 2021 &ndash; 2023</div>
    <div class="timeline-desc">Postdoctoral training focused on advancing quantitative and multiparametric MRI methodologies, including MR Fingerprinting and diffusion MRI.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-title">Doctoral Researcher</div>
    <div class="timeline-meta">Shenzhen Institutes of Advanced Technology (SIAT), Chinese Academy of Sciences</div>
    <div class="timeline-desc">Research in biomedical engineering and MRI, with a focus on improving scan efficiency, sensitivity, and specificity through innovative modeling, encoding, and reconstruction approaches.</div>
  </div>

</div>

Education
======

<div class="edu-card">
  <div class="edu-degree">Ph.D. in Pattern Recognition and Intelligent Systems</div>
  <div class="edu-school">University of Chinese Academy of Sciences</div>
  <div class="edu-detail">Doctoral research conducted at Shenzhen Institutes of Advanced Technology (SIAT), Chinese Academy of Sciences. Developed advanced methodologies in biomedical engineering and magnetic resonance imaging.</div>
</div>

<div class="edu-card">
  <div class="edu-degree">B.Eng. in Biomedical Engineering</div>
  <div class="edu-school">Southern Medical University</div>
  <div class="edu-detail">Foundation in biomedical signal processing, medical imaging, and engineering principles that inform interdisciplinary research in neuroimaging.</div>
</div>

Selected Publications
======

<p class="section-subtitle">First-author &amp; co-first-author journal articles</p>

<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">Self-calibrated subspace reconstruction for multidimensional MR fingerprinting for simultaneous relaxation and diffusion quantification</div>
  <div class="pub-authors"><span class="me">Z Qiu</span>, S Hu, W Zhao, K Sakaie, JEP Sun, MA Griswold, DK Jones, D Ma</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2024; 91(5): 1978&ndash;1993 <span class="pub-badge">First Author</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Highly accelerated parallel MRI using wave encoding and virtual conjugate coils</div>
  <div class="pub-authors"><span class="me">Z Qiu</span>, S Jia, S Su, Y Zhu, X Liu, H Zheng, D Liang, H Wang</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2021 <span class="pub-badge">First Author</span></div>
</li>

<li class="pub-item">
  <div class="pub-title">Aliasing-free reduced field-of-view parallel imaging</div>
  <div class="pub-authors">S Jia, <span class="me">Z Qiu</span>, L Zhang, H Wang, G Yang, X Liu, D Liang, H Zheng</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2022 <span class="pub-badge">Co-first Author</span></div>
</li>

</ul>

<p class="section-subtitle">Selected co-authored publications</p>

<ul class="pub-list">

<li class="pub-item">
  <div class="pub-title">Deep Learning&ndash;Based Structural Brain Age Estimation in Bipolar Disorder and Schizophrenia: A Single-Site Pilot Study</div>
  <div class="pub-authors">A Weerasekera, S Zhou, C Wang, <span class="me">Z Qiu</span>, et al.</div>
  <div class="pub-venue">Human Brain Mapping, 2026; 47(3): e70479</div>
</li>

<li class="pub-item">
  <div class="pub-title">Assessing repeatability and confounding factors of magnetic resonance fingerprinting (MRF) for quantitative liver imaging</div>
  <div class="pub-authors">K Stephans, ..., <span class="me">Z Qiu</span>, et al.</div>
  <div class="pub-venue">Medical Physics, 2025</div>
</li>

<li class="pub-item">
  <div class="pub-title">Efficient pulse sequence design framework for high-dimensional MR fingerprinting scans using systematic error index</div>
  <div class="pub-authors">S Hu, <span class="me">Z Qiu</span>, RJ Adams, W Zhao, et al.</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2024</div>
</li>

<li class="pub-item">
  <div class="pub-title">High resolution single-shot myocardial imaging using bSSFP with wave encoding</div>
  <div class="pub-authors">S Jia, <span class="me">Z Qiu</span>, et al.</div>
  <div class="pub-venue">Medical Physics, 2023</div>
</li>

<li class="pub-item">
  <div class="pub-title">MR Fingerprinting with b-Tensor Encoding for Simultaneous Quantification of Relaxation and Diffusion in a Single Scan</div>
  <div class="pub-authors">M Afzali, ..., <span class="me">Z Qiu</span>, et al.</div>
  <div class="pub-venue">Magnetic Resonance in Medicine, 2022</div>
</li>

</ul>

<p style="text-align: center; margin-top: 0.5em;">
<a href="https://scholar.google.com/citations?user=tmgnYv4AAAAJ" style="color: #1565C0; font-weight: 600;">View full publication list on Google Scholar &rarr;</a>
</p>

Current Research Directions
------

<div class="research-card">
<h4>Glymphatic MRI for Noninvasive Measurement of Glymphatic Function in Neuropsychiatric Disorders</h4>
<p>Developing advanced MRI techniques to noninvasively probe the glymphatic system and its role in brain physiology and pathology. By leveraging innovative acquisition strategies, quantitative modeling, and robust reconstruction methods, this work aims to improve sensitivity and specificity for imaging fluid transport and clearance pathways in the brain. These methodological advances are applied to the study of neuropsychiatric and neurodegenerative disorders, with the goal of uncovering previously inaccessible physiological processes related to disease mechanisms, progression, and treatment response.</p>
</div>

<div class="research-card">
<h4>&#xB3;&#xB9;P Magnetization Transfer MR Spectroscopic Imaging for Cerebral Energy Metabolism</h4>
<p>Developing advanced &#xB3;&#xB9;P MR spectroscopic imaging (MRSI) techniques to noninvasively assess cerebral energy metabolism and associated metabolic exchange processes. By integrating magnetization transfer strategies with optimized acquisition, modeling, and reconstruction methods, this work aims to improve sensitivity, spatial resolution, and quantitative accuracy in multinuclear MR spectroscopy.</p>
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
