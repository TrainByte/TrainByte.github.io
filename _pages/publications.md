---
layout: page
permalink: /publications/
title: Publications & Patents
description: Published and accepted research, granted invention patents, invention patent applications, and registered software copyrights.
nav: true
nav_order: 2
---

<style>
  body {
    background-image: url("{{ '/assets/img/logos/xidian-watermark.png' | relative_url }}");
    background-attachment: fixed;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: min(58vw, 640px);
  }

  .publications-note {
    color: var(--global-text-color-light);
    margin: 0.25rem 0 1.6rem;
    max-width: 56rem;
  }

  .publications-note strong {
    color: var(--global-text-color);
  }

  .publication-section {
    margin-top: 2rem;
  }

  .publication-section h2 {
    margin-bottom: 1rem;
  }

  h2.bibliography {
    color: var(--global-theme-color);
    font-size: 1.05rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    margin: 1.45rem 0 0.65rem;
  }

  ol.bibliography {
    counter-reset: publication;
    display: grid;
    gap: 0.75rem;
    list-style: none;
    margin: 0;
    padding: 0;
  }

  ol.bibliography li {
    background:
      linear-gradient(180deg, rgba(46, 127, 255, 0.035), rgba(255, 255, 255, 0)),
      var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    box-shadow: 0 8px 26px rgba(15, 23, 42, 0.035);
    padding: 0.85rem 0.95rem;
  }

  ol.bibliography li .row {
    align-items: flex-start;
    display: grid;
    gap: 0.75rem;
    grid-template-columns: minmax(78px, auto) minmax(0, 1fr);
    margin: 0;
  }

  ol.bibliography .abbr,
  ol.bibliography [class*="col-sm"] {
    flex: none;
    max-width: none;
    padding: 0;
    width: auto;
  }

  ol.bibliography .abbr abbr {
    background: #eef6ff;
    border: 1px solid #9fc6ef;
    border-radius: 6px;
    color: #245f9f;
    display: inline-flex;
    font-size: 0.72rem;
    font-weight: 700;
    line-height: 1.2;
    padding: 0.27rem 0.42rem;
    white-space: normal;
    width: auto !important;
  }

  ol.bibliography .title {
    font-size: 0.98rem;
    font-weight: 650;
    line-height: 1.38;
    margin-bottom: 0.24rem;
  }

  ol.bibliography .author,
  ol.bibliography .periodical {
    font-size: 0.9rem;
    line-height: 1.42;
  }

  ol.bibliography .periodical {
    color: var(--global-text-color-light);
  }

  ol.bibliography .author em {
    font-style: normal;
    font-weight: 600;
    text-decoration: underline;
    text-decoration-thickness: 0.08em;
    text-underline-offset: 0.16em;
  }

  ol.bibliography img,
  ol.bibliography .preview {
    display: none !important;
  }

  ol.bibliography .links a[href*="doi.org"],
  ol.bibliography .bibtex,
  ol.bibliography pre {
    display: none !important;
  }

  .ip-section {
    margin-top: 2.8rem;
  }

  .ip-group {
    margin-top: 1.4rem;
  }

  .ip-group h3 {
    font-size: 1.05rem;
    margin-bottom: 0.75rem;
  }

  .ip-list {
    display: grid;
    gap: 0.75rem;
    margin: 0;
    padding: 0;
  }

  .ip-item {
    background:
      linear-gradient(180deg, rgba(176, 62, 98, 0.035), rgba(255, 255, 255, 0)),
      var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    box-shadow: 0 8px 26px rgba(15, 23, 42, 0.035);
    display: grid;
    gap: 0.45rem;
    padding: 0.85rem 0.95rem;
  }

  .ip-title {
    font-weight: 600;
    line-height: 1.35;
  }

  .ip-meta {
    color: var(--global-text-color-light);
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    font-size: 0.86rem;
  }

  .ip-meta span {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    line-height: 1.2;
    padding: 0.24rem 0.42rem;
  }

  .ip-meta .ip-type {
    color: var(--global-theme-color);
    font-weight: 600;
  }

  @media (max-width: 767px) {
    body {
      background-position: center 6rem;
      background-size: 430px;
    }

    ol.bibliography li .row {
      grid-template-columns: 1fr;
      gap: 0.48rem;
    }
  }
</style>

<p class="publications-note">
  A concise record of peer-reviewed publications, granted invention patents, invention patent applications, and registered software copyrights.
</p>

<section class="publication-section" aria-label="Research publications">
  <h2>Publications</h2>

{% bibliography %}

</section>

<section id="patents" class="ip-section" aria-label="Invention patents and software copyright">
  <h2>Invention Patents</h2>

  <div class="ip-group">
    <h3>Granted invention patents</h3>
    <div class="ip-list">
      <article class="ip-item">
        <div class="ip-title">Anti-Tracking Jamming-Resistant Signal Transmission Method, Signal Reception Method, and System</div>
        <div class="ip-meta">
          <span class="ip-type">Granted invention patent</span>
          <span>CN202211134854.X</span>
          <span>2024-09-24</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Anti-Jamming Method and System Based on Relay Position Selection and Power Allocation</div>
        <div class="ip-meta">
          <span class="ip-type">Granted invention patent</span>
          <span>CN202310078808.0</span>
          <span>2025-05-27</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Construction Method and Resource Management Method for a Wireless Network Resource Allocation System</div>
        <div class="ip-meta">
          <span class="ip-type">Granted invention patent</span>
          <span>CN202310354794.0</span>
          <span>2026-04-07</span>
        </div>
      </article>
    </div>
  </div>

  <div class="ip-group">
    <h3>Invention patent applications</h3>
    <div class="ip-list">
      <article class="ip-item">
        <div class="ip-title">Construction Method and Resource Management Method for a Wireless Network Resource Allocation System</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application (PCT)</span>
          <span>PCT/CN2023/090283</span>
          <span>2023-04-24</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Real-Time Simulation System and Method for Full-Duplex Ad Hoc Networks</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202311719290.0</span>
          <span>2023-12-14</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Multi-User MIMO Signal Detection Model</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202410018551.4</span>
          <span>2024-01-05</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Channel Access Method and Communication System for Ad Hoc Networks</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202410348337.5</span>
          <span>2024-03-26</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Mobile Ad Hoc Network Data Routing Method and Industrial Ad Hoc Network System</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202510873622.3</span>
          <span>2025-06-27</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Environment- and Resource-State-Aware Resource Allocation Method and System</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202510955830.8</span>
          <span>2025-07-11</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Resource Allocation Method for AI-Generated Content Services Based on Integrated Sensing and Communication</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202511053332.0</span>
          <span>2025-07-30</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Joint Channel Estimation and Signal Detection Method, Signal Receiver, and Storage Medium</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202511536493.5</span>
          <span>2025-10-27</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Transmission Device and Semantic Transmission Method for High-Mobility Communications</div>
        <div class="ip-meta">
          <span class="ip-type">Invention patent application</span>
          <span>CN202610406457.5</span>
          <span>2026-03-31</span>
        </div>
      </article>
    </div>
  </div>

  <div class="ip-group">
    <h3>Software copyright</h3>
    <div class="ip-list">
      <article class="ip-item">
        <div class="ip-title">Large-Scale Full-Duplex Network Simulation System</div>
        <div class="ip-meta">
          <span class="ip-type">Registered software copyright</span>
          <span>2024SR0082117</span>
          <span>2024-01-11</span>
        </div>
      </article>
    </div>
  </div>
</section>
