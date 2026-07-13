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
</style>

<div class="cv-actions">
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener noreferrer">Download PDF</a>
</div>

## Research Profile

Ph.D. candidate researching 6G intelligent networks and AI service orchestration, with a focus on communication, sensing, computing, and knowledge resource optimization through reinforcement learning and optimization methods. My work spans cloud-edge collaborative AI services, RAG and AI Agent service orchestration, integrated sensing/communication/computing/intelligence, full-duplex networking, UAV communications, and space AI computing networks.

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
    <li>Investigated long-horizon memory mechanisms for AI agents in multi-turn interactions, focusing on context loss, redundant historical information, memory evolution, and response consistency.</li>
    <li>Surveyed retrieval-augmented memory, hierarchical storage, memory extraction, compression, forgetting, consolidation, and dynamic updating.</li>
    <li>Reproduced and analyzed the Mem-alpha memory architecture and formulated memory maintenance as a policy-optimization problem.</li>
    <li>Explored reinforcement-learning-based memory selection and updating.</li>
    <li>Investigated memory-aware task scheduling under cloud-edge collaborative architectures, considering storage, retrieval, inference, communication latency, and response quality.</li>
  </ul>
</div>

## Research Experience

<div class="cv-entry">
  <h3>Distributed System-Level Simulator for Large-Scale Full-Duplex Ad Hoc Networks</h3>
  <div class="cv-meta">Technical Lead, Institute of Computing Technology, Chinese Academy of Sciences, 2022 - 2023</div>
  <ul class="cv-list">
    <li>Architected a WebSocket-based distributed simulation platform integrating a central controller, network-node workers, channel computation, mobility modeling, and visualization.</li>
    <li>Designed priority-aware multi-channel access and cross-layer simulation logic covering traffic generation, routing, MAC access, physical transmission, interference, SINR, and reception decisions.</li>
    <li>Built core algorithms and performance-evaluation workflows for large-scale scenarios involving more than 1,000 nodes.</li>
    <li>Delivered a system prototype and one authorized software copyright.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Knowledge-Aware Cloud-Edge Orchestration for RAG Services</h3>
  <div class="cv-meta">Core Contributor, Institute of Computing Technology, Chinese Academy of Sciences, 2025 - 2026</div>
  <ul class="cv-list">
    <li>Modeled heterogeneous knowledge bases, real-time computing loads, communication conditions, retrieval cost, generation quality, service delay, and energy consumption.</li>
    <li>Designed a dynamic orchestration mechanism based on task semantics, node knowledge coverage, and resource states.</li>
    <li>Built a cloud-edge RAG simulation environment for comparative evaluation.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Memory-Aware Distributed Routing for Space AI Computing Networks</h3>
  <div class="cv-meta">Core Contributor, Institute of Computing Technology, Chinese Academy of Sciences, 2025 - 2026</div>
  <ul class="cv-list">
    <li>Modeled the coupling among task routing, node memory state, computing load, storage availability, and link conditions.</li>
    <li>Designed a distributed routing method for high-dimensional and dynamically changing network states.</li>
    <li>Evaluated the approach using a ground-based space-computing-network simulation environment.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>ISAC-Driven AIGC Service Orchestration</h3>
  <div class="cv-meta">Lead Researcher and First Author, Institute of Computing Technology, Chinese Academy of Sciences, 2024 - 2025</div>
  <ul class="cv-list">
    <li>Designed the content-accuracy-and-quality-aware metric and modeled sensing-computing-communication coupling for AIGC services.</li>
    <li>Formulated the joint resource-allocation problem and designed an LP-guided hierarchical deep reinforcement learning framework.</li>
    <li>Implemented comparative simulations, ablation studies, and performance analysis.</li>
  </ul>
</div>

<div class="cv-entry">
  <h3>Deception-Based UAV-Assisted Secure Communications</h3>
  <div class="cv-meta">Task Leader, Technical Lead, and First Author, Institute of Computing Technology, Chinese Academy of Sciences, 2021 - 2023</div>
  <ul class="cv-list">
    <li>Coordinated the technical route for secure communication modeling, deception signaling, UAV three-dimensional placement, beamforming, and power allocation.</li>
    <li>Built simulation validation workflows and delivered paper and invention-patent outputs related to anti-interference and secure communication.</li>
    <li>Achieved a gap of no more than 3% from the global optimum and improved secure transmission rate by more than 100% over the no-deception scheme.</li>
  </ul>
</div>

## Publications

1. **Ningzhe Shi**, Yiqing Zhou, Ling Liu, Yihao Wu, Hanxiao Yu, and Jinglin Shi. Service Satisfaction Based User Selection and Resource Allocation for NOMA-Based Multi-Cell MEC Networks. _IEEE Transactions on Mobile Computing_, 2026.
2. **Ningzhe Shi**, Yiqing Zhou, Ling Liu, Jinglin Shi, Yihao Wu, Haiwei Shi, and Hanxiao Yu. Content Accuracy and Quality Aware Resource Allocation Based on LP-Guided DRL for ISAC-Driven AIGC Networks. _IEEE Transactions on Mobile Computing_, 2026.
3. **Ningzhe Shi**, Ling Liu, Yiqing Zhou, Hanxiao Yu, Yihao Wu, Jingya Yang, and Jinglin Shi. Long-Term Fairness From Real-Time Decisions: Reward Adaptive Multi-Agent DRL for Wireless Communication With Imperfect CSI. _IEEE Transactions on Cognitive Communications and Networking_, 2026.
4. **Ningzhe Shi**, Yiqing Zhou, Yu Zhang, Zhijun Han, Ling Liu, and Jinglin Shi. Deception-Based Secure Communication for UAV-Assisted mmWave MIMO Systems. _China Communications_, 2026.
5. **Ningzhe Shi**, Yihao Wu, Yaxing Xu, Qing Cai, and Yiqing Zhou. Cross-Enabling of Operation, Information and Communication: Building the Foundation for Intelligent New-Generation Productivity. _Computing Magazine of the CCF_, 2025, 1(4): 82-91.

## Intellectual Property

1. 抗跟踪式干扰的信号发送方法、信号接收方法及系统. Granted invention patent: CN202211134854.X, 2024-09-24.
2. 一种基于中继位置选择和功率分配的抗干扰方法及系统. Granted invention patent: CN202310078808.0, 2025-05-27.
3. 无线网络资源分配系统的构建方法和资源管理方法. Granted invention patent: CN202310354794.0, 2026-04-07.
4. 无线网络资源分配系统的构建方法和资源管理方法. Patent application: PCT/CN2023/090283, 2023-04-24.
5. 一种全双工自组织网络实时仿真系统及方法. Patent application: CN202311719290.0, 2023-12-14.
6. 一种多用户 MIMO 信号检测模型. Patent application: CN202410018551.4, 2024-01-05.
7. 一种面向自组织网络的信道接入方法和通信系统. Patent application: CN202410348337.5, 2024-03-26.
8. 一种移动自组网数据路由方法、工业自组网系统. Patent application: CN202510873622.3, 2025-06-27.
9. 一种环境和资源状态感知的资源分配方法和系统. Patent application: CN202510955830.8, 2025-07-11.
10. 基于集成感知与通信的AI生成内容服务的资源分配方法. Patent application: CN202511053332.0, 2025-07-30.
11. 联合信道估计与信号检测的方法、信号接收机及存储介质. Patent application: CN202511536493.5, 2025-10-27.
12. 一种面向高速移动通信的发射装置及语义传输方法. Patent application: CN202610406457.5, 2026-03-31.
13. 大规模全双工网络仿真系统. Registered software copyright: 2024SR0082117, 2024-01-11.

## Honors and Awards

- Outstanding Graduate Student, Xinghang Program, Journal of Electronics & Information Technology, 2026.
- Outstanding Poster Award, Frontiers in Electronics and Information Conference, 2026.
- UCAS Outstanding Student Model, university-wide top 1%, 2026.
- ICT Outstanding Student, Institute of Computing Technology / State Key Laboratory of Processors, 2026.
- E Fund Financial Technology Doctoral Scholarship, 12 recipients institute-wide, 2025.
- UCAS Outstanding Student Cadre, 2025.
- UCAS Outstanding Student, 2023.
- UCAS First-Class Scholarship, 2021-2025, awarded for five consecutive years.
- Outstanding Graduate, Xidian University, 2021.
- First-Class Graduation Scholarship, Xidian University, 2021.
- Honorable Mention, Mathematical Contest in Modeling, 2020.
- National Scholarship, 2019.
- National Second Prize, China Undergraduate Mathematical Contest in Modeling, 2019.
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
  <div><span class="cv-skill-label">Research and Modeling:</span> Wireless and computing resource scheduling; integrated sensing, communication, computing, and intelligence; cloud-edge collaborative AI services; RAG service orchestration; AI Agent memory systems; space AI computing networks; cross-layer wireless network modeling.</div>
  <div><span class="cv-skill-label">Optimization and Learning:</span> Convex optimization; linear programming; evolutionary and heuristic algorithms; deep reinforcement learning; multi-agent reinforcement learning; generative diffusion models; quantum reinforcement learning; Lyapunov optimization.</div>
  <div><span class="cv-skill-label">Programming and Simulation:</span> Python; C++; MATLAB; Shell; PyTorch; custom reinforcement-learning environments; system-level network simulation; large-scale experiment automation; data processing and visualization.</div>
  <div><span class="cv-skill-label">Systems and Engineering:</span> Distributed simulation architecture; WebSocket-based module communication; wireless protocol-stack modeling; MAC and resource-allocation algorithm implementation; cloud-edge system modeling; performance evaluation and technical reporting.</div>
  <div><span class="cv-skill-label">Research Project Execution:</span> Research proposal preparation; technical scheme design; simulation and prototype validation; third-party testing support; mid-term project review; project completion and acceptance; patent and software-copyright preparation.</div>
  <div><span class="cv-skill-label">Academic Communication:</span> IEEE journal paper writing; English literature review; peer review; technical presentations; research reports; cross-team technical coordination.</div>
</div>
