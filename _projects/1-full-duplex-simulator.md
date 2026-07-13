---
layout: page
title: Distributed System-Level Simulator for Large-Scale Full-Duplex Ad Hoc Networks
period: 2022 - 2023
role: Technical Lead
category: Engineering Systems
featured: true
importance: 1
summary: Distributed system-level simulation for large-scale, infrastructure-less, and mission-critical ad hoc networks.
contribution: Architected the controller-worker simulation workflow, cross-layer node model, channel engine, and priority-aware multi-channel full-duplex access mechanism.
results:
  - ">1,000-node design target"
  - "1 authorized software copyright"
tags:
  - Distributed Systems
  - Network Simulation
  - WebSocket
  - MAC Protocols
  - Cross-Layer Modeling
outputs:
  - Authorized Software Copyright
  - Related Patent Applications
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

Led the technical development of a distributed system-level simulation platform for large-scale in-band full-duplex ad hoc networks. The platform was designed to overcome the scalability limitations of conventional single-machine, event-driven simulators when evaluating networks with thousands of nodes, complex interference, and cross-layer protocols.

<figure class="project-figure">
  <img src="{{ '/assets/img/projects/full-duplex-simulator-architecture.svg' | relative_url }}" alt="Distributed full-duplex simulator architecture">
  <figcaption>The platform decouples node execution, channel computation, mobility modeling, and visualization while coordinating all modules through a central time-slot controller.</figcaption>
</figure>

## Challenge

- Centralized single-machine simulation becomes computationally expensive when the network size exceeds 1,000 nodes.
- Full-duplex networking requires simultaneous modeling of residual self-interference, inter-node interference, and concurrent multi-link access.
- Network behavior spans application-layer traffic generation, network-layer routing and clustering, MAC-layer access control, physical-layer transmission and reception, and channel modeling.
- Distributed modules must advance synchronously on a unified time-slot timeline.
- The platform needs to support protocol evaluation, runtime control, logging, metrics, historical inspection, and state visualization.

## My Contributions

- Led the system architecture and core algorithm design as the technical lead.
- Designed a distributed simulation architecture composed of a central simulation controller, distributed network-node workers, channel-processing modules, mobility modules, and visualization and management modules.
- Designed a WebSocket-based inter-module communication mechanism to coordinate simulation states and extend available computing resources across multiple workers.
- Developed the time-slot synchronization workflow, including simulation initialization, slot-start notification, node processing, channel processing, result aggregation, slot completion, and visualization update.
- Built a cross-layer node model covering application-layer traffic generation, network-layer routing and clustering, MAC-layer access control, and physical-layer transmission and reception.
- Designed or implemented channel-processing logic involving propagation delay, transmit and receive gains, received-power calculation, background noise, inter-node interference, SINR evaluation, capture-effect-based reception decisions, and per-channel reception-result generation.
- Designed a priority-aware multi-channel full-duplex access mechanism that classifies traffic into priority queues, estimates channel load independently, assigns differentiated transmission thresholds, selects the least-loaded available channel, applies backoff when the threshold is not satisfied, and coordinates concurrent access under residual self-interference and inter-node interference.
- Implemented platform management capabilities including start, continue, step, stop, logging, performance-statistics collection, historical-result inspection, and node-state visualization.

## Technical Highlights

- WebSocket-based distributed module coordination
- Central time-slot controller for synchronous simulation
- Cross-layer node model from traffic generation to reception decision
- Channel engine for interference, SINR, and capture-effect modeling
- Priority-aware multi-channel full-duplex MAC access
- Designed for simulations involving more than 1,000 nodes, with a distributed architecture illustrated for scenarios of up to 5,000 nodes

## Outcomes

- Delivered an end-to-end system-level simulation prototype for large-scale full-duplex networking research.
- Connected protocol design, channel modeling, distributed execution, performance evaluation, and visualization in one platform.
- Produced one authorized software copyright: Large-Scale Full-Duplex Network Simulation System V1.0, registration number 2024SR0082117.
- Contributed to related patent applications on full-duplex ad hoc network simulation and channel access.

## Related Outputs

- [Intellectual Property]({{ '/publications/#intellectual-property' | relative_url }})
- System Prototype
- Authorized Software Copyright

## Keywords / Tags

Distributed Systems; Network Simulation; WebSocket; Cross-Layer Modeling; MAC Protocols; Full-Duplex Networking.
