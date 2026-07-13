---
layout: page
permalink: /publications/
title: Publications & Intellectual Property
description: Published and accepted research, invention patents, and registered software copyrights.
nav: true
nav_order: 2
---

<style>
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

  ol.bibliography {
    display: grid;
    gap: 0.9rem;
    padding-left: 1.35rem;
  }

  ol.bibliography li {
    border-left: 3px solid var(--global-theme-color);
    padding: 0.25rem 0 0.45rem 0.9rem;
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
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    display: grid;
    gap: 0.45rem;
    padding: 0.85rem 0.95rem;
    background: var(--global-bg-color);
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
</style>

<p class="publications-note">
  A concise record of peer-reviewed publications, granted invention patents, patent applications, and registered software copyrights.
</p>

<section class="publication-section" aria-label="Research publications">
  <h2>Research publications</h2>

{% bibliography %}

</section>

<section id="intellectual-property" class="ip-section" aria-label="Intellectual property">
  <h2>Intellectual property</h2>

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
    <h3>Patent applications</h3>
    <div class="ip-list">
      <article class="ip-item">
        <div class="ip-title">Construction Method and Resource Management Method for a Wireless Network Resource Allocation System</div>
        <div class="ip-meta">
          <span class="ip-type">PCT application</span>
          <span>PCT/CN2023/090283</span>
          <span>2023-04-24</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Real-Time Simulation System and Method for Full-Duplex Ad Hoc Networks</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202311719290.0</span>
          <span>2023-12-14</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Multi-User MIMO Signal Detection Model</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202410018551.4</span>
          <span>2024-01-05</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Channel Access Method and Communication System for Ad Hoc Networks</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202410348337.5</span>
          <span>2024-03-26</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Mobile Ad Hoc Network Data Routing Method and Industrial Ad Hoc Network System</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202510873622.3</span>
          <span>2025-06-27</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Environment- and Resource-State-Aware Resource Allocation Method and System</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202510955830.8</span>
          <span>2025-07-11</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Resource Allocation Method for AI-Generated Content Services Based on Integrated Sensing and Communication</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202511053332.0</span>
          <span>2025-07-30</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Joint Channel Estimation and Signal Detection Method, Signal Receiver, and Storage Medium</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
          <span>CN202511536493.5</span>
          <span>2025-10-27</span>
        </div>
      </article>
      <article class="ip-item">
        <div class="ip-title">Transmission Device and Semantic Transmission Method for High-Mobility Communications</div>
        <div class="ip-meta">
          <span class="ip-type">Patent application</span>
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
