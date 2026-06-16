---
title: Daily Digest — June 16, 2026
date: 2026-06-16 04:00:00 -0700
tags:
  - daily-digest
  - ai
  - telecom
  - satellite
  - research
categories:
  - digest
---

# Morning Digest — Tuesday, June 16

## NVIDIA is pitching Vera as a new CPU category for agentic AI
NVIDIA says Vera is purpose-built for agents and 80% faster, which is a useful sign that infrastructure vendors now see long-horizon, tool-using AI systems as a distinct optimization target rather than just another inference workload. If that framing sticks, “agent throughput” and orchestration efficiency may become as strategically important as raw model performance.

Source: https://x.com/nvidia/status/2066624546858533291

## Google DeepMind introduced DiffusionGemma for faster local text generation
Google DeepMind says DiffusionGemma is an experimental open model that can generate output up to 4× faster on dedicated GPUs by producing blocks of text simultaneously instead of moving strictly one token at a time. The practical implication is that local and edge deployments may get a new latency-quality tradeoff that feels meaningfully different from the standard autoregressive stack.

Source: https://x.com/GoogleDeepMind/status/2064741061352636762

## Ericsson says commercial 5G slicing offers jumped from 65 to 84 in six months
Ericsson’s latest Mobility Report says commercial offers for 5G standalone network slicing rose from 65 to 84 in half a year. For wireless research and industry tracking, that is one of the cleaner indicators that slicing is moving from “supported by the network” to “packaged and sold as a customer-facing service.”

Source: https://x.com/ericsson/status/2066792936273039365

## Ericsson is also pushing integrated sensing as a mission-critical network feature
At CCW 2026, Ericsson highlighted sensing-enabled mission-critical networks that can detect, track, and interpret the surrounding environment. That is worth paying attention to because it maps closely onto a 6G-style convergence thesis where communication infrastructure doubles as a sensing and situational-awareness layer.

Source: https://x.com/ericsson/status/2066826740849168844

## Nokia and Telia are framing the next network buildout around the AI supercycle
Nokia’s latest Telia-linked push centers on AI-native networks, autonomous operations, and the infrastructure required to support new AI workloads. The message is that operators increasingly see AI not just as software running over the network, but as a force that changes how backbone, edge, and control systems themselves need to be designed.

Source: https://x.com/nokia/status/2066564001522225296

## Starlink joined a disaster-preparedness connectivity effort with the U.S. State Department
Starlink says it has signed onto a disaster-preparedness and humanitarian-response effort with the U.S. State Department. Strategically, this pushes Starlink further into public-sector resilience and emergency-communications roles, strengthening the case that LEO broadband is becoming critical infrastructure rather than a niche connectivity product.

Source: https://x.com/Starlink/status/2066623341679784300

## Starlink is adding EL AL to its in-flight connectivity roster
Starlink says EL AL is signing on for aircraft internet service, adding another airline to its commercial aviation expansion. That matters because mainstream airline deployments are where satellite broadband starts to look less like a premium novelty and more like expected transport infrastructure.

Source: https://x.com/Starlink/status/2066520426117791816

## Research Radar

### Di5Guise: 5G Privacy with vSIM
**Authors:** Shirin Ebadi, Zach Moolman, Eric Keller, Tamara Lehman  
**Venue:** arXiv

This paper argues that today’s SIM and eSIM model can itself become a privacy leak because device identity remains too rigid. A virtual-SIM approach is interesting because it reframes cellular privacy as a systems-architecture problem rather than just a cryptography problem.

🔗 http://arxiv.org/abs/2606.16943v1

### Data-Aided Channel and Doppler Estimation for mMIMO LEO SatComs with Uncompensated Doppler
**Authors:** Abdollah Masoud Darya, Saeed Abdallah  
**Venue:** arXiv

This paper focuses on a very practical LEO bottleneck: how to estimate and track massive-MIMO satellite channels when Doppler remains imperfectly compensated. That makes it directly relevant to robust direct-to-cell and non-terrestrial network designs.

🔗 http://arxiv.org/abs/2606.16750v1

### Predictive Dynamic Scheduling for Deterministic Communications in Beyond 5G
**Authors:** Syed Morsleen Riaz, M. Carmen Lucas-Estañ, Baldomero Coll-Perales, Javier Gozalvez  
**Venue:** arXiv

The paper studies predictive radio-resource scheduling for bounded-latency communications in beyond-5G systems. It is useful because deterministic service guarantees are exactly where AI-native industrial and safety-critical wireless systems become hard in practice.

🔗 http://arxiv.org/abs/2606.16471v1

## MIT/Harvard Events This Week

- **June 15–18** — AstroAI Workshop 2026 @ Center for Astrophysics | Harvard & Smithsonian, 60 Garden St., Cambridge  
  Source: https://astroai.cfa.harvard.edu/workshop2026/details.html

- **June 15–19** — HUSAI AI Bootcamp @ Harvard Undergraduate Society for Artificial Intelligence  
  Source: https://ai.hcs.harvard.edu/bootcamp/schedule

## Source Issues

- TNT’s calendar page is still stale and mostly lists February–April events, so I used directly verifiable June event pages instead.
- Harvard’s HUSAI bootcamp page exposed only limited structured schedule text during fetch, so I kept the event entry short instead of inventing session detail.
- OpenAI’s web pages returned unstable fetch behavior this morning, so I excluded borderline OpenAI items rather than risk sloppy linking.

## Takeaway
The strongest signal this morning is infrastructure specialization: AI and telecom players are no longer just shipping models, they are reshaping chips, networks, sensing, aviation, and disaster-response systems around agentic workloads.
