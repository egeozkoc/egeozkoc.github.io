---
title: "Ege Ozkoc"
permalink: /
layout: portfolio
excerpt: "PhD student at the University of Pittsburgh working on machine learning, biomedical signals, and efficient AI systems."
---

<section class="hero" aria-labelledby="intro-title">
  <div class="hero__copy">
    <p class="eyebrow">University of Pittsburgh · Electrical &amp; Computer Engineering</p>
    <h1 id="intro-title">Ege Ozkoc</h1>
    <p class="hero__role">PhD student working at the intersection of machine learning, biomedical signals, and efficient AI systems.</p>
    <p class="hero__summary">My work ranges from evidence-grounded interpretation of AI-ECG models to embedded tremor detection and research software built from first principles.</p>
    <div class="hero__actions">
      <a class="button button--primary" href="#research">Selected work</a>
      <a class="button button--quiet" href="/assets/docs/Ege_Ozkoc_CV.pdf" target="_blank" rel="noopener">Download CV <span aria-hidden="true">↗</span></a>
    </div>
  </div>
  <div class="hero__portrait-wrap">
    <img class="hero__portrait" src="/assets/images/profile.jpeg" alt="Ege Ozkoc" width="586" height="752">
  </div>
</section>

<section class="focus-strip" aria-label="Research focus">
  <div><span class="focus-strip__label">Current focus</span><strong>Trustworthy clinical AI</strong></div>
  <div><span class="focus-strip__label">Methods</span><strong>Machine learning &amp; signal processing</strong></div>
  <div><span class="focus-strip__label">Systems</span><strong>Efficient and deployable AI</strong></div>
</section>

<section id="research" class="section section--research" aria-labelledby="research-title">
  <div class="section__heading">
    <p class="eyebrow">Research</p>
    <h2 id="research-title">Work shaped by evidence, constraints, and real signals.</h2>
  </div>
  <div class="work-list">
    <article class="work-item">
      <p class="work-item__meta">University of Pittsburgh · 2025–present</p>
      <h3>Evidence-grounded explanations for AI-ECG models</h3>
      <p>I am developing methods that turn model outputs into human-readable explanations while keeping the language tied to model evidence such as saliency maps and SHAP attributions. The goal is interpretation, not independent clinical diagnosis.</p>
      <p class="work-item__note">This work contributed to a U.S. provisional patent.</p>
    </article>
    <article class="work-item">
      <p class="work-item__meta">Fraunhofer IIS · 2024</p>
      <h3>Real-time Parkinson's tremor detection</h3>
      <p>I designed and evaluated a lightweight 1D CNN for wrist-worn IMU data, comparing it with FFT-based, SVM, and Random Forest baselines under subject-independent validation. The model achieved an AUC above 0.90 on unseen patients.</p>
      <p class="work-item__note">8-bit quantization and structured pruning reduced model size by about 75% with less than 0.1% loss in accuracy.</p>
    </article>
    <article class="work-item">
      <p class="work-item__meta">Middle East Technical University · 2020–2022</p>
      <h3>Inverse electrocardiography</h3>
      <p>I worked on noninvasive electrocardiographic imaging for localizing premature ventricular contractions, with a focus on Bayesian MAP estimation, prior-model selection, and noise reduction.</p>
      <a class="text-link" href="#publications">Related publications <span aria-hidden="true">↓</span></a>
    </article>
  </div>
</section>

<section id="projects" class="section section--projects" aria-labelledby="projects-title">
  <div class="section__heading section__heading--split">
    <div>
      <p class="eyebrow">Selected projects</p>
      <h2 id="projects-title">I build to understand the details.</h2>
    </div>
    <p>Small, public projects that make my implementation work easy to inspect.</p>
  </div>
  <div class="project-grid">
    <article class="project-card">
      <p class="project-card__type">C++ · pybind11</p>
      <h3>mini-numpy</h3>
      <p>A NumPy-like N-dimensional array library in modern C++, with Python bindings. It includes array operations, reductions, reshaping, matrix multiplication, and tests.</p>
      <a class="text-link" href="https://github.com/egeozkoc/mini-numpy" target="_blank" rel="noopener">View repository <span aria-hidden="true">↗</span></a>
    </article>
    <article class="project-card">
      <p class="project-card__type">Python · NumPy · SciPy</p>
      <h3>Deep learning from scratch</h3>
      <p>A neural-network framework with manual forward and backward passes for convolutional, recurrent, and fully connected layers, along with regularization and optimizers.</p>
      <a class="text-link" href="https://github.com/egeozkoc/deep-learning-from-scratch" target="_blank" rel="noopener">View repository <span aria-hidden="true">↗</span></a>
    </article>
    <article class="project-card">
      <p class="project-card__type">Python · Whisper · MLX</p>
      <h3>Murmur</h3>
      <p>A local macOS dictation app built around Whisper. It runs on-device, supports a global hotkey, and uses MLX acceleration on Apple Silicon.</p>
      <a class="text-link" href="https://github.com/egeozkoc/murmur" target="_blank" rel="noopener">View repository <span aria-hidden="true">↗</span></a>
    </article>
  </div>
</section>

<section id="publications" class="section section--publications" aria-labelledby="publications-title">
  <div class="section__heading section__heading--split">
    <div>
      <p class="eyebrow">Publications</p>
      <h2 id="publications-title">Selected peer-reviewed work.</h2>
    </div>
    <a class="text-link" href="https://scholar.google.com/citations?user=OqtWjZUAAAAJ" target="_blank" rel="noopener">Google Scholar <span aria-hidden="true">↗</span></a>
  </div>
  <ol class="publication-list">
    <li>
      <p><strong>E. Ozkoc</strong>, T. S. Zech, N. Pfeiffer, S. Gobl, and J. Frickel. “Compressed and Lightweight CNN for Real-Time Parkinson's Tremor Detection from Wearable IMU Data.” <em>IEEE MLSP</em>, 2025.</p>
      <a class="text-link" href="https://doi.org/10.1109/MLSP62443.2025.11204316" target="_blank" rel="noopener">DOI <span aria-hidden="true">↗</span></a>
    </li>
    <li>
      <p><strong>E. Ozkoc</strong> and Y. Serinagaoglu Dogrusoz. “Bayesian MAP Solution of the Inverse ECG Problem with Sinus Rhythm Data: Evaluation of Simulated Training Sets.” <em>IEEE SIU</em>, 2022.</p>
      <a class="text-link" href="https://doi.org/10.1109/SIU55565.2022.9864708" target="_blank" rel="noopener">DOI <span aria-hidden="true">↗</span></a>
    </li>
    <li>
      <p><strong>E. Ozkoc</strong>, E. Sunger, K. Ugurlu, and Y. Serinagaoglu Dogrusoz. “Prior Model Selection in Bayesian MAP Estimation-Based ECG Reconstruction.” <em>Measurement</em>, 2021.</p>
      <a class="text-link" href="https://doi.org/10.23919/Measurement52780.2021.9446831" target="_blank" rel="noopener">DOI <span aria-hidden="true">↗</span></a>
    </li>
  </ol>
</section>

<section class="section section--background" aria-labelledby="background-title">
  <div class="section__heading">
    <p class="eyebrow">Background</p>
    <h2 id="background-title">Engineering training across computation and medicine.</h2>
  </div>
  <div class="education-grid">
    <article><p>2025–present</p><h3>University of Pittsburgh</h3><span>PhD, Electrical and Computer Engineering</span></article>
    <article><p>2022–2024</p><h3>FAU Erlangen-Nurnberg</h3><span>MSc, Medical Engineering</span></article>
    <article><p>2016–2022</p><h3>Middle East Technical University</h3><span>BSc, Electrical and Electronics Engineering</span></article>
  </div>
</section>

<section class="contact" aria-labelledby="contact-title">
  <div>
    <p class="eyebrow">Contact</p>
    <h2 id="contact-title">Get in touch.</h2>
  </div>
  <div class="contact__links">
    <a href="mailto:ege.ozkoc@pitt.edu">ege.ozkoc@pitt.edu</a>
    <a href="https://www.linkedin.com/in/egeozkoc/" target="_blank" rel="noopener">LinkedIn <span aria-hidden="true">↗</span></a>
    <a href="https://github.com/egeozkoc" target="_blank" rel="noopener">GitHub <span aria-hidden="true">↗</span></a>
  </div>
</section>
