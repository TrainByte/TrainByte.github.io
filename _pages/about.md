---
layout: about
title: about
permalink: /
subtitle: Ph.D. in Computer Science | Institute of Computing Technology, Chinese Academy of Sciences
profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: ""
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
    background-position: center center;
    background-repeat: no-repeat;
    background-size: min(58vw, 640px);
  }

  .profile {
    max-width: 128px;
    margin-left: 1.25rem;
  }

  .profile img {
    width: 100%;
    max-width: 116px;
    height: auto;
  }

  .profile .more-info {
    display: none;
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

  .about-intro {
    font-size: 1.01rem;
    line-height: 1.7;
  }

  .about-intro p {
    margin-bottom: 0.72rem;
  }

  .profile-strip-stack {
    clear: both;
    display: grid;
    gap: 0.82rem;
    margin: 1.35rem 0 2.55rem;
  }

  .profile-strip,
  .career-note {
    background:
      linear-gradient(90deg, rgba(46, 127, 255, 0.08), rgba(176, 62, 98, 0.055)),
      var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-left: 4px solid var(--global-theme-color);
    border-radius: 8px;
    color: var(--global-text-color);
    margin: 0;
    padding: 0.82rem 0.95rem;
  }

  .profile-strip strong,
  .career-note strong {
    color: var(--global-theme-color);
  }

  .education-strip {
    display: contents;
  }

  .education-card {
    display: grid;
    grid-template-columns: 62px minmax(0, 1fr);
    gap: 0.42rem;
    column-gap: 0.9rem;
    align-items: center;
    border: 1px solid var(--global-divider-color);
    border-left: 4px solid rgba(46, 127, 255, 0.48);
    border-radius: 8px;
    padding: 0.82rem 0.95rem;
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
    height: 62px;
    justify-content: center;
    padding: 0.35rem;
    width: 62px;
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

  .education-place {
    color: var(--global-text-color-light);
    font-size: 0.88rem;
  }

  .interest-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.75rem;
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
    min-height: 5.6rem;
    overflow: hidden;
    padding: 0.95rem 1rem;
    position: relative;
  }

  .interest-card::after {
    background: linear-gradient(180deg, var(--global-theme-color), #b03e62);
    content: "";
    height: 100%;
    opacity: 0.82;
    position: absolute;
    right: 0;
    top: 0;
    width: 4px;
  }

  .interest-index {
    align-items: center;
    background: rgba(46, 127, 255, 0.08);
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
      background-position: center 5.8rem;
      background-size: 430px;
    }

    .profile,
    .profile.float-right {
      float: none !important;
      margin: 0 auto 1.35rem !important;
      max-width: 124px;
    }

    .profile img {
      max-width: 116px;
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

  @media (min-width: 768px) and (max-width: 1100px) {
    .interest-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }
</style>

<div class="about-intro">
  <p>I am <strong>Ningzhe Shi (时宁哲)</strong>, pursuing a <strong>Ph.D. in Computer Science and Technology</strong> at the Institute of Computing Technology, Chinese Academy of Sciences, and the University of Chinese Academy of Sciences, advised by <a href="https://www.ict.ac.cn/sourcedb/cn/jssrck/200909/t20090917_2496807.html" target="_blank" rel="noopener noreferrer">Prof. Yiqing Zhou</a>. I received my B.Eng. in Communication Engineering from Xidian University, where I was advised by <a href="https://web.xidian.edu.cn/junyuliu/" target="_blank" rel="noopener noreferrer">Prof. Junyu Liu</a>, received the National Scholarship, and ranked 1st in class.</p>
  <p>My work explores how communication, sensing, computing, and intelligence can be jointly orchestrated in intelligent 6G networks to better serve AI services. I focus on translating coupled system constraints into tractable models, learning-based algorithms, and simulation evidence for deployment-oriented network design. I have published <strong>20+ papers</strong> in international and Chinese journals and conferences, including IEEE TMC, TCCN, TWC, TVT, TNSE, WCL, WCNC, VTC, and China Communications. If you are interested in academic collaboration, please feel free to email me at <a href="mailto:shiningzhe21b@ict.ac.cn">shiningzhe21b@ict.ac.cn</a>.</p>
</div>

<div class="profile-strip-stack" aria-label="Career and education">
  <p class="career-note"><strong>Open to career opportunities:</strong> industrial research and engineering roles, as well as academic or faculty-track opportunities, focused on intelligent networks, AI service orchestration, and cloud-edge systems.</p>

  <div class="education-strip" aria-label="Education">
    <article class="education-card">
      <div class="education-logo">
        <img src="{{ '/assets/img/logos/ucas-emblem.png' | relative_url }}" alt="University of Chinese Academy of Sciences emblem">
      </div>
      <div>
        <span class="education-year">2021 - present</span>
        <strong>Ph.D. in Computer Science and Technology</strong>
        <span>Institute of Computing Technology, Chinese Academy of Sciences / University of Chinese Academy of Sciences</span>
        <span class="education-place">Beijing, China</span>
      </div>
    </article>
    <article class="education-card">
      <div class="education-logo">
        <img src="{{ '/assets/img/logos/xidian-emblem.png' | relative_url }}" alt="Xidian University emblem">
      </div>
      <div>
        <span class="education-year">2017 - 2021</span>
        <strong>B.Eng. in Communication Engineering</strong>
        <span>Xidian University · National Scholarship · Ranked 1st in class</span>
        <span class="education-place">Xi'an, Shaanxi, China</span>
      </div>
    </article>
  </div>
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
        <span class="publication-badge venue">China Com.</span>
        <span class="publication-badge cic">T1 CIC</span>
        <span class="publication-badge status">Published</span>
      </div>
    </div>
  </article>
</div>

{% include visitor_counter.liquid %}
