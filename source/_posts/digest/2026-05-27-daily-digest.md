---
title: Daily Digest — May 27, 2026
date: 2026-05-27 04:00:00 -0700
tags:
  - daily-digest
  - ai
  - satellites
  - 6g
  - semiconductors
categories:
  - digest
---

## Morning Digest — Wednesday, May 27

### Telesat is chasing a secure satellite deal with Italy
Reuters reports that Canada’s Telesat held preliminary talks with Italy about encrypted satellite communications for government, diplomatic, and defense use. This is worth watching because it pushes LEO competition beyond consumer broadband and into sovereign communications, where procurement cycles are slower but contracts can be strategically sticky.

Source: [https://www.reuters.com/business/media-telecom/canadas-telesat-eyes-secure-italian-satellite-connectivity-contract-sources-say-2026-05-26/](https://www.reuters.com/business/media-telecom/canadas-telesat-eyes-secure-italian-satellite-connectivity-contract-sources-say-2026-05-26/)

### Europe’s next mobile-satellite spectrum plan may leave room for Starlink and Amazon
A Reuters exclusive says European companies are set to receive most of the future mobile-satellite spectrum allocation, with the rest potentially open to outside players like Starlink and Amazon. The big implication is that non-terrestrial networking is becoming a spectrum-governance story as much as a launch and hardware story.

Source: [https://www.reuters.com/business/aerospace-defense/european-companies-set-receive-two-thirds-future-mobile-satellite-spectrum-rest-2026-05-26/](https://www.reuters.com/business/aerospace-defense/european-companies-set-receive-two-thirds-future-mobile-satellite-spectrum-rest-2026-05-26/)

### SK hynix joined the $1 trillion club after Samsung and Micron
Reuters says SK hynix crossed the $1 trillion market-cap mark, following Samsung and Micron as investors keep rewarding AI-memory winners. That reinforces a useful market truth: AI infrastructure is not only about model labs and GPU vendors anymore; memory suppliers are now central to the bottleneck stack.

Source: [https://www.reuters.com/world/asia-pacific/sk-hynix-market-capitalisation-tops-1-trln-2026-05-27/](https://www.reuters.com/world/asia-pacific/sk-hynix-market-capitalisation-tops-1-trln-2026-05-27/)

### American Airlines is bringing Starlink onboard its flights
Starlink said it will provide in-flight internet for American Airlines, extending LEO connectivity deeper into mainstream passenger infrastructure. Airline Wi-Fi has long been a pain point, so this is one of those mundane-but-important deployments that could shift user expectations if performance holds up.

Source: [https://x.com/Starlink/status/2059292635911819641](https://x.com/Starlink/status/2059292635911819641)

### Starlink-supported buoys streamed live video during Starship’s latest flight test
Starlink said ocean buoys in the Indian Ocean delivered real-time video streaming during Starship’s twelfth flight test. The interesting part is not just the space spectacle, but the operational proof that LEO links can support hard-to-wire telemetry setups in remote marine environments.

Source: [https://x.com/Starlink/status/2059391182094880785](https://x.com/Starlink/status/2059391182094880785)

### NVIDIA is pushing fresh Vera CPU benchmark claims for agentic AI workloads
NVIDIA highlighted new Phoronix benchmark results for its Vera CPU, claiming major gains in overall performance, Linux kernel compilation, and memory bandwidth for AI-factory workloads. Even though Vera is not brand-new news, the updated benchmark push shows how NVIDIA is framing agentic AI as a full-system compute problem rather than a pure GPU story.

Source: [https://x.com/nvidia/status/2059387019109826953](https://x.com/nvidia/status/2059387019109826953)

### Google DeepMind spotlighted Gemini Embedding 2 as its multimodal retrieval layer
Google DeepMind is continuing to push Gemini Embedding 2, its multimodal embedding model for retrieval, classification, clustering, and recommendations across text, images, video, audio, and documents. This matters because better embeddings quietly improve the grounding layer that powers search, RAG, and agent memory in production systems.

Source: [https://deepmind.google/models/gemini/embedding/](https://deepmind.google/models/gemini/embedding/)

## Research Radar

### GENESIS: Harnessing AI Agents for Autonomous 6G RAN Synthesis, Research, and Testing
**Authors:** Tamerlan Aghayev, Maxime Elkael, Michele Polese, Minh Dat Nguyen, Gabriele Gemmi, Andrea Lacava, Ali Saeizadeh, Reshma Prasad, Paolo Testolina, Angelo Feraudo, Soumendra Nanda, Pedram Johari, Salvatore D'Oro, Tommaso Melodia  
**Venue:** arXiv

GENESIS proposes an agentic framework for cellular R&D that converts intents such as standards clauses, telemetry anomalies, and research hypotheses into over-the-air validated solutions. For Dad’s lane, the key idea is compounding RAN experimentation through reusable skills and a persistent knowledge layer instead of one-off manual engineering loops.

Source: [https://arxiv.org/abs/2605.27360](https://arxiv.org/abs/2605.27360)

### On the LEO Satellite Constellation Design for North Atlantic Coverage
**Authors:** Alejandro Ramírez-Arroyo, Miguel Villanueva-Fernández, Preben Mogensen  
**Venue:** arXiv

This paper studies how inclination, minimum elevation angle, altitude, and footprint affect visibility probability, revisit time, path loss, and coverage continuity for North Atlantic service. It is especially relevant for maritime, aviation, and Arctic scenarios where generic global-coverage assumptions are too coarse.

Source: [https://arxiv.org/abs/2605.26943](https://arxiv.org/abs/2605.26943)

### OpenTwin: Digital Twin Driven Closed Loop KPM Inference and Control for Open RAN
**Authors:** Md Sharif Hossen, Zifan Zhang, Dara Ron, Yuchen Liu, Vijay K. Shah  
**Venue:** arXiv

OpenTwin builds an O-RAN digital twin that learns live network behavior, corrects deviations against real measurements, and validates control policies before applying them to physical infrastructure. Reported fidelity up to 96% makes this a practical digital-twin paper rather than a vague architectural sketch.

Source: [https://arxiv.org/abs/2605.24662](https://arxiv.org/abs/2605.24662)

## MIT/Harvard Events This Week

- **Thu, May 28** — Gen AI and Its Impact on the World: Step into the Future of Innovation @ Harvard University  
  Source: [https://careerservices.fas.harvard.edu/events/2026/05/28/gen-ai-and-its-impact-on-the-world-step-into-the-future-of-innovation/](https://careerservices.fas.harvard.edu/events/2026/05/28/gen-ai-and-its-impact-on-the-world-step-into-the-future-of-innovation/)

- **Mon, June 1** — Claude Code: Putting it all together to develop course content and communicate research @ Harvard Bok Center, 50 Church Street  
  Source: [https://bokcenter.harvard.edu/generative-ai-events](https://bokcenter.harvard.edu/generative-ai-events)

- **Wed, June 3** — Intro to MIT’s AI Tools @ MIT Building NE49, 405  
  Source: [https://calendar.mit.edu/event/intro-to-mits-ai-tools](https://calendar.mit.edu/event/intro-to-mits-ai-tools)

## Source Issues

- TNT’s calendar page still appears stale and mostly shows February–April listings, so event picks were cross-checked on direct Harvard/MIT pages.
- arXiv API requests returned 429 errors this morning, so paper discovery fell back to arXiv recent-list pages and abstract pages.
- OpenAI and AST SpaceMobile did not yield fresh usable items in the rotated X pass, and Next G Alliance’s feed appeared stale.

## Takeaway

The frontier keeps looking more infrastructural: satellite spectrum, sovereign communications, AI memory hardware, multimodal retrieval, and digital-twin control loops are all becoming more strategically important than one more flashy model demo.
