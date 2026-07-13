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
    background-position: left clamp(-260px, -14vw, -120px) top 7rem;
    background-repeat: no-repeat;
    background-size: min(46vw, 560px);
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
  .project-tag,
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
    display: flex;
    flex-direction: column;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 0.9rem;
    min-height: 100%;
    min-width: 0;
    background:
      linear-gradient(180deg, rgba(46, 127, 255, 0.035), rgba(255, 255, 255, 0)),
      var(--global-bg-color);
    overflow: hidden;
    position: relative;
    box-shadow: 0 8px 26px rgba(15, 23, 42, 0.035);
  }

  .project-card::before {
    content: "";
    display: block;
    height: 4px;
    background: linear-gradient(90deg, var(--global-theme-color), #b03e62);
    margin: -0.9rem -0.9rem 0.8rem;
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
    font-size: 0.98rem;
    line-height: 1.35;
    margin: 0 0 0.5rem;
  }

  .project-card p {
    font-size: 0.9rem;
    line-height: 1.45;
    margin-bottom: 0.55rem;
  }

  .project-contribution {
    border-left: 3px solid var(--global-theme-color);
    padding-left: 0.65rem;
  }

  .project-card h3,
  .project-card p {
    overflow-wrap: anywhere;
  }

  .project-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.35rem;
    margin: 0.55rem 0;
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

  .project-tag {
    padding: 0.25rem 0.42rem;
    font-size: 0.71rem;
    color: var(--global-text-color-light);
  }

  .project-output {
    padding: 0.25rem 0.42rem;
    font-size: 0.71rem;
    background: #f3fbf6;
    border-color: #9bd9b1;
    color: #176b3a;
  }

  .project-link {
    display: inline-block;
    margin-top: auto;
    font-weight: 600;
  }

  @media (max-width: 767px) {
    body {
      background-position: left -210px top 5.5rem;
      background-size: 390px;
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
  Selected projects from AI Agent memory and cloud-edge RAG orchestration to space AI routing, AIGC service scheduling, ISAC resource allocation, secure UAV communications, full-duplex ad hoc networking, and large-scale wireless simulation.
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
