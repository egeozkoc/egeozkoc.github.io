---
title: "Ege Ozkoc"
permalink: /
layout: portfolio
excerpt: "PhD student at the University of Pittsburgh working on machine learning for real-world time-series data, interpretable AI systems, and efficient deep learning."
---

<header id="about" class="profile-header">
  <img src="/assets/images/profile.jpeg" alt="Ege Ozkoc" width="586" height="752">
  <div>
    <h1>Ege Ozkoc</h1>
    <p class="profile-header__affiliation">PhD Student, Electrical and Computer Engineering<br>University of Pittsburgh</p>
    <p>My research focuses on machine learning and signal processing for real-world time-series data, with current work on interpretable AI-ECG systems and LLM-based explanations. My broader work spans efficient deep learning and practical ML systems, from model compression and edge inference to low-level implementation.</p>
    <p class="profile-header__links"><a href="mailto:ege.ozkoc@pitt.edu">Email</a> · <a href="/assets/docs/Ege_Ozkoc_Resume.pdf" target="_blank" rel="noopener">Resume</a> · <a href="https://scholar.google.com/citations?user=OqtWjZUAAAAJ" target="_blank" rel="noopener">Google Scholar</a> · <a href="https://github.com/egeozkoc" target="_blank" rel="noopener">GitHub</a> · <a href="https://www.linkedin.com/in/egeozkoc/" target="_blank" rel="noopener">LinkedIn</a></p>
  </div>
</header>

<section id="selected-work" class="content-section">
  <h2>Selected Work</h2>
  <div class="work-list">
    <div class="work-item">
      <figure class="work-item__media work-item__media--wide"><a href="/assets/images/projects/interpretable-ai-ecg-llm-concept-diagram.png" target="_blank" rel="noopener"><img src="/assets/images/projects/interpretable-ai-ecg-llm-concept-diagram.png" alt="Conceptual illustration, not experimental data: ECG signal evidence feeds model output (prediction and attributions), which feeds an LLM explanation." loading="lazy"></a></figure>
      <div class="work-item__body">
        <h3>Interpretable AI-ECG with LLMs</h3>
        <p>I develop evidence-grounded LLM pipelines for interpreting AI-ECG predictions, combining waveform evidence, model outputs, and saliency/SHAP attributions. This work has led to a U.S. provisional patent application.</p>
        
      </div>
    </div>
    <div class="work-item">
      <figure class="work-item__media "><a href="/assets/images/projects/parkinsons-tremor-fft-thesis-fig2-6.png" target="_blank" rel="noopener"><img src="/assets/images/projects/parkinsons-tremor-fft-thesis-fig2-6.png" alt="Magnitude of the FFT of a wrist accelerometer recording of a tremor, with a dominant peak near 5 Hz." loading="lazy"></a><figcaption>Tremor spectrum (master's thesis)</figcaption></figure>
      <div class="work-item__body">
        <h3>Real-Time Parkinson's Tremor Detection</h3>
        <p>At Fraunhofer IIS, I developed a lightweight 1D CNN for Parkinson's tremor detection using wrist-worn IMU data. It achieved approximately 0.91 AUC on unseen subjects, while 8-bit quantization reduced model size by approximately 75% with negligible performance loss.</p>
        <p class="work-item__links"><a href="https://doi.org/10.1109/MLSP62443.2025.11204316" target="_blank" rel="noopener">Paper</a> · <a href="/assets/docs/Master_s_Thesis_Ege_Ozkoc.pdf" target="_blank" rel="noopener">Thesis</a></p>
      </div>
    </div>
    <div class="work-item">
      <figure class="work-item__media "><a href="/assets/images/projects/inverse-ecg-forward-inverse-overview.png" target="_blank" rel="noopener"><img src="/assets/images/projects/inverse-ecg-forward-inverse-overview.png" alt="Illustration of the forward and inverse ECG problems: heart-surface potential map on the left, body-surface potential map on the right." loading="lazy"></a></figure>
      <div class="work-item__body">
        <h3>Bayesian Inverse ECG Reconstruction</h3>
        <p>I used Bayesian MAP estimation to reconstruct cardiac electrical activity from body-surface measurements, evaluating prior models derived from measured and simulated data. This work resulted in two peer-reviewed conference publications.</p>
        <p class="work-item__links"><a href="https://doi.org/10.1109/SIU55565.2022.9864708" target="_blank" rel="noopener">2022 paper</a> · <a href="https://doi.org/10.23919/Measurement52780.2021.9446831" target="_blank" rel="noopener">2021 paper</a></p>
      </div>
    </div>
    <div class="work-item">
      <figure class="work-item__media work-item__media--code"><a href="/assets/images/projects/mini-numpy-array2d-code-excerpt.png" target="_blank" rel="noopener"><img src="/assets/images/projects/mini-numpy-array2d-code-excerpt.png" alt="C++ source excerpt from mini-numpy: the element-wise in-place multiplication operator of the Array2D class." loading="lazy"></a><figcaption>Excerpt from mini-numpy (Array2D.hpp).</figcaption></figure>
      <div class="work-item__body">
        <h3>ML Systems &amp; Open Source</h3>
        <p>I build ML systems and implementations beyond high-level model APIs, including a deep-learning framework from scratch, a C++ array library, offline Whisper dictation using MLX, and merged bitsandbytes contributions.</p>
        <p class="work-item__links"><a href="https://github.com/egeozkoc/deep-learning-from-scratch" target="_blank" rel="noopener">deep-learning-from-scratch</a> · <a href="https://github.com/egeozkoc/mini-numpy" target="_blank" rel="noopener">mini-numpy</a> · <a href="https://github.com/egeozkoc/murmur" target="_blank" rel="noopener">murmur</a> · <a href="https://github.com/bitsandbytes-foundation/bitsandbytes/pulls?q=is%3Apr+author%3Aegeozkoc" target="_blank" rel="noopener">bitsandbytes contributions</a></p>
      </div>
    </div>
  </div>
</section>

<section id="projects" class="content-section">
  <h2>Additional Projects</h2>
  <ul class="project-list">
    <li><a href="https://github.com/egeozkoc/lora-from-scratch" target="_blank" rel="noopener">lora-from-scratch</a> — a minimal PyTorch implementation of LoRA, including low-rank adapters, injection into existing linear layers, weight merging, and a small LLM fine-tuning experiment.</li>
    <li><a href="https://github.com/egeozkoc/clustering-toolbox" target="_blank" rel="noopener">clustering-toolbox</a> — a Streamlit application for clustering and exploring tabular data with KMeans, Gaussian mixture models, DBSCAN, PCA, and t-SNE.</li>
  </ul>
</section>

<section id="publications" class="content-section">
  <h2>Publications</h2>
  <ol class="publication-list">
    <li><strong>Ege Ozkoc</strong>, Tobias Sebastian Zech, Norman Pfeiffer, Stephan Göbl, and Jürgen Frickel. “Compressed and Lightweight CNN for Real-Time Parkinson’s Tremor Detection from Wearable IMU Data.” <em>2025 IEEE International Workshop on Machine Learning for Signal Processing (MLSP)</em>, Istanbul, Türkiye, 2025. <a href="https://doi.org/10.1109/MLSP62443.2025.11204316" target="_blank" rel="noopener">Paper</a></li>
    <li><strong>Ege Ozkoc</strong> and Yesim Serinagaoglu Dogrusoz. “Bayesian MAP Solution of the Inverse ECG Problem with Sinus Rhythm Data: Evaluation of Simulated Training Sets.” <em>30th IEEE Signal Processing and Communications Applications Conference (SIU)</em>, 2022. <a href="https://doi.org/10.1109/SIU55565.2022.9864708" target="_blank" rel="noopener">Paper</a></li>
    <li><strong>Ege Ozkoc</strong>, Elifnur Sunger, Kutay Ugurlu, and Yesim Serinagaoglu Dogrusoz. “Prior Model Selection in Bayesian MAP Estimation-Based ECG Reconstruction.” <em>13th International Conference on Measurement</em>, 2021. <a href="https://doi.org/10.23919/Measurement52780.2021.9446831" target="_blank" rel="noopener">Paper</a></li>
  </ol>
</section>

<section id="experience" class="content-section">
  <h2>Experience</h2>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/pitt.svg" alt="University of Pittsburgh" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>University of Pittsburgh</h3><p class="entry__position">PhD Researcher</p><p class="entry__group">Signal Processing and Statistical Learning Lab (SPSL)</p></div>
    <p class="entry__date">Aug 2025–present</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/fraunhofer.svg" alt="Fraunhofer IIS" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Fraunhofer Institute for Integrated Circuits IIS</h3><p class="entry__position">Master's Thesis Researcher</p><p class="entry__group">Medical Sensors and Analytics Group</p></div>
    <p class="entry__date">Mar 2024–Nov 2024</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/fau.svg" alt="Friedrich-Alexander-Universität Erlangen-Nürnberg" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>FAU Erlangen-Nürnberg</h3><p class="entry__position">Research Intern &amp; Student Assistant</p><p class="entry__group">Machine Learning and Data Analytics Lab</p></div>
    <p class="entry__date">Jun 2023–Apr 2024</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/uk-erlangen.svg" alt="Universitätsklinikum Erlangen" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Universitätsklinikum Erlangen</h3><p class="entry__position">Student Research Assistant</p><p class="entry__group">Department of Radiology</p></div>
    <p class="entry__date">Feb 2023–Oct 2023</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/metu.svg" alt="Middle East Technical University" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Middle East Technical University</h3><p class="entry__position">Undergraduate Researcher</p><p class="entry__group">Heart Research Laboratory</p></div>
    <p class="entry__date">Jul 2020–Jul 2022</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/aselsan.svg" alt="ASELSAN" width="36" height="36" loading="lazy"></span>
    <div class="entry__body">
      <h3>ASELSAN</h3>
      <div class="entry__stint">
        <p class="entry__position">Part-time Candidate Engineer</p>
        <p class="entry__group">Radar &amp; Electronic Warfare <span class="entry__stint-date">· Nov 2021–Jan 2022</span></p>
      </div>
      <div class="entry__stint">
        <p class="entry__position">Engineering Intern</p>
        <p class="entry__group">Defense Systems Technologies <span class="entry__stint-date">· Jul 2021–Aug 2021</span></p>
      </div>
    </div>
    <p class="entry__date">2021–2022</p>
  </div>
</section>

<section id="education" class="content-section education-section">
  <h2>Education</h2>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/pitt.svg" alt="University of Pittsburgh" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>University of Pittsburgh</h3><p class="entry__role">PhD in Electrical and Computer Engineering</p></div>
    <p class="entry__date">2025–present</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/fau.svg" alt="Friedrich-Alexander-Universität Erlangen-Nürnberg" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>FAU Erlangen-Nürnberg</h3><p class="entry__role">MSc in Medical Engineering</p></div>
    <p class="entry__date">2022–2024</p>
  </div>
  <div class="entry">
    <span class="entry__logo"><img src="/assets/images/logos/metu.svg" alt="Middle East Technical University" width="36" height="36" loading="lazy"></span>
    <div class="entry__body"><h3>Middle East Technical University</h3><p class="entry__role">BSc in Electrical and Electronics Engineering</p></div>
    <p class="entry__date">2016–2022</p>
  </div>
</section>

