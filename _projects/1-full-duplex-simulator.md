---
layout: page
title: Multi-Channel Access for In-Band Full-Duplex Ad Hoc Networks
period: Oct. 2022 - Jun. 2023
role: Technical Lead
category: Engineering Systems
featured: true
importance: 8
summary: Multi-channel access, interference coordination, and system-level simulation for simultaneous same-frequency full-duplex ad hoc networks.
contribution: Led the technical design of the access mechanism, throughput model, MAC-layer channel-selection logic, and large-scale simulator implementation.
results:
  - "Concurrent full-duplex access"
  - ">1,000-node simulation target"
  - "Patent and software copyright"
tags:
  - Full-Duplex Networking
  - Ad Hoc Networks
  - MAC Protocols
  - Network Simulation
  - Interference Coordination
outputs:
  - Authorized Software Copyright
  - Invention Patent
  - System Prototype
---

<style>
  .project-figure {
    margin: 1.5rem 0;
  }

  .project-figure img {
    width: 100%;
    height: auto;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background: #fff;
  }

  .project-figure figcaption {
    color: var(--global-text-color-light);
    font-size: 0.9rem;
    margin-top: 0.5rem;
  }
</style>

## Overview

Led the technical work on multi-channel access for simultaneous same-frequency full-duplex ad hoc networks. The project studied how large numbers of infrastructure-less nodes can share channels while residual self-interference, inter-node interference, channel contention, and concurrent transmissions are all present.

<figure class="project-figure">
  <img src="{{ '/assets/img/projects/full-duplex-simulator-architecture.svg' | relative_url }}" alt="Distributed full-duplex simulator architecture">
  <figcaption>The system-level simulator coordinates node execution, channel computation, mobility modeling, and visualization through a central time-slot controller.</figcaption>
</figure>

## Challenge

- Full-duplex access must model residual self-interference and inter-node interference together.
- Multi-node concurrent access creates channel contention, hidden interference, and MAC-layer coordination pressure.
- Large-scale protocol evaluation requires a simulator that connects traffic generation, routing, MAC access, physical transmission, interference, SINR, and reception decisions.
- Distributed modules must advance synchronously on a unified time-slot timeline.

## My Contributions

- Led the technical route, access-mechanism design, core algorithm implementation, and performance validation.
- Built a throughput-analysis model for concurrent full-duplex multi-node access.
- Designed multi-channel interference coordination and access-control logic for channel selection, contention, backoff, and concurrent transmission.
- Architected a distributed system-level simulation platform with a central controller, network-node workers, channel-computation modules, mobility modules, and visualization modules.
- Implemented a WebSocket-based coordination workflow to extend computing resources across workers.
- Built a cross-layer node model covering application traffic, network routing and clustering, MAC access, physical transmission, interference evaluation, and reception decisions.

## Outcomes

- Delivered a system-level simulation prototype for large-scale full-duplex networking research.
- Supported protocol evaluation scenarios involving more than 1,000 nodes.
- Produced one granted invention patent and one registered software copyright related to full-duplex ad hoc networking.

## Related Outputs

- [Patents and Software Copyrights]({{ '/publications/#patents' | relative_url }})
- Authorized software copyright: Large-Scale Full-Duplex Network Simulation System
- Related invention patent on ad hoc channel access
