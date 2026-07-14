---
layout: page
title: Selected Projects
permalink: /projects/
description: Selected research and engineering projects spanning AI-native networks, cloud-edge intelligence, space computing, secure wireless systems, and distributed simulation.
nav: true
nav_order: 3
---

<style>
  body {
    background-image: url("{{ '/assets/img/logos/ucas-watermark.png' | relative_url }}");
    background-attachment: fixed;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: min(58vw, 640px);
  }

  .project-toolbar {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 1.25rem 0 1.4rem;
  }

  .project-toolbar a,
  .project-output,
  .project-role,
  .project-result {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    display: inline-flex;
    align-items: center;
    line-height: 1.2;
  }

  .project-toolbar a {
    padding: 0.45rem 0.7rem;
    color: var(--global-text-color);
    text-decoration: none;
  }

  .project-toolbar a:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
  }

  .project-intro {
    color: var(--global-text-color-light);
    max-width: 60rem;
  }

  .project-section {
    margin-top: 2.35rem;
  }

  .project-section h2 {
    border-bottom: 1px solid var(--global-divider-color);
    font-size: 1.28rem;
    margin-bottom: 0.9rem;
    padding-bottom: 0.4rem;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.9rem;
  }

  .project-card {
    background:
      linear-gradient(180deg, rgba(46, 127, 255, 0.035), rgba(255, 255, 255, 0)),
      var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    box-shadow: 0 8px 26px rgba(15, 23, 42, 0.035);
    display: flex;
    flex-direction: column;
    min-height: 100%;
    min-width: 0;
    overflow: hidden;
    padding: 1rem;
    position: relative;
    transition:
      border-color 160ms ease,
      box-shadow 160ms ease,
      transform 160ms ease;
  }

  .project-card:hover {
    border-color: rgba(46, 127, 255, 0.42);
    box-shadow: 0 14px 34px rgba(15, 23, 42, 0.08);
    transform: translateY(-2px);
  }

  .project-card::before {
    content: "";
    display: block;
    height: 4px;
    background: linear-gradient(90deg, var(--global-theme-color), #b03e62);
    margin: -0.95rem -0.95rem 0.8rem;
  }

  .project-category {
    color: var(--global-text-color-light);
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    margin-bottom: 0.35rem;
    text-transform: uppercase;
  }

  .project-card h3 {
    font-size: 1rem;
    line-height: 1.35;
    margin: 0 0 0.58rem;
  }

  .project-card h3 a {
    color: var(--global-text-color);
    text-decoration: none;
  }

  .project-card h3 a:hover {
    color: var(--global-theme-color);
  }

  .project-card p {
    font-size: 0.9rem;
    line-height: 1.45;
    margin-bottom: 0.55rem;
  }

  .project-contribution {
    background: rgba(46, 127, 255, 0.045);
    border-left: 3px solid var(--global-theme-color);
    border-radius: 6px;
    padding: 0.55rem 0.65rem;
  }

  .project-contribution strong {
    color: var(--global-theme-color);
  }

  .project-card h3,
  .project-card p {
    overflow-wrap: anywhere;
  }

  .project-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.35rem;
    margin: 0.55rem 0 0.25rem;
  }

  .project-role {
    padding: 0.25rem 0.45rem;
    font-size: 0.72rem;
    font-weight: 600;
    color: var(--global-theme-color);
  }

  .project-result {
    padding: 0.25rem 0.45rem;
    font-size: 0.72rem;
    background: #eef6ff;
    border-color: #9fc6ef;
    color: #245f9f;
  }

  .project-output {
    padding: 0.25rem 0.42rem;
    font-size: 0.71rem;
    background: #f3fbf6;
    border-color: #9bd9b1;
    color: #176b3a;
  }

  .project-link {
    align-self: flex-start;
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    display: inline-flex;
    margin-top: auto;
    padding: 0.36rem 0.58rem;
    font-weight: 600;
    text-decoration: none;
  }

  .project-link:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
  }

  @media (max-width: 767px) {
    body {
      background-position: center 5.8rem;
      background-size: 430px;
    }

    .project-grid {
      grid-template-columns: 1fr;
    }
  }

  @media (min-width: 768px) and (max-width: 1100px) {
    .project-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }
</style>

{% assign sorted_projects = site.projects | sort: "importance" %}
{% assign categories = "AI Systems|Wireless Intelligence|Engineering Systems" | split: "|" %}

<p class="project-intro">
  Selected projects that connect algorithm design with deployable networked systems, spanning AI service orchestration, learning-driven wireless intelligence, space computing, secure communications, and distributed simulation.
</p>

<div class="project-toolbar" aria-label="Project categories">
  {% for category in categories %}
    <a href="#{{ category | slugify }}">{{ category }}</a>
  {% endfor %}
</div>

{% for category in categories %}

  <section id="{{ category | slugify }}" class="project-section">
    <h2>{{ category }}</h2>
    <div class="project-grid">
      {% assign category_projects = sorted_projects | where: "category", category %}
      {% for project in category_projects %}
        {% include project-card.html project=project %}
      {% endfor %}
    </div>
  </section>
{% endfor %}
