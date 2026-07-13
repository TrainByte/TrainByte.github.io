---
layout: page
permalink: /publications/
title: publications
description: Published and accepted research in wireless networking, edge intelligence, AI-service orchestration, and space computing networks.
nav: true
nav_order: 2
---

<style>
  .publications-note {
    color: var(--global-text-color-light);
    margin: 0.25rem 0 1.2rem;
  }

  .publications-note strong {
    color: var(--global-text-color);
  }

  ol.bibliography {
    display: grid;
    gap: 0.85rem;
    padding-left: 1.35rem;
  }

  ol.bibliography li {
    border-left: 3px solid var(--global-theme-color);
    padding: 0.15rem 0 0.35rem 0.85rem;
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
</style>

<p class="publications-note">
  A concise list of published and accepted work. Selected highlights with visual summaries and ranking badges are shown on the homepage.
</p>

{% include bib_search.liquid %}

{% bibliography %}
