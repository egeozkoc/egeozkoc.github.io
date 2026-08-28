---
title: "Ege Ozkoc"
permalink: /
layout: portfolio
excerpt: "PhD student at the University of Pittsburgh working on machine learning, biomedical signals, and efficient AI systems."
---

<header id="about" class="profile-header">
  <img src="/assets/images/profile.jpeg" alt="Ege Ozkoc" width="586" height="752">
  <div>
    <h1>Ege Ozkoc</h1>
    <p class="profile-header__affiliation">PhD Student, Electrical and Computer Engineering<br>University of Pittsburgh</p>
    <p>I work on machine learning and signal processing for biomedical data, with experience in efficient AI systems and embedded inference.</p>
    <p class="profile-header__links"><a href="mailto:ege.ozkoc@pitt.edu">Email</a> · <a href="/assets/docs/Ege_Ozkoc_CV.pdf" target="_blank" rel="noopener">CV</a> · <a href="https://scholar.google.com/citations?user=OqtWjZUAAAAJ" target="_blank" rel="noopener">Google Scholar</a> · <a href="https://github.com/egeozkoc" target="_blank" rel="noopener">GitHub</a> · <a href="https://www.linkedin.com/in/egeozkoc/" target="_blank" rel="noopener">LinkedIn</a></p>
  </div>
</header>

<section class="content-section education-section">
  <h2>Education</h2>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/pitt.svg" alt="University of Pittsburgh" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>University of Pittsburgh</h3><p>PhD in Electrical and Computer Engineering</p></div>
    <p class="entry__date">2025–present</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/fau.svg" alt="Friedrich-Alexander-Universität Erlangen-Nürnberg" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>FAU Erlangen-Nürnberg</h3><p>MSc in Medical Engineering</p></div>
    <p class="entry__date">2022–2024</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/metu.svg" alt="Middle East Technical University" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Middle East Technical University</h3><p>BSc in Electrical and Electronics Engineering</p></div>
    <p class="entry__date">2016–2022</p>
  </div>
</section>

<section id="experience" class="content-section">
  <h2>Experience</h2>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/pitt.svg" alt="University of Pittsburgh" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>University of Pittsburgh</h3><p class="entry__role">Signal Processing and Statistical Learning Lab</p><p>I am developing evidence-grounded methods for explaining AI-ECG model outputs with LLMs. The explanations are constrained by model evidence, including saliency maps and SHAP attributions, rather than used for independent clinical diagnosis. I am the first-named inventor on a U.S. provisional patent for the framework.</p></div>
    <p class="entry__date">2025–present</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/fraunhofer.svg" alt="Fraunhofer IIS" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Fraunhofer IIS</h3><p class="entry__role">Medical Sensors and Analytics Group</p><p>I developed a lightweight 1D CNN for Parkinson's tremor detection from wrist-worn IMU data, for a hand-stabilizing glove that reacts to tremor onset. Under subject-independent validation it reached an AUC above 0.90, against 0.68–0.75 for FFT, SVM, and random-forest baselines; quantization and structured pruning then reduced its size by about 75% with under 0.1% accuracy loss.</p></div>
    <p class="entry__date">2024</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/fau.svg" alt="Friedrich-Alexander-Universität Erlangen-Nürnberg" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>FAU Erlangen-Nürnberg</h3><p class="entry__role">Machine Learning and Data Analytics Lab</p><p>I ran predictive gait simulations of leg-length inequality in MATLAB, and prepared the Python exercises for the Biomedical Signal Analysis course as a student assistant.</p></div>
    <p class="entry__date">2023–2024</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/uk-erlangen.svg" alt="Universitätsklinikum Erlangen" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Universitätsklinikum Erlangen</h3><p class="entry__role">Department of Radiology</p><p>I built neural-network pipelines for virtual contrast-enhanced breast MRI, preprocessing scans with SimpleITK and organizing patient data with Pandas.</p></div>
    <p class="entry__date">2023</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/aselsan.svg" alt="ASELSAN" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>ASELSAN</h3><p class="entry__role">Defense Systems Technologies Division</p><p>I built a MATLAB tool that visualized missile trajectory and orientation from experimental position and angle data.</p></div>
    <p class="entry__date">2021</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/metu.svg" alt="Middle East Technical University" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Middle East Technical University</h3><p class="entry__role">Heart Research Laboratory</p><p>I worked on the ClinECGI project, evaluating noninvasive electrocardiographic imaging for localizing premature ventricular contractions, and studied the inverse problem of electrocardiography through Bayesian MAP estimation and prior-model selection. The work led to two IEEE publications.</p></div>
    <p class="entry__date">2020–2022</p>
  </div>
</section>

<section id="projects" class="content-section">
  <h2>Projects</h2>
  <ul class="project-list">
    <li><a href="https://github.com/egeozkoc/mini-numpy" target="_blank" rel="noopener">mini-numpy</a> — a NumPy-like N-dimensional array library in modern C++, with Python bindings through pybind11.</li>
    <li><a href="https://github.com/egeozkoc/deep-learning-from-scratch" target="_blank" rel="noopener">deep-learning-from-scratch</a> — a NumPy/SciPy neural-network framework with manually implemented forward and backward passes, covering convolutional and recurrent layers, batch normalization, and Adam.</li>
    <li><a href="https://github.com/egeozkoc/lora-from-scratch" target="_blank" rel="noopener">lora-from-scratch</a> — a minimal LoRA implementation in PyTorch: the low-rank adapter, injection into existing linear layers, and weight merging, with small fine-tuning experiments.</li>
    <li><a href="https://github.com/egeozkoc/murmur" target="_blank" rel="noopener">murmur</a> — a local macOS dictation application built around Whisper, GPU-accelerated with MLX and running fully offline.</li>
    <li><a href="https://github.com/egeozkoc/clustering-toolbox" target="_blank" rel="noopener">clustering-toolbox</a> — a Streamlit application for clustering and exploring tabular data, with KMeans, GMM, and DBSCAN alongside PCA and t-SNE views.</li>
    <li>Open-source contributions to <a href="https://github.com/bitsandbytes-foundation/bitsandbytes/pulls?q=is%3Apr+author%3Aegeozkoc" target="_blank" rel="noopener">bitsandbytes</a>, including fixes to LAMB optimizer parameter handling and to blockwise quantization on non-contiguous CPU tensors.</li>
  </ul>
</section>

<section id="publications" class="content-section">
  <h2>Publications</h2>
  <ol class="publication-list">
    <li><strong>E. Ozkoc</strong>, T. S. Zech, N. Pfeiffer, S. Gobl, and J. Frickel. “Compressed and Lightweight CNN for Real-Time Parkinson's Tremor Detection from Wearable IMU Data.” <em>IEEE MLSP</em>, 2025. <a href="https://doi.org/10.1109/MLSP62443.2025.11204316" target="_blank" rel="noopener">DOI</a></li>
    <li><strong>E. Ozkoc</strong> and Y. Serinagaoglu Dogrusoz. “Bayesian MAP Solution of the Inverse ECG Problem with Sinus Rhythm Data: Evaluation of Simulated Training Sets.” <em>IEEE SIU</em>, 2022. <a href="https://doi.org/10.1109/SIU55565.2022.9864708" target="_blank" rel="noopener">DOI</a></li>
    <li><strong>E. Ozkoc</strong>, E. Sunger, K. Ugurlu, and Y. Serinagaoglu Dogrusoz. “Prior Model Selection in Bayesian MAP Estimation-Based ECG Reconstruction.” <em>Measurement</em>, 2021. <a href="https://doi.org/10.23919/Measurement52780.2021.9446831" target="_blank" rel="noopener">DOI</a></li>
  </ol>
</section>
