---
layout: page
title: Knowledge-Matching-Aware Scheduling for RAG Services
period: Oct. 2025 - Jun. 2026
role: Main Contributor
category: AI Systems
featured: true
importance: 2
summary: Collaborative cloud-edge scheduling for RAG services under heterogeneous knowledge bases, dynamic loads, and communication variability.
contribution: Built a joint model of task semantics, knowledge coverage, computation, transmission delay, and energy, then designed a knowledge-aware scheduling mechanism.
results:
  - "approximately 50% energy reduction"
  - ">10% delay reduction"
  - "Submitted to a CCF-A journal"
tags:
  - RAG
  - Cloud-Edge Computing
  - Knowledge Matching
  - Task Scheduling
  - Resource Optimization
outputs:
  - Simulation Framework
  - Algorithm Prototype
  - Journal Submission
---

## Overview

This project studies collaborative scheduling for RAG services deployed across heterogeneous edge and cloud nodes. The core idea is that the best node for a generation request is not simply the fastest or least loaded one; it should also have a knowledge base that matches the task's semantic requirements.

## Challenge

- Edge and cloud nodes maintain heterogeneous knowledge bases.
- Real-time loads, transmission conditions, retrieval costs, and energy consumption change dynamically.
- RAG quality depends on both resource states and knowledge matching.

## My Contributions

- Served as a main contributor and led the knowledge-matching-aware scheduling design.
- Modeled task semantic requirements, node knowledge coverage, computing cost, transmission delay, and energy consumption in a unified optimization framework.
- Designed a dynamic RAG task orchestration mechanism based on task requirements, knowledge-matching degree, and resource states.
- Built a simulation environment to evaluate generation quality, response latency, and service energy consumption.
- Analyzed the quality-latency-energy tradeoff caused by retrieving better knowledge from farther or busier nodes.

## Outcomes

The proposed mechanism reduced energy consumption by approximately 50% while reducing service delay by more than 10% in the evaluated settings. The related work has been submitted to a CCF-A journal.
