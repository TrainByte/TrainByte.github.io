---
layout: page
title: Selected Research & Engineering Projects
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
    margin: 1.5rem 0 1rem;
  }

  .project-toolbar a,
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

  .project-section {
    margin-top: 2rem;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1rem;
  }

  .project-card {
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 1rem;
    min-height: 100%;
    background: var(--global-bg-color);
  }

  .project-card h3 {
    font-size: 1.05rem;
    line-height: 1.35;
    margin: 0 0 0.5rem;
  }

  .project-card p {
    margin-bottom: 0.55rem;
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
  }

  .project-tag {
    padding: 0.25rem 0.42rem;
    font-size: 0.76rem;
    color: var(--global-text-color-light);
  }

  .project-link {
    display: inline-block;
    margin-top: 0.35rem;
    font-weight: 600;
  }
</style>

{% assign sorted_projects = site.projects | sort: "importance" %}
{% assign categories = "Engineering Systems|AI Systems|Wireless Intelligence" | split: "|" %}

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
