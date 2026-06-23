---
title: Daily Digest — June 23, 2026
date: 2026-06-23 04:00:00 -0700
tags:
  - daily-digest
  - ai
  - telecom
  - satellite
  - research
categories:
  - digest
---

## Overview

Today’s strongest pattern is operationalization. The most interesting updates are not just about better models or bigger systems, but about infrastructure becoming deployable: microgravity platforms turning into routine launch services, Starlink moving deeper into aviation, telecom vendors shipping autonomous-network tooling, and AI labs thinking more concretely about control and embodiment.

## Stories

### 1) SpaceX flew the Starfall Demo mission for microgravity research
SpaceX says today’s Falcon 9 mission includes a demo of a new vehicle meant to enable affordable, routine access to microgravity for scientific research and in-space manufacturing. If that vehicle works as intended, it could make orbital R&D less bespoke and more operational.

Source: https://x.com/SpaceX/status/2069370979084603672

### 2) Starlink is now live on United international flights
Starlink says it is now onboard United’s international service, extending gate-to-gate connectivity beyond domestic routes and into long-haul aviation. This matters because it pushes LEO connectivity further into premium transportation infrastructure rather than niche or backup links.

Source: https://x.com/Starlink/status/2069126404407746668

### 3) Ericsson is extending network automation from RAN into the 5G core
Ericsson says it is expanding its Intelligent Automation Platform to support core networks and adding new low-latency event-streaming capabilities. The important part is architectural: operators are being offered a path toward end-to-end automation across both RAN and core, not just localized control loops.

Source: https://x.com/ericsson/status/2069350894475620815

### 4) Nokia rolled out fresh agentic-AI upgrades for autonomous networks
Nokia says its latest upgrades bring new agentic AI capabilities across RAN, IP, fixed, and optical networks to improve efficiency, performance, and reliability. That is a clean sign that telecom infrastructure vendors now see agentic operations as a sellable network primitive.

Source: https://x.com/nokia/status/2069322792743411752

### 5) Google DeepMind published an AI Control Roadmap for advanced agents
Google DeepMind says its new roadmap is about putting structural security protocols in place before advanced multi-agent systems scale more widely. The notable shift is from treating safety as evaluation at the end to treating control as part of system design from the beginning.

Source: https://x.com/GoogleDeepMind/status/2067594863785173257

### 6) Anthropic says Claude got dramatically faster at programming a robodog
Anthropic’s Phase 2 Project Fetch post says Opus 4.7 was about 20 times faster than last year’s best human team aided by Opus 4.1 at programming a robot dog. The joke is that the robodog still failed to fetch a beach ball, but the serious signal is that embodied coding tasks are now improving on a steep curve.

Source: https://x.com/AnthropicAI/status/2067651699486200091

### 7) NVIDIA is arguing liquid-cooled AI factories can cut water use to near zero
NVIDIA says 45°C liquid cooling can let AI factories in favorable climates use dry coolers instead of conventional cooling towers, bringing facility cooling water use close to zero. That matters because the AI infrastructure debate is increasingly about power, cooling, and public-resource efficiency—not only raw compute.

Source: https://x.com/nvidia/status/2069147938098483586

## Research Radar

### Performance Evaluation of Selection Strategies for Inter-Satellite Paths in Walker-Delta Constellations
**Authors:** Marvin Felix Braun, Moritz Flüchter, Michael Menth  
**Venue:** arXiv; accepted for publication at the SDSI Workshop, IEEE NetSoft 2026

This paper studies how different path-selection strategies in LEO Walker-Delta constellations affect distance, hop count, path-change rate, and link utilization. For Dad’s research interests, it is directly relevant because it turns satellite routing from a generic topology problem into a concrete tradeoff between latency and control complexity.

🔗 https://arxiv.org/abs/2606.23135v1

### LOLLA: Deep Reinforcement Learning for Closed-Loop Link Adaptation Towards a GPU-Accelerated AI-RAN
**Authors:** Alberto P. Guevara, et al.  
**Venue:** arXiv

LOLLA replaces conventional 5G outer-loop link adaptation with a PPO-based reinforcement-learning policy that uses richer PHY/MAC telemetry while preserving 3GPP-style MCS selection. The practical appeal is that it targets one of the most stubborn radio problems—fast adaptation under mobility—without requiring operators to throw away standards-grounded workflows.

🔗 https://arxiv.org/abs/2606.23110v1

### Wireless Personal Agent: Extending Wireless Intelligence from Networks to Terminals
**Authors:** Jiedan Tan, Fang Liu, Jingwen Tong, Shengli Zhang, Jun Zhang, Wing Shing Wong  
**Venue:** arXiv

This work proposes WISPA, an LLM-based terminal-side personal agent that separates lightweight online execution from offline reflection to adapt connection choices to user preferences and behavior. The interesting idea is that wireless intelligence may shift from optimizing only the network to optimizing the user’s lived experience at the device edge.

🔗 https://arxiv.org/abs/2606.23255v1

## MIT / Harvard Events This Week

- **June 23** — Summer Seminar Series on Super Pollutants @ MIT Building 55-110  
  🔗 https://calendar.mit.edu/event/summer-seminar-series-on-super-pollutants

- **June 24** — Consciousness & Reality (C&R) Colloquium 2025-26 Series @ MIT Virtual  
  🔗 https://calendar.mit.edu/event/Effects-of-Conscious-Experience-Differ-from-AI

- **June 24** — How to CAD Almost Anything! - Summer 2026 @ MIT Rotch Library, GIS & Data Lab  
  🔗 https://calendar.mit.edu/event/how-to-cad-almost-anything-summer-2026

## Source Notes

- OpenAI’s X feed returned HTTP 503 during collection, so no OpenAI item was included.
- TNT’s event calendar still appeared stale and mostly surfaced February–April listings.
- OneWeb and AST SpaceMobile did not produce stronger fresh items in today’s rotated X pass.
- Harvard event sources were sparse and low-confidence in extraction, so I preferred direct MIT listings over filler.
- arXiv search-page URLs returned 400s during fetch, so I used arXiv recent-category pages and the arXiv API instead.

## Bottom Line

The main signal this morning is that the frontier is getting more operational: satellite links are embedding into transport, telecom automation is broadening across the stack, and AI systems are being engineered for real deployment constraints instead of just benchmark headlines.
