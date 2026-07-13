---
layout: page
title: Selected Projects
permalink: /projects/
description: Selected systems, algorithms, and research prototypes spanning AI-native networks, distributed simulation, cloud-edge intelligence, and wireless resource optimization.
nav: true
nav_order: 3
---

<style>
  .project-toolbar {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin: 1.25rem 0 1rem;
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

  .project-intro {
    color: var(--global-text-color-light);
    max-width: 56rem;
  }

  .project-section {
    margin-top: 2rem;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }

  .project-card {
    display: flex;
    flex-direction: column;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 1rem;
    min-height: 100%;
    min-width: 0;
    background: var(--global-bg-color);
    overflow: hidden;
    position: relative;
  }

  .project-card::before {
    content: "";
    display: block;
    height: 4px;
    background: var(--global-theme-color);
    margin: -1rem -1rem 0.85rem;
  }

  .project-category {
    color: var(--global-text-color-light);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    margin-bottom: 0.35rem;
    text-transform: uppercase;
  }

  .project-card h3 {
    font-size: 1.05rem;
    line-height: 1.35;
    margin: 0 0 0.5rem;
  }

  .project-card p {
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
    gap: 0.4rem;
    margin: 0.65rem 0;
  }

  .project-role {
    padding: 0.25rem 0.45rem;
    font-size: 0.78rem;
    font-weight: 600;
    color: var(--global-theme-color);
  }

  .project-result {
    padding: 0.25rem 0.45rem;
    font-size: 0.78rem;
    background: #eef6ff;
    border-color: #9fc6ef;
    color: #245f9f;
  }

  .project-tag {
    padding: 0.25rem 0.42rem;
    font-size: 0.76rem;
    color: var(--global-text-color-light);
  }

  .project-output {
    padding: 0.25rem 0.42rem;
    font-size: 0.76rem;
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
    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

{% assign sorted_projects = site.projects | sort: "importance" %}
{% assign categories = "Engineering Systems|AI Systems|Wireless Intelligence" | split: "|" %}

<p class="project-intro">
  Selected projects across distributed network simulation, AI Agent memory, cloud-edge RAG orchestration, space AI routing, ISAC-driven AIGC services, and secure UAV communications.
</p>

<div class="project-toolbar" aria-label="Project categories">
  <a href="#all-projects">All</a>
  {% for category in categories %}
    <a href="#{{ category | slugify }}">{{ category }}</a>
  {% endfor %}
</div>

<section id="all-projects" class="project-section">
  <h2>All</h2>
  <div class="project-grid">
    {% for project in sorted_projects %}
      {% include project-card.html project=project %}
    {% endfor %}
  </div>
</section>

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
