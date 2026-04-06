---
layout: page
permalink: /publications/
title: publications
importance: 2
description:
nav: true
---

<div class="publications-page">
  <section class="pub-hero">
    <p>
      My research focuses on learned image compression, 3D Gaussian Splatting compression, and enhancing the efficiency of vision systems.
      I am interested in bridging the advances of computer vision with practical, scalable pipelines that enable high-quality and efficient immersive AI applications.
    </p>
    <ul class="pub-focus-list">
      <li>Efficient 3D scene representations & compression</li>
      <li>Learned image & video compression</li>
      <li>Real-time & resource-efficient vision systems</li>
      <li>Scalable & deployable AI for immersive applications</li>
    </ul>
    <div class="pub-hero__actions">
      <a class="pub-action primary" href="https://scholar.google.com/citations?user=qbreZUIAAAAJ&amp;hl=en" target="_blank" rel="noopener">Google Scholar</a>
      <a class="pub-action" href="#all">Jump to publications</a>
    </div>
  </section>

  <nav class="pub-section-nav" aria-label="Publications navigation">
    <a href="#all">All publications</a>
  </nav>

  <div class="pub-highlight-grid">
    <article class="pub-highlight">
      <p class="pub-highlight__eyebrow">Track record</p>
      <h3>20+ peer-reviewed papers</h3>
      <p>Published across NeurIPS, ICCV, AAAI, CVPR, BMVC, WACV, IEEE Transactions, and SCIE-indexed journals.</p>
    </article>
    <article class="pub-highlight">
      <p class="pub-highlight__eyebrow">Core themes</p>
      <h3>Compression-centric AI</h3>
      <p>Neural codecs and splatting techniques that reduce memory/compute while preserving fidelity.</p>
    </article>
    <article class="pub-highlight">
      <p class="pub-highlight__eyebrow">Service</p>
      <h3>Active reviewer</h3>
      <p>Served for NeurIPS, CVPR, ICCV, ECCV, ICLR, BMVC, WACV, and IEEE Transactions.</p>
    </article>
  </div>

  <section class="pub-section" id="all">
    <div class="pub-section__header">
      <h2>All publications</h2>
    </div>
    <div class="publications publications--archive">
      {% bibliography -f papers --group_by year --group_order descending %}
    </div>
  </section>
</div>
