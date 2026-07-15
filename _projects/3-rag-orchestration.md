---
layout: page
title: Knowledge-Aware Joint Scheduling and Retrieval Activation for RAG Services
period: Oct. 2025 - Jun. 2026
role: Main Contributor
category: AI Systems
featured: true
importance: 2
summary: Cloud-edge RAG/GAI service orchestration that jointly decides where to serve a task and whether retrieval should be activated.
contribution: Built a knowledge-aware model of task semantics, server-side knowledge coverage, retrieval activation, computation, delay, and energy, then designed a joint scheduling mechanism.
results:
  - "Adaptive retrieval activation"
  - "67% delay reduction vs always-on"
  - "Submitted to a CCF-A journal"
tags:
  - RAG
  - Cloud-Edge Computing
  - Knowledge-Aware Scheduling
  - Retrieval Activation
  - Resource Optimization
outputs:
  - Simulation Framework
  - Algorithm Prototype
  - Journal Submission
---

## Overview

This project studies knowledge-aware orchestration for retrieval-augmented GAI services deployed across heterogeneous edge and cloud nodes. The core idea is that the best decision is not simply the fastest or least loaded server; the scheduler must jointly choose the service node and decide whether retrieval should be activated for the current task.

## Challenge

- Edge and cloud nodes maintain heterogeneous knowledge bases.
- Real-time loads, transmission conditions, retrieval delay, and retrieval energy change dynamically.
- Retrieval can reduce downstream generation workload when useful knowledge is available, but unnecessary retrieval may increase delay and energy consumption.

## My Contributions

- Served as a main contributor and led the knowledge-aware joint scheduling and retrieval activation design.
- Modeled task semantic requirements, server-side knowledge coverage, retrieval activation, computing cost, transmission delay, and energy consumption in a unified optimization framework.
- Designed a dynamic orchestration mechanism that jointly decides task offloading/scheduling and retrieval activation according to knowledge relevance, resource state, and long-term energy pressure.
- Built a simulation environment to evaluate generation latency, retrieval overhead, response delay, and cloud-edge energy consumption.
- Analyzed when retrieval should be activated, and when it should be suppressed because its delay and energy overhead outweigh the knowledge-induced computation gain.

## Outcomes

The proposed mechanism adaptively activates retrieval instead of keeping retrieval always on or always off. In the evaluated settings, adaptive retrieval activation reduced average service delay by 67% and 62% compared with retrieval-always-on and retrieval-always-off baselines, respectively. The related work has been submitted to a CCF-A journal.
