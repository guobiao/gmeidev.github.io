---
layout: default
title: "Visualization of Collaborative Data (2006)"
structured: true
---

<section class="hero-card hero-card-padded" aria-label="Paper overview">
  <span class="hero-eyebrow">UAI · 2006</span>
  <h1 class="hero-title-paper">Visualization of Collaborative Data</h1>
  <p class="hero-authors">by <a href="/">Guobiao Mei</a> and <a href="https://www.cs.ucr.edu/~cshelton/">Christian R. Shelton</a></p>
  <div class="contact-actions">
    <a class="action-pill action-pill-primary" href="/assets/papers/covis.pdf">
      <svg viewBox="0 0 24 24" width="16" height="16" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
        <polyline points="7 10 12 15 17 10"/>
        <line x1="12" x2="12" y1="15" y2="3"/>
      </svg>
      Download PDF
    </a>
    <a class="action-pill" href="#bibtex">
      <svg viewBox="0 0 24 24" width="16" height="16" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <path d="M16 3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V8Z"/>
        <path d="M15 3v4a2 2 0 0 0 2 2h4"/>
        <path d="M10 13H8"/>
        <path d="M16 17H8"/>
        <path d="M16 13h-2"/>
      </svg>
      BibTeX Citation
    </a>
  </div>
</section>

<section class="section-block" aria-labelledby="heading-abstract">
  <h2 id="heading-abstract" class="section-heading">Abstract</h2>
  <div class="surface-card paper-card">
    <p>Collaborative data consist of ratings relating two distinct sets of objects: users and items. Much of the work with such data focuses on filtering: predicting unknown ratings for pairs of users and items. In this paper we focus on the problem of visualizing the information. Given all of the ratings, our task is to embed all of the users and items as points in the same Euclidean space. We would like to place users near items that they have rated (or would rate) high, and far away from those they would give low ratings. We pose this problem as a real-valued non-linear Bayesian network and employ Markov chain Monte Carlo and expectation maximization to find an embedding. We present a metric by which to judge the quality of a visualization and compare our results to <em>Eigentaste</em>, <em>locally linear embedding</em> and <em>co-occurrence data embedding</em> on three real-world datasets.</p>
  </div>
</section>

<section id="bibtex" class="section-block" aria-labelledby="heading-citation">
  <h2 id="heading-citation" class="section-heading">Download &amp; BibTeX Citation</h2>
  <div class="surface-card paper-card">
    <p>Guobiao Mei and Christian R. Shelton (2006). "<strong>Visualization of Collaborative Data.</strong>" <em>Proceedings of the Twenty-Second International Conference on Uncertainty in Artificial Intelligence</em> (pp. 341–348). (<a href="/assets/papers/covis.pdf">PDF</a>)</p>
    <div class="bibtex-box">
      <div class="bibtex-header">
        <span>BibTeX</span>
        <button class="copy-btn" type="button" data-copy-bibtex aria-label="Copy BibTeX citation">
          <svg viewBox="0 0 24 24" width="13" height="13" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
            <rect width="14" height="14" x="8" y="8" rx="2" ry="2"/>
            <path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"/>
          </svg>
          <span>Copy</span>
        </button>
      </div>
<pre><code>@inproceedings{MeiShe06,
    author = "Guobiao Mei and Christian R. Shelton",
    title = "Visualization of Collaborative Data",
    booktitle = "Proceedings of the Twenty-Second International Conference on Uncertainty in Artificial Intelligence",
    booktitleabbr = "{UAI}-2006",
    pages = "341--348",
    year = 2006,
}</code></pre>
    </div>
  </div>
</section>

<footer class="family-banner">
  <span class="family-icon" aria-hidden="true">
    <svg viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <path d="m3 9 9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/>
      <polyline points="9 22 9 12 15 12 15 22"/>
    </svg>
  </span>
  <p>Back to <a href="/#publications">Publications</a> on the <a href="/">Homepage of Guobiao Mei</a>.</p>
</footer>
