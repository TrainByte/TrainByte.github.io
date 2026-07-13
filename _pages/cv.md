---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/rendercv/rendercv_output/Ningzhe_Shi_CV.pdf
description: Education, research profile, internship, research experience, publications, intellectual property, awards, service, outreach, leadership, and skills.
toc:
  sidebar: left
---

<style>
  body {
    background-image:
      url("{{ '/assets/img/logos/ucas-watermark.png' | relative_url }}"),
      url("{{ '/assets/img/logos/xidian-watermark.png' | relative_url }}");
    background-attachment: fixed, fixed;
    background-position:
      left clamp(-260px, -15vw, -120px) top 7rem,
      right clamp(-280px, -16vw, -120px) bottom 4rem;
    background-repeat: no-repeat, no-repeat;
    background-size:
      min(43vw, 520px),
      min(46vw, 560px);
  }

  .cv-actions {
    margin: 0.75rem 0 1.25rem;
  }

  .cv-actions a {
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    display: inline-flex;
    font-weight: 600;
    line-height: 1.2;
    padding: 0.45rem 0.7rem;
  }

  .cv-list li {
    margin-bottom: 0.45rem;
  }

  .cv-entry {
    margin-bottom: 1rem;
  }

  .cv-entry h3 {
    font-size: 1rem;
    line-height: 1.35;
    margin-bottom: 0.25rem;
  }

  .cv-meta {
    color: var(--global-text-color-light);
    font-size: 0.92rem;
    margin-bottom: 0.4rem;
  }

  .cv-skills {
    display: grid;
    gap: 0.45rem;
  }

  .cv-skill-label {
    font-weight: 700;
  }

  @media (max-width: 767px) {
    body {
      background-position:
        left -210px top 5.5rem,
        right -230px bottom 3rem;
      background-size: 380px, 410px;
    }
  }
</style>

<div class="cv-actions">
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener noreferrer">Download CV PDF</a>
</div>

## Research Profile

Ph.D. candidate researching 6G intelligent networks and AI service orchestration, with a focus on communication, sensing, computing, memory, and knowledge-resource optimization through reinforcement learning and mathematical optimization. My work spans cloud-edge collaborative AI services, RAG and AI Agent service orchestration, integrated sensing/communication/computing/intelligence, full-duplex networking, UAV communications, and space AI computing networks.

## Education

<div class="cv-entry">
  <h3>Institute of Computing Technology, Chinese Academy of Sciences; University of Chinese Academy of Sciences</h3>
  <div class="cv-meta">Ph.D. Candidate, Computer Science and Technology, Beijing, China, Sep. 2021 - present</div>
  <ul class="cv-list">
    <li>Ph.D. Advisor: <a href="https://www.ict.ac.cn/sourcedb/cn/jssrck/200909/t20090917_2496807.html" target="_blank" rel="noopener noreferrer">Prof. Yiqing Zhou</a>.</li>
    <li>Discipline rated A+ in the national subject assessment.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Xidian University</h3>
  <div class="cv-meta">B.Eng., Communication Engineering, Xi'an, China, Sep. 2017 - Jul. 2021</div>
  <ul class="cv-list">
    <li>Undergraduate Research Advisor: <a href="https://web.xidian.edu.cn/junyuliu/" target="_blank" rel="noopener noreferrer">Prof. Junyu Liu</a>.</li>
    <li>Received the National Scholarship and ranked 1st in class for comprehensive recommendation.</li>
    <li>Discipline rated A+ in the national subject assessment.</li>
  </ul>
</div>

## Internship Experience

<div class="cv-entry">
  <h3>China Mobile, Digital Intelligence Department - AI Agent Algorithm Intern</h3>
  <div class="cv-meta">China, Jan. 2026 - Mar. 2026</div>
  <ul class="cv-list">
    <li>Investigated long-horizon memory mechanisms for AI agents in multi-turn interactions, focusing on context forgetting, historical redundancy, and response consistency.</li>
    <li>Surveyed retrieval-augmented memory, hierarchical storage, self-evolving memory updates, memory extraction, compression, forgetting, and dynamic updating.</li>
    <li>Reproduced and analyzed the Mem-alpha memory architecture and formulated memory selection, compression, and updating as a policy-optimization problem.</li>
    <li>Studied reinforcement-learning-based memory maintenance and memory-aware LLM task scheduling under end-edge-cloud collaboration.</li>
  </ul>
</div>

## Research Experience

<div class="cv-entry">
  <h3>Knowledge-Matching-Aware Scheduling for RAG Services</h3>
  <div class="cv-meta">Main Contributor, Institute of Computing Technology, Chinese Academy of Sciences, Oct. 2025 - Jun. 2026</div>
  <ul class="cv-list">
    <li>Modeled task semantics, node knowledge coverage, computing cost, transmission delay, generation quality, and energy consumption for cloud-edge RAG services.</li>
    <li>Designed a knowledge-matching-aware RAG task scheduling mechanism under heterogeneous knowledge bases and dynamic resource states.</li>
    <li>Built a simulation environment; reduced energy consumption by approximately 50% and service delay by more than 10% in evaluated settings.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Memory-Aware Distributed Routing for Space AI Computing Networks</h3>
  <div class="cv-meta">Main Contributor, Institute of Computing Technology, Chinese Academy of Sciences, Oct. 2025 - Mar. 2026</div>
  <ul class="cv-list">
    <li>Modeled the coupling among task routing, node memory state, onboard computing load, storage availability, and link conditions.</li>
    <li>Designed a distributed routing method for high-dimensional dynamic network states and introduced diffusion-assisted policy generation.</li>
    <li>Validated the method on a ground-based space computing network simulator, reducing end-to-end routing delay by more than 15%.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Distributed Quantum Reinforcement Learning for AIGC Cloud-Edge Scheduling</h3>
  <div class="cv-meta">Main Contributor, Institute of Computing Technology, Chinese Academy of Sciences, Jun. 2025 - Dec. 2025</div>
  <ul class="cv-list">
    <li>Modeled collaborative cloud-edge processing for multi-user AIGC services, coupling task offloading, computing allocation, and service delay.</li>
    <li>Designed a distributed hybrid quantum-classical reinforcement learning scheduler using parameterized quantum circuits and classical neural networks.</li>
    <li>Reduced model parameters by more than 95% and average service delay by more than 30% compared with baseline methods in simulation.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>ISAC-Driven AIGC Service Orchestration</h3>
  <div class="cv-meta">Main Contributor and First Author, Institute of Computing Technology, Chinese Academy of Sciences, Jan. 2024 - Jun. 2025</div>
  <ul class="cv-list">
    <li>Designed a content-accuracy-and-quality-aware service metric and modeled sensing, computing, communication, and AIGC service experience as a coupled system.</li>
    <li>Formulated the joint resource-allocation problem and designed an LP-guided hierarchical reinforcement learning framework.</li>
    <li>Improved average user service experience by more than 50% in evaluated settings; related work was published in IEEE Transactions on Mobile Computing.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>User Selection and Resource Allocation for High-Concurrency AI Services</h3>
  <div class="cv-meta">Main Contributor and First Author, Institute of Computing Technology, Chinese Academy of Sciences, Dec. 2022 - Dec. 2024</div>
  <ul class="cv-list">
    <li>Modeled user access, bandwidth, subchannels, transmit power, edge computing resources, and service satisfaction in multi-cell MEC networks.</li>
    <li>Designed a joint optimization algorithm for user selection, channel assignment, power control, and edge computing resource allocation.</li>
    <li>Improved average user satisfaction by more than 50%; related work was published in IEEE Transactions on Mobile Computing.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Adaptive Fair Resource Scheduling Under Imperfect CSI</h3>
  <div class="cv-meta">Main Contributor and First Author, Institute of Computing Technology, Chinese Academy of Sciences, May 2022 - May 2024</div>
  <ul class="cv-list">
    <li>Built a channel-uncertainty-aware resource allocation model for multi-cell multi-user downlink communications under imperfect CSI.</li>
    <li>Designed a reward-adaptive multi-agent DRL scheduler balancing long-term fairness and network service rate.</li>
    <li>Improved long-term fairness by 13% and service rate by more than 10%; related work was published in IEEE Transactions on Cognitive Communications and Networking.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Multi-Channel Access for In-Band Full-Duplex Ad Hoc Networks</h3>
  <div class="cv-meta">Technical Lead, Institute of Computing Technology, Chinese Academy of Sciences, Oct. 2022 - Jun. 2023</div>
  <ul class="cv-list">
    <li>Designed multi-channel interference coordination and access-control mechanisms for full-duplex ad hoc networks with residual self-interference and inter-node interference.</li>
    <li>Built a distributed WebSocket-based system-level simulator integrating node workers, channel computation, mobility modeling, and visualization.</li>
    <li>Delivered a system prototype and related invention patent/software copyright outputs.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>UAV-Assisted Secure Transmission Under Deception and Jamming</h3>
  <div class="cv-meta">Task Leader, Technical Lead, and First Author, Institute of Computing Technology, Chinese Academy of Sciences, Sep. 2021 - Jun. 2023</div>
  <ul class="cv-list">
    <li>Built a UAV-assisted mmWave MIMO secure communication model covering legitimate links, deception links, jamming sources, and UAV-assisted nodes.</li>
    <li>Designed joint optimization for beamforming, UAV three-dimensional placement, and power allocation under complex electromagnetic confrontation.</li>
    <li>Improved secure transmission rate to approximately two times that of the no-deception baseline; related work was published in China Communications and one invention patent was granted.</li>
  </ul>
</div>

## Publications

1. **Ningzhe Shi**, Yiqing Zhou, Ling Liu, Yihao Wu, Hanxiao Yu, and Jinglin Shi. Service Satisfaction Based User Selection and Resource Allocation for NOMA-Based Multi-Cell MEC Networks. _IEEE Transactions on Mobile Computing_, 2026.
2. **Ningzhe Shi**, Yiqing Zhou, Ling Liu, Jinglin Shi, Yihao Wu, Haiwei Shi, and Hanxiao Yu. Content Accuracy and Quality Aware Resource Allocation Based on LP-Guided DRL for ISAC-Driven AIGC Networks. _IEEE Transactions on Mobile Computing_, 2026.
3. **Ningzhe Shi**, Ling Liu, Yiqing Zhou, Hanxiao Yu, Yihao Wu, Jingya Yang, and Jinglin Shi. Long-Term Fairness From Real-Time Decisions: Reward Adaptive Multi-Agent DRL for Wireless Communication With Imperfect CSI. _IEEE Transactions on Cognitive Communications and Networking_, 2026.
4. **Ningzhe Shi**, Yiqing Zhou, Yu Zhang, Zhijun Han, Ling Liu, and Jinglin Shi. Deception-Based Secure Communication for UAV-Assisted mmWave MIMO Systems. _China Communications_, 2026.
5. **Ningzhe Shi**, Yihao Wu, Yaxing Xu, Qing Cai, and Yiqing Zhou. Cross-Enabling of Operation, Information and Communication: Building the Foundation for Intelligent New-Generation Productivity. _Computing Magazine of the CCF_, 2025, 1(4): 82-91.

## Intellectual Property

1. Anti-Tracking Jamming-Resistant Signal Transmission Method, Signal Reception Method, and System. Granted invention patent: CN202211134854.X, 2024-09-24.
2. Anti-Jamming Method and System Based on Relay Position Selection and Power Allocation. Granted invention patent: CN202310078808.0, 2025-05-27.
3. Construction Method and Resource Management Method for a Wireless Network Resource Allocation System. Granted invention patent: CN202310354794.0, 2026-04-07.
4. Construction Method and Resource Management Method for a Wireless Network Resource Allocation System. Patent application: PCT/CN2023/090283, 2023-04-24.
5. Real-Time Simulation System and Method for Full-Duplex Ad Hoc Networks. Patent application: CN202311719290.0, 2023-12-14.
6. Multi-User MIMO Signal Detection Model. Patent application: CN202410018551.4, 2024-01-05.
7. Channel Access Method and Communication System for Ad Hoc Networks. Patent application: CN202410348337.5, 2024-03-26.
8. Mobile Ad Hoc Network Data Routing Method and Industrial Ad Hoc Network System. Patent application: CN202510873622.3, 2025-06-27.
9. Environment- and Resource-State-Aware Resource Allocation Method and System. Patent application: CN202510955830.8, 2025-07-11.
10. Resource Allocation Method for AI-Generated Content Services Based on Integrated Sensing and Communication. Patent application: CN202511053332.0, 2025-07-30.
11. Joint Channel Estimation and Signal Detection Method, Signal Receiver, and Storage Medium. Patent application: CN202511536493.5, 2025-10-27.
12. Transmission Device and Semantic Transmission Method for High-Mobility Communications. Patent application: CN202610406457.5, 2026-03-31.
13. Large-Scale Full-Duplex Network Simulation System. Registered software copyright: 2024SR0082117, 2024-01-11.

## Honors and Awards

- Outstanding Graduate Student, Xinghang Program, Journal of Electronics & Information Technology, 2026.
- Outstanding Poster Award, Frontiers in Electronics and Information Conference, 2026.
- UCAS Outstanding Student Model, university-wide top 1%, 2026.
- ICT Outstanding Student, Institute of Computing Technology / State Key Laboratory of Processors, 2026.
- E Fund Financial Technology Doctoral Scholarship, 12 recipients institute-wide, 2025.
- UCAS Outstanding Student Cadre, 2025.
- Outstanding Volunteer, Chinese Academy of Sciences Public Science Day, 2023, 2024, and 2025.
- UCAS Outstanding Student, 2023.
- UCAS First-Class Scholarship, 2021-2025, awarded for five consecutive years.
- Outstanding Graduate, Xidian University, 2021.
- First-Class Graduation Scholarship, Xidian University, 2021.
- Honorable Mention, Mathematical Contest in Modeling, 2020.
- National Scholarship, 2019.
- National Second Prize, China Undergraduate Mathematical Contest in Modeling, 2019.
- National Encouragement Scholarship, 2018.
- Third Prize, CETC-10 Communication Cup, 2019.

## Academic Service

- **Program Committee:** Technical Program Committee Member, IEEE International Conference on Communications (ICC), 2026.
- **Academic Correspondence:** Academic Correspondent, _Digital Communications and Networks_.
- **Peer Review:** IEEE Transactions on Mobile Computing (TMC); IEEE Transactions on Communications (TCOM); IEEE Internet of Things Journal; IEEE Transactions on Vehicular Technology (TVT); Science China Information Sciences; China Communications; IEEE International Conference on Communications (ICC); IEEE Vehicular Technology Conference (VTC); Journal on Communications; Journal of Electronics & Information Technology.

## Outreach and Public Engagement

- Science outreach volunteer, Chinese Academy of Sciences Public Science Day.
- Committee Member, UCAS Science Popularization Association.
- Participated in public science communication, research demonstrations, and science outreach activities.
- Outstanding Science Popularization Volunteer, Bureau of Academic Divisions, Chinese Academy of Sciences.

## Leadership and Student Service

- **Graduate Stage:** Vice President, Haidian Branch of the Volunteer Federation; Committee Member, UCAS Science Popularization Association; Class Mental Health Liaison.
- **Undergraduate Stage:** Youth League Branch Secretary; Team Leader, Horizon Volunteer Team, School of Telecommunications Engineering, Xidian University.

## Skills

<div class="cv-skills">
  <div><span class="cv-skill-label">AI-Native Network Research:</span> 6G intelligent networks; cloud-edge collaborative AI services; RAG service orchestration; AI Agent memory systems; space AI computing networks; ISAC-driven AIGC services.</div>
  <div><span class="cv-skill-label">Optimization and Learning:</span> Reinforcement learning; multi-agent DRL; LP-guided hierarchical scheduling; diffusion-assisted policy generation; quantum-classical reinforcement learning; convex optimization; robust and fairness-aware resource allocation.</div>
  <div><span class="cv-skill-label">Wireless and Computing Systems:</span> MEC/NOMA networks; full-duplex ad hoc networks; UAV-assisted secure communications; integrated sensing, communication, computing, and knowledge-resource optimization.</div>
  <div><span class="cv-skill-label">Implementation and Simulation:</span> Python; PyTorch; MATLAB; C++; Shell; custom RL environments; system-level wireless simulation; distributed WebSocket-based simulation; experiment automation and visualization.</div>
  <div><span class="cv-skill-label">Research Delivery:</span> Problem formulation; algorithm design; simulation validation; ablation studies; technical reporting; journal paper writing; patent and software-copyright preparation; cross-team technical coordination.</div>
</div>
