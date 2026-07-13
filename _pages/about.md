---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate in Computer Science | Institute of Computing Technology, Chinese Academy of Sciences
profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Beijing, China</p>
    <p><a href="mailto:shiningzhe21b@ict.ac.cn">shiningzhe21b@ict.ac.cn</a></p>
selected_papers: false
social: true
announcements:
  enabled: true
  scrollable: true
  limit: 6
latest_posts:
  enabled: false
  scrollable: false
  limit: 3
---

<style>
  ol.bibliography .author em {
    font-style: normal;
    font-weight: 600;
    text-decoration: underline;
    text-decoration-thickness: 0.08em;
    text-underline-offset: 0.16em;
  }

  .profile {
    max-width: 210px;
  }

  .profile img {
    width: 100%;
    max-width: 180px;
    height: auto;
  }

  .profile .more-info {
    font-size: 0.9rem;
    line-height: 1.45;
  }

  .selected-publication-list {
    display: grid;
    gap: 1rem;
    margin-top: 1rem;
  }

  .selected-publication {
    display: grid;
    grid-template-columns: 136px minmax(0, 1fr);
    gap: 1rem;
    align-items: start;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 0.9rem;
    background: var(--global-bg-color);
  }

  .selected-publication img {
    width: 136px;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    background: #fff;
  }

  .selected-publication h3 {
    font-size: 1rem;
    line-height: 1.35;
    margin: 0 0 0.35rem;
    overflow-wrap: anywhere;
  }

  .selected-publication p {
    margin: 0.25rem 0;
    overflow-wrap: anywhere;
  }

  .selected-publication-authors em {
    font-style: normal;
    font-weight: 600;
    text-decoration: underline;
    text-decoration-thickness: 0.08em;
    text-underline-offset: 0.16em;
  }

  .publication-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-top: 0.55rem;
  }

  .publication-badge {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    display: inline-flex;
    align-items: center;
    line-height: 1.2;
    padding: 0.25rem 0.42rem;
    font-size: 0.76rem;
    font-weight: 600;
  }

  .publication-badge.venue {
    color: var(--global-theme-color);
  }

  .featured-projects {
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
    background: var(--global-bg-color);
    min-width: 0;
  }

  .project-card h3 {
    font-size: 1rem;
    line-height: 1.35;
    margin: 0 0 0.5rem;
  }

  .project-card h3,
  .project-card p {
    overflow-wrap: anywhere;
  }

  .project-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin: 0.55rem 0;
  }

  .project-role,
  .project-tag,
  .project-result {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    display: inline-flex;
    align-items: center;
    line-height: 1.2;
    padding: 0.25rem 0.42rem;
    font-size: 0.76rem;
  }

  .project-role {
    color: var(--global-theme-color);
    font-weight: 600;
  }

  .project-link {
    display: inline-block;
    margin-top: auto;
    font-weight: 600;
  }

  @media (max-width: 767px) {
    .selected-publication {
      grid-template-columns: 1fr;
    }

    .selected-publication img {
      width: 100%;
      max-width: 220px;
    }

    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

I am **Ningzhe Shi (时宁哲)**, a Ph.D. candidate in Computer Science and Technology at the Institute of Computing Technology, Chinese Academy of Sciences, and the University of Chinese Academy of Sciences. My Ph.D. Advisor is <a href="https://www.ict.ac.cn/sourcedb/cn/jssrck/200909/t20090917_2496807.html" target="_blank" rel="noopener noreferrer">Prof. Yiqing Zhou</a>. I received my B.Eng. in Communication Engineering from Xidian University, where my Undergraduate Research Advisor was <a href="https://web.xidian.edu.cn/junyuliu/" target="_blank" rel="noopener noreferrer">Prof. Junyu Liu</a>. During my undergraduate study, I received the National Scholarship and ranked 1st in class for comprehensive recommendation.

My research focuses on 6G intelligent networks and AI service orchestration. I study communication, sensing, computing, and knowledge resource optimization for networked AI systems, using reinforcement learning and optimization methods.

## Research interests

- AI-Native 6G Networks
- Edge Intelligence and Cloud-Edge Collaborative AI Services
- Integrated Sensing, Communication, Computing, and Intelligence
- Space AI Computing Networks

## Selected publications

<div class="selected-publication-list">
  <article class="selected-publication">
    <img src="{{ '/assets/img/publication_preview/tmc-noma.png' | relative_url }}" alt="NOMA-based multi-cell MEC resource allocation preview">
    <div>
      <h3>Service Satisfaction Based User Selection and Resource Allocation for NOMA-Based Multi-Cell MEC Networks</h3>
      <p class="selected-publication-authors"><em>Ningzhe Shi</em>, Yiqing Zhou, Ling Liu, Yihao Wu, Hanxiao Yu, and Jinglin Shi</p>
      <p>IEEE Transactions on Mobile Computing, 2026</p>
      <div class="publication-badges" aria-label="Publication venue and ranking">
        <span class="publication-badge venue">TMC</span>
        <span class="publication-badge">CCF-A</span>
        <span class="publication-badge">Q1 CAS</span>
        <span class="publication-badge">Accepted/Published</span>
      </div>
    </div>
  </article>

  <article class="selected-publication">
    <img src="{{ '/assets/img/publication_preview/tmc-isac.png' | relative_url }}" alt="ISAC-driven AIGC resource allocation preview">
    <div>
      <h3>Content Accuracy and Quality Aware Resource Allocation Based on LP-Guided DRL for ISAC-Driven AIGC Networks</h3>
      <p class="selected-publication-authors"><em>Ningzhe Shi</em>, Yiqing Zhou, Ling Liu, Jinglin Shi, Yihao Wu, Haiwei Shi, and Hanxiao Yu</p>
      <p>IEEE Transactions on Mobile Computing, 2026</p>
      <div class="publication-badges" aria-label="Publication venue and ranking">
        <span class="publication-badge venue">TMC</span>
        <span class="publication-badge">CCF-A</span>
        <span class="publication-badge">Q1 CAS</span>
        <span class="publication-badge">Published</span>
      </div>
    </div>
  </article>

  <article class="selected-publication">
    <img src="{{ '/assets/img/publication_preview/tccn-fairness.png' | relative_url }}" alt="Wireless fairness and multi-agent DRL preview">
    <div>
      <h3>Long-Term Fairness From Real-Time Decisions: Reward Adaptive Multi-Agent DRL for Wireless Communication With Imperfect CSI</h3>
      <p class="selected-publication-authors"><em>Ningzhe Shi</em>, Ling Liu, Yiqing Zhou, Hanxiao Yu, Yihao Wu, Jingya Yang, and Jinglin Shi</p>
      <p>IEEE Transactions on Cognitive Communications and Networking, 2026</p>
      <div class="publication-badges" aria-label="Publication venue and ranking">
        <span class="publication-badge venue">TCCN</span>
        <span class="publication-badge">Q1 CAS</span>
        <span class="publication-badge">Published</span>
      </div>
    </div>
  </article>

  <article class="selected-publication">
    <img src="{{ '/assets/img/publication_preview/china-communications-uav.png' | relative_url }}" alt="UAV-assisted mmWave MIMO secure communication preview">
    <div>
      <h3>Deception-Based Secure Communication for UAV-Assisted mmWave MIMO Systems</h3>
      <p class="selected-publication-authors"><em>Ningzhe Shi</em>, Yiqing Zhou, Yu Zhang, Zhijun Han, Ling Liu, and Jinglin Shi</p>
      <p>China Communications, 2026</p>
      <div class="publication-badges" aria-label="Publication venue and ranking">
        <span class="publication-badge venue">China Commun.</span>
        <span class="publication-badge">T1 CIC</span>
        <span class="publication-badge">Published</span>
      </div>
    </div>
  </article>
</div>

## Featured projects

<section class="featured-projects" aria-label="Featured projects">
  <div class="project-grid">
    {% assign featured_projects = site.projects | where: "featured", true | sort: "importance" %}
    {% for project in featured_projects limit: 4 %}
      {% include project-card.html project=project %}
    {% endfor %}
  </div>
</section>

{% include visitor_counter.liquid %}
