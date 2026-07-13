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
  enabled: false
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

  .social a[href*="feed"],
  .social a[href*="rss"],
  .social a[aria-label*="RSS"],
  .social a[title*="RSS"],
  footer a[href*="feed"],
  footer a[href*="rss"],
  footer a[aria-label*="RSS"],
  footer a[title*="RSS"],
  .social .fa-rss,
  .social .fa-square-rss,
  footer .fa-rss,
  footer .fa-square-rss {
    display: none !important;
  }

  .section-note {
    color: var(--global-text-color-light);
    margin: 0.25rem 0 1rem;
  }

  .interest-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.8rem;
    margin-top: 1rem;
  }

  .interest-card {
    border: 1px solid var(--global-divider-color);
    border-left: 4px solid var(--global-theme-color);
    border-radius: 8px;
    padding: 0.85rem 0.95rem;
    background: var(--global-bg-color);
  }

  .interest-card h3 {
    font-size: 0.98rem;
    line-height: 1.35;
    margin: 0 0 0.35rem;
  }

  .interest-card p {
    color: var(--global-text-color-light);
    margin: 0;
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

  .publication-badge.ccf {
    background: #fff1f2;
    border-color: #f3a6b2;
    color: #ad1742;
  }

  .publication-badge.cas {
    background: #ecfdf3;
    border-color: #8fd7ad;
    color: #176b3a;
  }

  .publication-badge.cic {
    background: #fff7ed;
    border-color: #f0bc79;
    color: #9a4b07;
  }

  .publication-badge.status {
    background: #eef6ff;
    border-color: #9fc6ef;
    color: #245f9f;
  }

  .home-news {
    display: grid;
    gap: 0.55rem;
    margin: 1rem 0 0;
    padding: 0;
    list-style: none;
  }

  .home-news li {
    display: grid;
    grid-template-columns: 8.5rem minmax(0, 1fr);
    gap: 0.75rem;
    align-items: start;
    border-bottom: 1px solid var(--global-divider-color);
    padding-bottom: 0.55rem;
  }

  .home-news-date {
    color: var(--global-text-color-light);
    font-size: 0.9rem;
    white-space: nowrap;
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
    position: relative;
    overflow: hidden;
  }

  .project-card::before {
    content: "";
    display: block;
    height: 4px;
    background: var(--global-theme-color);
    margin: -1rem -1rem 0.85rem;
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

  .project-category {
    color: var(--global-text-color-light);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    margin-bottom: 0.35rem;
    text-transform: uppercase;
  }

  .project-role,
  .project-output,
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

  .project-contribution {
    border-left: 3px solid var(--global-theme-color);
    padding-left: 0.65rem;
  }

  .project-result {
    background: #eef6ff;
    border-color: #9fc6ef;
    color: #245f9f;
  }

  .project-output {
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
    .interest-grid {
      grid-template-columns: 1fr;
    }

    .home-news li {
      grid-template-columns: 1fr;
      gap: 0.15rem;
    }

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

<div class="interest-grid">
  <section class="interest-card">
    <h3>AI-Native 6G Networks</h3>
    <p>Resource orchestration and learning-driven network intelligence for next-generation wireless systems.</p>
  </section>
  <section class="interest-card">
    <h3>Cloud-Edge Collaborative AI Services</h3>
    <p>Task scheduling, RAG service placement, and AI Agent memory management across heterogeneous nodes.</p>
  </section>
  <section class="interest-card">
    <h3>Integrated Sensing, Communication, Computing, and Intelligence</h3>
    <p>Joint modeling of sensing accuracy, communication quality, computing resources, and AI service outcomes.</p>
  </section>
  <section class="interest-card">
    <h3>Space AI Computing Networks</h3>
    <p>Distributed routing and computing-resource scheduling for dynamic space-ground intelligent networks.</p>
  </section>
</div>

## News

<ul class="home-news">
  {% assign news_items = site.news | sort: "date" | reverse %}
  {% for item in news_items limit: 6 %}
    <li>
      <span class="home-news-date">{{ item.date | date: "%b %-d, %Y" }}</span>
      <span>{{ item.content | strip_html | strip_newlines }}</span>
    </li>
  {% endfor %}
</ul>

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
        <span class="publication-badge ccf">CCF-A</span>
        <span class="publication-badge cas">Q1 CAS</span>
        <span class="publication-badge status">Accepted/Published</span>
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
        <span class="publication-badge ccf">CCF-A</span>
        <span class="publication-badge cas">Q1 CAS</span>
        <span class="publication-badge status">Published</span>
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
        <span class="publication-badge cas">Q1 CAS</span>
        <span class="publication-badge status">Published</span>
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
        <span class="publication-badge cic">T1 CIC</span>
        <span class="publication-badge status">Published</span>
      </div>
    </div>
  </article>
</div>

## Selected research & engineering projects

<p class="section-note">A compact view of research systems, algorithm prototypes, and engineering platforms that connect wireless networks, AI services, and distributed simulation.</p>

<section class="featured-projects" aria-label="Featured projects">
  <div class="project-grid">
    {% assign featured_projects = site.projects | sort: "importance" %}
    {% for project in featured_projects limit: 6 %}
      {% include project-card.html project=project %}
    {% endfor %}
  </div>
</section>

{% include visitor_counter.liquid %}
