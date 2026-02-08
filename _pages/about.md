---
layout: about
title: About
permalink: /
# nav: true
---

<!-- ## <span style="color: #e569d4ff;"><strong>Frances Fengyi Yang</strong></span> -->

**Bridging quantum computing and computer vision — from quantum optimization to robust geometry and machine learning.**

<p align="left">
  <a class="btn btn-outline-secondary btn-sm" href="mailto:{{ site.email | default: 'fengyi.yang@adelaide.edu.au' }}">Email</a>
  <!-- <a class="btn btn-outline-secondary btn-sm" href="https://scholar.google.com/">Google Scholar</a> -->
  <!-- <a class="btn btn-outline-secondary btn-sm" href="https://github.com/{{ site.github_username | default: 'chenqi008' }}">GitHub</a> -->
  <a class="btn btn-secondary btn-sm" href="https://www.linkedin.com/in/frances-fengyi-yang/" target="_blank"> LinkedIn</a>
</p>

---

### About Me

<div style="height: 1rem;"></div>
<div class="row align-items-start">
  <div class="col-md-3 mb-3">
    <img src="{{ '/assets/img/IMG_5740_Original.jpg' | relative_url }}" class="img-fluid rounded mb-3" alt="Profile photo">

    <h6 class="text-muted">Hobby</h6>

    <div style="display:flex; flex-wrap:wrap; gap:0.4rem;">
      <a class="badge badge-pill badge-light" style="border:1px solid var(--global-divier-color);">📷 Photography</a>
      <a class="badge badge-pill badge-light" style="border:1px solid var(--global-divier-color);">🥘 Food</a>
      <a class="badge badge-pill badge-light" style="border:1px solid var(--global-divier-color);">🎾 Tennis</a>
      <a class="badge badge-pill badge-light" style="border:1px solid var(--global-divier-color);">🚘 Road Trips</a>
      <a class="badge badge-pill badge-light" style="border:1px solid var(--global-divier-color);">🤿 Water Activities</a>
    </div>
  </div>
  <div class="col-md-9">
    <p>
      Frances Yang is a final-year PhD candidate at the <a href="https://adelaideuni.edu.au/research/australian-institute-for-machine-learning/" target="_blank">Australian Institute for Machine Learning (AIML)</a>, The University of Adelaide, supervised by <a href="https://www.ai4space.group/" target="_blank">Prof. Tat-Jun Chin</a> and <a href="https://cs.adelaide.edu.au/~frank/" target="_blank">Prof. Frank Neumann</a>. Completing her PhD in 2026, she focuses on developing quantum algorithms for foundational problems in machine learning and computer vision, with a particular emphasis on quantum-enhanced geometric reasoning and optimization. She has experience working with both annealing-based and gate-based quantum platforms and has implemented scalable solutions for perception and decision-making tasks.
    </p>
    <p>
      Frances is eager to join a team advancing quantum hardware, where she can contribute to showcasing hardware capabilities and improving quantum-classical workflows through rigorous algorithmic benchmarking and performance analysis. With a strong foundation in algorithm development, hands-on Python programming, and experience translating research into practical systems, she brings a deep commitment to pushing the boundaries of quantum computing in real-world applications.
    </p>
  </div>
</div>

---

### Featured Publications

<!-- > Featured papers are marked in your BibTeX/metadata (e.g., `featured = {true}`) and rendered automatically here. -->

<div class="publications">
<!-- {% for item in site.data.bib_publications | where: "featured", true %}
  {{ item | publication }}
{% endfor %} -->
{% bibliography %}
</div>

---

### Research Directions

<div style="height: 1rem;"></div>
<div class="row">
  <div class="col-md-4 mb-4">
    <div class="card h-100">
      <img class="card-img-top" src="{{ '/assets/img/qml.png' | relative_url }}" alt="Quantum Machine Learning">
      <div class="card-body">
        <h5 class="card-title">Quantum Machine Learning</h5>
        <p class="card-text">
          I develop quantum-assisted learning methods that leverage quantum sampling for training.
          Representative projects include training multilayer perceptrons via quantum annealing-based sampling, and
          optimization with binary gradients on quantum annealers.
        </p>
      </div>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card h-100">
      <img class="card-img-top" src="{{ '/assets/img/qcv.jpg' | relative_url }}" alt="Quantum Computer Vision">
      <div class="card-body">
        <h5 class="card-title">Quantum Computer Vision</h5>
        <p class="card-text">
          I study how quantum computation can enhance core vision primitives, especially geometric estimation.
          A key project is demonstrating robust fitting on a real gate-model quantum computer, targeting practical quantum advantage
          for geometric reasoning pipelines.
        </p>
      </div>
    </div>
  </div>

  <div class="col-md-4 mb-4">
    <div class="card h-100">
      <img class="card-img-top" src="{{ '/assets/img/benchmark1.jpg' | relative_url }}" alt="Quantum Hardware Benchmarking">
      <div class="card-body">
        <h5 class="card-title">Quantum Hardware Benchmarking</h5>
        <p class="card-text">
          I benchmark quantum hardware and quantum-classical workflows with an algorithmic lens: scalability, robustness,
          and end-to-end performance. This includes systematic solver comparisons and device-aware evaluation across
          annealing and gate-based platforms.
        </p>
      </div>
    </div>
  </div>
</div>



