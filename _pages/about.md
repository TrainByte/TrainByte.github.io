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
  body {
    background-image: url("{{ '/assets/img/logos/ucas-watermark.png' | relative_url }}");
    background-attachment: fixed;
    background-position: left clamp(-260px, -14vw, -120px) top 7rem;
    background-repeat: no-repeat;
    background-size: min(46vw, 560px);
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

  h2 {
    margin-top: 2.8rem;
    margin-bottom: 0.95rem;
  }

  .education-strip {
    display: grid;
    gap: 0.95rem;
    margin: 1.5rem 0 2.55rem;
  }

  .education-card {
    display: grid;
    grid-template-columns: 74px minmax(0, 1fr);
    gap: 0.42rem;
    column-gap: 1rem;
    align-items: center;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 0.95rem 1rem;
    background: var(--global-bg-color);
    box-shadow: 0 8px 26px rgba(15, 23, 42, 0.04);
  }

  .education-year {
    color: var(--global-theme-color);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    text-transform: uppercase;
  }

  .education-logo {
    align-items: center;
    background: #fff;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    display: flex;
    height: 74px;
    justify-content: center;
    padding: 0.42rem;
    width: 74px;
  }

  .education-logo img {
    display: block;
    height: 100%;
    object-fit: contain;
    width: 100%;
  }

  .education-card strong {
    display: block;
    line-height: 1.35;
  }

  .education-card span:not(.education-year) {
    color: var(--global-text-color-light);
    display: block;
    margin-top: 0.18rem;
  }

  .interest-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.9rem;
    margin: 1.05rem 0 2.35rem;
  }

  .interest-card {
    align-items: center;
    background:
      linear-gradient(135deg, rgba(46, 127, 255, 0.08), rgba(176, 62, 98, 0.05)),
      var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    display: grid;
    gap: 0.62rem;
    grid-template-columns: auto minmax(0, 1fr);
    padding: 0.95rem 1rem;
  }

  .interest-index {
    align-items: center;
    border: 1px solid rgba(46, 127, 255, 0.28);
    border-radius: 999px;
    color: var(--global-theme-color);
    display: inline-flex;
    font-size: 0.76rem;
    font-weight: 700;
    height: 2rem;
    justify-content: center;
    line-height: 1;
    width: 2rem;
  }

  .interest-card h3 {
    font-size: 0.98rem;
    line-height: 1.35;
    margin: 0;
  }

  .home-news-panel {
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    margin: 1rem 0 2.45rem;
    padding: 0.95rem 1rem;
    background: var(--global-bg-color);
  }

  .home-news-list {
    display: grid;
    gap: 0.72rem;
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .home-news-list li {
    display: grid;
    gap: 0.18rem;
  }

  .home-news-list time {
    color: var(--global-theme-color);
    font-size: 0.78rem;
    font-weight: 700;
  }

  .home-news-list span {
    color: var(--global-text-color);
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

  @media (max-width: 767px) {
    body {
      background-position: left -210px top 5.5rem;
      background-size: 390px;
    }

    .profile,
    .profile.float-right {
      float: none !important;
      margin: 0 auto 1.35rem !important;
      max-width: 170px;
    }

    .profile img {
      max-width: 160px;
    }

    .profile .more-info {
      text-align: center;
    }

    .education-card {
      grid-template-columns: 58px minmax(0, 1fr);
      column-gap: 0.8rem;
    }

    .education-logo {
      height: 58px;
      width: 58px;
    }

    .interest-grid {
      grid-template-columns: 1fr;
    }

    .selected-publication {
      grid-template-columns: 1fr;
    }

    .selected-publication img {
      width: 100%;
      max-width: 220px;
    }
  }
</style>

I am **Ningzhe Shi (时宁哲)**, a Ph.D. candidate in Computer Science and Technology at the Institute of Computing Technology, Chinese Academy of Sciences, and the University of Chinese Academy of Sciences. My Ph.D. Advisor is <a href="https://www.ict.ac.cn/sourcedb/cn/jssrck/200909/t20090917_2496807.html" target="_blank" rel="noopener noreferrer">Prof. Yiqing Zhou</a>. I received my B.Eng. in Communication Engineering from Xidian University, where my Undergraduate Advisor was <a href="https://web.xidian.edu.cn/junyuliu/" target="_blank" rel="noopener noreferrer">Prof. Junyu Liu</a>. During my undergraduate study, I received the National Scholarship and ranked 1st in class for comprehensive recommendation.

<div class="education-strip" aria-label="Education">
  <article class="education-card">
    <div class="education-logo">
      <img src="{{ '/assets/img/logos/ucas-emblem.png' | relative_url }}" alt="University of Chinese Academy of Sciences emblem">
    </div>
    <div>
      <span class="education-year">2021 - present</span>
      <strong>Ph.D. Candidate in Computer Science and Technology</strong>
      <span>Institute of Computing Technology, Chinese Academy of Sciences / University of Chinese Academy of Sciences</span>
    </div>
  </article>
  <article class="education-card">
    <div class="education-logo">
      <img src="{{ '/assets/img/logos/xidian-emblem.png' | relative_url }}" alt="Xidian University emblem">
    </div>
    <div>
      <span class="education-year">2017 - 2021</span>
      <strong>B.Eng. in Communication Engineering</strong>
      <span>Xidian University · National Scholarship · Ranked 1st in class for comprehensive recommendation</span>
    </div>
  </article>
</div>

## Research interests

<div class="interest-grid">
  <section class="interest-card">
    <span class="interest-index">01</span>
    <h3>AI-Native 6G Networks</h3>
  </section>
  <section class="interest-card">
    <span class="interest-index">02</span>
    <h3>Cloud-Edge Collaborative AI Services</h3>
  </section>
  <section class="interest-card">
    <span class="interest-index">03</span>
    <h3>Integrated Sensing, Communication, Computing, and Intelligence</h3>
  </section>
  <section class="interest-card">
    <span class="interest-index">04</span>
    <h3>Space AI Computing Networks</h3>
  </section>
  <section class="interest-card">
    <span class="interest-index">05</span>
    <h3>RAG and AI Agent Memory Systems</h3>
  </section>
  <section class="interest-card">
    <span class="interest-index">06</span>
    <h3>Wireless Resource Optimization</h3>
  </section>
</div>

## News

<div class="home-news-panel">
  {% assign news_items = site.news | sort: "date" | reverse %}
  {% if news_items.size > 0 %}
    <ul class="home-news-list">
      {% for item in news_items limit: 6 %}
        <li>
          <time datetime="{{ item.date | date_to_xmlschema }}">{{ item.date | date: "%b %-d, %Y" }}</time>
          <span>{{ item.content | strip_html | strip_newlines | strip }}</span>
        </li>
      {% endfor %}
    </ul>
  {% else %}
    <p>More updates coming soon.</p>
  {% endif %}
</div>

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

{% include visitor_counter.liquid %}
