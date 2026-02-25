---
title: "MIAM"
permalink: /publications/miam/
author_profile: false
layout: splash
sidebar: false

custom_css:
  - "academic_template/bulma.min.css"
  - "academic_template/bulma-carousel.min.css"
  - "academic_template/bulma-slider.min.css"
  - "academic_template/index.css"
  - "academic_template/fontawesome.all.min.css"

custom_js:
  - "academic_template/bulma-carousel.min.js"
  - "academic_template/bulma-carousel.js"
  - "academic_template/bulma-slider.min.js"
  - "academic_template/bulma-slider.js"
  - "academic_template/index.js"
  - "academic_template/fontawesome.all.min.js"
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<link rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/academicons@1.9.4/css/academicons.min.css"
      integrity="sha384-FQC0RRnwLGAeE0vz3BXhosES7aq6v3cZlK1KJ71Z5gB8HuF6I4BhJwkdoUJ0W6qL"
      crossorigin="anonymous">

  <!-- Scroll to Top Button -->
  <button class="scroll-to-top" onclick="scrollToTop()" title="Scroll to top" aria-label="Scroll to top">
    <i class="fas fa-chevron-up"></i>
  </button>

  <!-- More Works Dropdown -->
<!-- <div class="more-works-container tooltip" data-tooltip="More publications">
  <a href="https://www.epfl.ch/labs/eceo/eceo/publications" 
     target="_blank" 
     rel="noopener noreferrer">
    <button class="more-works-btn">
      <img src="{{ '/assets/images/academic_template/eceo.png' | relative_url }}" width="70" alt="Icon" class="btn-icon">
    </button>
  </a>
</div> -->

<main id="main-content">
  <section class="hero hero-with-bg">
    <div class="hero-image-container">
      <!-- TODO: Change background image. Set opacitiy to 0 if you don't want an image background -->
      <img style="opacity: 0;" src="{{ '/assets/images/academic_template/background.png' | relative_url }}" alt="Background picture">
    </div>

<div class="hero-body">
<div class="container is-max-desktop">
<div class="columns is-centered">
<div class="column has-text-centered">
<div class="hero-text-wrapper">
<!-- TODO: Replace paper name and authors -->
<h1 class="title is-1 publication-title">MIAM</h1>
<h2 class="title is-2 publication-title">Modality Imbalance-Aware Masking for Multimodal Ecological Applications</h2>

<div class="is-size-6 publication-authors">
  <span class="author-block stacked">
    <img class="author-avatar" src="/assets/images/bio-photo.jpeg" alt="Robin Zbinden">
    <a href="/" target="_blank" style="text-decoration:none;">Robin Zbinden*,</a>
  </span>
  <span class="author-block stacked">
    <img class="author-avatar" src="/assets/images/authors/wesley.jpg" alt="Wesley Monteith-Finas">
    <a href="https://www.linkedin.com/in/wesley-monteith-959bab237/?originalSubdomain=ch" target="_blank" style="text-decoration:none;">Wesley Monteith-Finas*,</a>
  </span>
  <span class="author-block stacked">
    <img class="author-avatar" src="/assets/images/authors/gencer.png" alt="Gencer Sumbul">
    <a href="https://scholar.google.com/citations?user=beJ28JMAAAAJ&hl=tr" target="_blank" style="text-decoration:none;">Gencer Sumbul,</a>
  </span>
  <span class="author-block stacked">
    <img class="author-avatar" src="/assets/images/authors/nina.png" alt="Nina van Tiel">
    <a href="https://scholar.google.com/citations?user=pCOoHuAAAAAJ&hl=en" target="_blank" style="text-decoration:none;">Nina van Tiel,</a>
  </span>
  <span class="author-block stacked">
    <img class="author-avatar" src="/assets/images/authors/chiara.png" alt="Chiara Vanalli">
    <a href="https://chiaravanalli.weebly.com/" target="_blank" style="text-decoration:none;">Chiara Vanalli,</a>
  </span>
  <span class="author-block stacked">
    <img class="author-avatar" src="/assets/images/authors/devis.png" alt="Devis Tuia">
    <a href="https://scholar.google.com/citations?hl=en&user=p3iJiLIAAAAJ" target="_blank" style="text-decoration:none;">Devis Tuia</a>
  </span>
  </div>
  <div class="is-size-6 publication-authors" style="margin-top: -2rem;">
  <span class="author-block"><br>ICLR 2026</span>
  </div>
</div>

<!-- TODO: Replace with your pdf, supplementary, github, etc. -->
<!--  To delete a block if not applicable: from span class="link-block" to </span>.  -->
<div class="column has-text-centered">
<div class="publication-links">
  <span class="link-block">
    <a href="https://openreview.net/forum?id=oljjAkgZN4" target="_blank"
      class="external-link button is-normal is-rounded is-dark">
      <span class="icon">
        <i class="fas fa-file-pdf"></i>
      </span>
      <span>Paper</span>
    </a>
  </span>

  <span class="link-block">
    <a href="https://github.com/zbirobin/MIAM" target="_blank"
      class="external-link button is-normal is-rounded is-dark">
      <span class="icon">
        <i class="fab fa-github"></i>
      </span>
      <span>Code</span>
    </a>
  </span>

  <span class="link-block" style="display:none;">
    <a href="" target="_blank"
      class="external-link button is-normal is-rounded is-dark">
      <span class="icon">
        <i class="fas fa-file-alt"></i>
      </span>
      <span>arXiv</span>
    </a>
  </span>

  <span class="link-block">
    <a href="https://huggingface.co/zbirobin/MIAM" target="_blank"
      class="external-link button is-normal is-rounded is-dark">
      <span class="icon">
        <i class="fas fa-download"></i>
      </span>
      <span>Data</span>
    </a>
  </span>

  <span class="link-block" style="display:none;">
    <a href="https://<POSTER LINK>" target="_blank"
      class="external-link button is-normal is-rounded is-dark">
      <span class="icon">
        <i class="fas fa-image"></i>
      </span>
      <span>Poster</span>
    </a>
  </span>

  <span class="link-block" style="display:none;">
    <a href="https://<VIDEO LINK>" target="_blank"
      class="external-link button is-normal is-rounded is-dark">
      <span class="icon">
        <i class="fas fa-image"></i>
      </span>
      <span>Video</span>
    </a>
  </span>

</div> <!-- publication-links -->
</div> <!-- column has-text-centered -->

</div> <!-- column -->
</div> <!-- columns -->
</div> <!-- container -->
</div> <!-- hero-body -->

  </section>
</main>


<section class="section" style="padding-top: 0rem;">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">TL;DR</h2>

        <div class="content has-text-justified">
          <p>
            We introduce <strong>MIAM (Modality Imbalance-Aware Masking)</strong>, a dynamic masking strategy that counteracts modality imbalance using modality-specific performance and learning signals.
            Models trained with MIAM can be evaluated under <strong><em>any combination of input <span class="token-term" data-token-definition="A token is the smallest input unit processed by the model (for example, one tabular variable, one time step, or one image patch).">tokens</span></em></strong>, supporting fine-grained contribution analysis across and within modalities, while improving robustness to missing data in ecological applications.
          </p>
        </div>

        <div style="text-align: justify; margin: 40px 0;">
          <img src="{{ '/assets/images/miam/miam_main.png' | relative_url }}" alt="MIAM main figure" style="max-width: 100%; height: auto;">
          <p class="is-size-9" style="margin-top: 8px;">
            <strong>Overview of MIAM.</strong>
            <strong>(Left)</strong> Each token of modality <em>m</em> is masked with probability <strong>p</strong><em><sub>m</sub></em>, sampled from a mixture of product beta distributions.
            <strong>(Right)</strong> The distribution parameters are modulated by <em>ρ<sub>s<sub>m</sub></sub></em> and <em>ρ<sub>d<sub>m</sub></sub></em>, derived from the per-modality performance <em>s<sub>m</sub></em> and its absolute derivative <em>d<sub>m</sub></em>.
            Modalities with strong and stable performance are masked more frequently to mitigate modality imbalance.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Overview -->
<section class="section hero is-light" style="padding-top: 0.5rem;">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Introduction</h2>

        <div class="content has-text-justified">
          <p>
            Ecological modeling underpins conservation, climate adaptation, and environmental management.
            Modern ecological datasets are inherently <strong>multimodal</strong>, integrating heterogeneous signals such as environmental tabular variables 📊, climate time series 📈, bioacoustics 🔊, natural images 📷, and satellite imagery 🛰️.
          </p>

          <p>
            Learning and inference in this setting are challenging because:
          </p>

          <ul>
            <li><strong>inputs are often incomplete</strong>, with missing data occurring either at the modality level or within modalities;</li>
            <li><strong>modalities contribute unequally</strong>, leading to modality imbalance during optimization;</li>
            <li><strong>interpretability is essential</strong>, both across and within modalities.</li>
          </ul>

          <p>
            By exposing models to incomplete inputs during training, <strong>masking strategies</strong> provide a principled approach to improving robustness to missing data while enabling structured analysis of input contributions.
          </p>
        </div>

      </div>
    </div>
  </div>
</section>

<!-- Why MIAM -->
<section class="section" style="padding-bottom: 0rem;">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Limitations of Existing Masking Strategies</h2>

        <div class="content has-text-justified">
          <p>
            However, most multimodal masking strategies are fixed and underexplore the space of possible input subsets. 
            As a result, they only partially improve robustness and fail to explicitly address modality imbalance, 
            where dominant modalities hinder the learning of complementary ones.
          </p>
          <style>
            .token-term {
              text-decoration: underline dotted;
              text-underline-offset: 2px;
              cursor: help;
            }
            #token-definition-tooltip {
              position: fixed;
              z-index: 9999;
              max-width: 300px;
              padding: 0.55rem 0.7rem;
              border-radius: 8px;
              border: 1px solid #d8d8d8;
              background: #ffffff;
              color: #1a1a1a;
              font-size: 0.9rem;
              line-height: 1.35;
              box-shadow: 0 8px 22px rgba(0, 0, 0, 0.14);
              pointer-events: none;
              opacity: 0;
              transform: translateY(3px);
              transition: opacity 100ms ease, transform 100ms ease;
            }
            #token-definition-tooltip.is-visible {
              opacity: 1;
              transform: translateY(0);
            }
          </style>
          <div id="token-definition-tooltip" role="tooltip" aria-hidden="true"></div>
          <p>
            First, we formalize masking strategies as <strong>probability distributions over the unit hypercube</strong>, 
            where each dimension corresponds to a modality. 
            With <em>M</em> modalities, we define a masking probability vector p = (p<sub><em>1</em></sub>, ..., p<sub><em>M</em></sub>) ∈ [0,1]<sup><em>M</em></sup>, where p<sub><em>m</em></sub> denotes the probability of masking a <span class="token-term" data-token-definition="A token is the smallest input unit processed by the model (for example, one tabular variable, one time step, or one image patch).">token</span> of modality <em>m</em>.
            A masking strategy is then a probability distribution 𝒟 over [0,1]<sup><em>M</em></sup> from which p is sampled during training.
          </p>

          <p>
            Existing approaches can be interpreted within this unified framework:
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section pt-0" style="padding-bottom: 0.5rem;">
  <div style="display: flex; justify-content: center; width: 100%;">
    <iframe id="hypercubes-frame"
            src="/assets/html/hypercubes.html"
            style="width: 100%; max-width: 900px; min-height: 1300px; border: none;"
            frameborder="0"
            scrolling="no">
    </iframe>
  </div>
</section>

<script>
(function () {
  const frame = document.getElementById('hypercubes-frame');
  if (!frame) return;

  function setFrameHeight(height) {
    const h = Number(height);
    if (!Number.isFinite(h) || h <= 0) return;
    frame.style.height = `${Math.ceil(h)}px`;
  }

  window.addEventListener('message', function (event) {
    if (!event.data || typeof event.data !== 'object') return;
    if (!frame.contentWindow || event.source !== frame.contentWindow) return;
    if (!Object.prototype.hasOwnProperty.call(event.data, 'iframeHeight')) return;
    setFrameHeight(event.data.iframeHeight);
  });
})();
</script>

<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">MIAM 😋</h2>

        <div class="content has-text-justified">
          <p>
            MIAM provides a principled alternative built on three key properties:
          </p>

          <ul>
            <li>
              <strong>Full support:</strong>  Masking probabilities are sampled over the entire 
              hypercube, allowing <em>any</em> combination of masked and unmasked tokens 
              to occur during training.
            </li>

            <li>
              <strong>Corner prioritization:</strong> Rather than sampling uniformly, MIAM uses a 
              <em>corner-anchored mixture of product beta distributions</em>. Each mixture component 
              concentrates probability mass near one of the <em>2<sup>M</sup></em> hypercube corners, 
              promoting training on informative subsets (e.g., single-modality or near-complete inputs).
            </li>

            <li>
              <strong>Imbalance awareness:</strong> MIAM dynamically adjusts the sharpness of these 
              beta distributions based on modality-specific learning dynamics. Modalities with 
              high and stable unimodal performance are masked more frequently, encouraging 
              the model to better optimize slower-learning or underutilized modalities.
            </li>
          </ul>

          <p>
            The following interactive visualization illustrates how these principles translate into a dynamic masking distribution during training:
          </p>

        </div>
      </div>
    </div>
  </div>


<section class="section pt-0" style="padding-bottom: 0.5rem;">
  <div style="display: flex; justify-content: center; width: 100%;">
    <iframe id="miam-interactive-frame"
            src="/assets/html/miam_interactive.html"
            style="width: 100%; max-width: 900px; min-height: 1100px; border: none;"
            frameborder="0"
            scrolling="no">
    </iframe>
  </div>
</section>

<script>
(function () {
  const frame = document.getElementById('miam-interactive-frame');
  if (!frame) return;

  function setFrameHeight(height) {
    const h = Number(height);
    if (!Number.isFinite(h) || h <= 0) return;
    frame.style.height = `${Math.ceil(h)}px`;
  }

  window.addEventListener('message', function (event) {
    if (!event.data || typeof event.data !== 'object') return;
    if (!frame.contentWindow || event.source !== frame.contentWindow) return;
    if (!Object.prototype.hasOwnProperty.call(event.data, 'iframeHeight')) return;
    setFrameHeight(event.data.iframeHeight);
  });
})();
</script>
</section>


<!-- Main contributions -->
<section class="section hero is-light">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Main contributions ✨</h2>

        <div class="content has-text-justified">
          <ul>
            <li><strong>Dynamic, imbalance-aware masking (MIAM)</strong> that mitigates modality imbalance, promotes complementary multimodal learning, and improves robustness to missing data in ecological applications ⚖️ </li>
            <li><strong>Consistent improvements on ecological multimodal benchmarks</strong> (GeoPlant and TaxaBench), especially for under-optimized modalities 📊 </li>
            <li><strong>Fine-grained interpretability</strong> across and within modalities (variables, time segments, image patches) 🔎 </li>
          </ul>

          <p><strong>
            For full methodological details and experimental results, read the 
            <a href="https://openreview.net/forum?id=oljjAkgZN4" target="_blank">paper 📄</a></strong>
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- End paper overview -->

<!-- Citation section -->

<!--BibTex citation -->
  <section class="section" id="BibTeX">
    <div class="container is-max-desktop content">
      <div class="bibtex-header">
        <h2 class="title">Citation</h2>
        <button class="copy-bibtex-btn" onclick="copyBibTeX()" title="Copy BibTeX to clipboard">
          <i class="fas fa-copy"></i>
          <span class="copy-text">Copy</span>
        </button>
      </div>
      <pre id="bibtex-code"><code>@inproceedings{
    zbinden2026miam,
    title={MIAM: Modality Imbalance-Aware Masking for Multimodal Ecological Applications},
    author={Robin Zbinden and Wesley Monteith-Finas and Gencer Sumbul and Nina van Tiel and Chiara Vanalli and Devis Tuia},
    booktitle={International Conference on Learning Representations (ICLR)},
    year={2026},
    url={https://openreview.net/forum?id=oljjAkgZN4}
}</code></pre>
    </div>
</section>
<!--End BibTex citation -->

  <footer class="footer">
  <div class="container">
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content">

          <p>
            This page was built using the <a href="https://github.com/eliahuhorwitz/Academic-project-page-template" target="_blank">Academic Project Page Template</a> which was adopted from the <a href="https://nerfies.github.io" target="_blank">Nerfies</a> project page. This website is licensed under a <a rel="license"  href="http://creativecommons.org/licenses/by-sa/4.0/" target="_blank">Creative
            Commons Attribution-ShareAlike 4.0 International License</a>.
          </p>

        </div>
      </div>
    </div>
  </div>
</footer>

<!-- Statcounter tracking code -->
  
<!-- You can add a tracker to track page visits by creating an account at statcounter.com -->

<!-- End of Statcounter Code -->

<script>
(function () {
  const tokenDefinitionTooltip = document.getElementById('token-definition-tooltip');
  if (!tokenDefinitionTooltip) return;

  const OFFSET_X = 14;
  const OFFSET_Y = 14;

  function placeTooltip(event) {
    const x = event.clientX + OFFSET_X;
    const y = event.clientY + OFFSET_Y;
    const pad = 10;
    const maxX = window.innerWidth - tokenDefinitionTooltip.offsetWidth - pad;
    const maxY = window.innerHeight - tokenDefinitionTooltip.offsetHeight - pad;
    tokenDefinitionTooltip.style.left = `${Math.max(pad, Math.min(x, maxX))}px`;
    tokenDefinitionTooltip.style.top = `${Math.max(pad, Math.min(y, maxY))}px`;
  }

  document.querySelectorAll('.token-term').forEach((el) => {
    el.addEventListener('mouseenter', (event) => {
      const definition = el.getAttribute('data-token-definition');
      if (!definition) return;
      tokenDefinitionTooltip.textContent = definition;
      tokenDefinitionTooltip.classList.add('is-visible');
      tokenDefinitionTooltip.setAttribute('aria-hidden', 'false');
      placeTooltip(event);
    });

    el.addEventListener('mousemove', placeTooltip);

    el.addEventListener('mouseleave', () => {
      tokenDefinitionTooltip.classList.remove('is-visible');
      tokenDefinitionTooltip.setAttribute('aria-hidden', 'true');
    });
  });
})();
</script>