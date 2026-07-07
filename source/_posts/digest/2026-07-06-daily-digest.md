---
title: Daily Digest — Monday, July 6, 2026
date: 2026-07-06 08:00:00
tags:
  - daily-digest
  - ai
  - wireless
  - leo
  - research
categories:
  - Digest
---

# Daily Digest — Monday, July 6, 2026

## Apptronik expands Robot Park and tightens its Gemini Robotics loop
Apptronik announced an expanded Robot Park in Austin and positioned Apollo 2 as the data-collection workhorse for a broader continuous-learning system. The key point is that fleets of humanoid robots are now being used to generate real-world training data at scale, not just to stage demos.

As part of Apptronik’s research partnership with Google DeepMind, data from Apollo 2 deployments helps train Gemini Robotics. That makes this one of the clearest recent examples of a robotics company building an industrialized feedback loop between physical deployments and foundation-model improvement.

Source: https://apptronik.com/news-collection/welcome-to-robot-park-where-apptroniks-apollo-goes-to-work

## Amazon Leo passes 375 satellites in orbit
Amazon’s latest Leo mission update says the network now has more than 375 satellites in orbit after successive Atlas V and Ariane 6 launches. That doesn’t put it near Starlink scale, but it does show that Amazon’s LEO effort is now accumulating real orbital mass instead of remaining an early-stage launch story.

For wireless and satellite-watchers, the significance is competitive pressure: a second deep-pocketed broadband constellation is building cadence, launch diversity, and deployment muscle.

Source: https://www.aboutamazon.com/news/innovation-at-amazon/project-kuiper-satellite-rocket-launch-progress-updates

## Emirates hits one million Starlink Wi-Fi connections
Emirates says customers have already made more than one million Starlink Wi-Fi connections since rollout began seven months ago. The airline also says it now operates more than 60 Starlink-equipped flights per day and has already seen more than a petabyte of customer usage.

That matters because it suggests inflight satellite internet is crossing from novelty into expected infrastructure, especially when a major global carrier can show rapid adoption at fleet scale.

Source: https://www.emirates.com/media-centre/one-million-connections-and-counting-emirates-customers-embrace-starlink-wi-fi/

## Anthropic launches Claude Science for reproducible research workflows
Anthropic released Claude Science in beta for Pro, Max, Team, and Enterprise users. The product is designed to generate scientific artifacts such as figures and manuscripts alongside the code and environment that produced them, while also handling compute across laptops, clusters, and on-demand GPUs.

The interesting part for researchers is not just convenience but auditability. Anthropic is clearly aiming at a workflow where AI-generated scientific work stays inspectable and reproducible instead of becoming a black-box assistant.

Source: https://www.anthropic.com/news/claude-science-ai-workbench

## Ericsson pushes AI into the radio access network itself
Ericsson introduced AI in RAN, a software subscription that brings telco-grade AI models directly into basebands and radios. The company says the system is already proven in more than 15 deployments and trials, with gains in throughput, spectral efficiency, user density handling, and positioning precision.

For Dad’s research lane, this is one of the more concrete signs that AI-native RAN is maturing from concept into deployable software that works within existing 5G Advanced hardware and Cloud RAN environments.

Source: https://www.ericsson.com/en/news/2026/6/the-ran-gets-smarter-ericsson-puts-ai-where-it-matters

## GitHub sets a final shutdown date for GitHub Models
GitHub says GitHub Models will be fully retired on July 30, 2026. Before that, scheduled brownouts on July 16 and July 23 will temporarily break requests to help users prepare for shutdown.

This is worth watching because it reflects a broader platform trend: instead of supporting multiple overlapping AI surfaces, developer platforms are consolidating around narrower default experiences such as Copilot and partner ecosystems.

Source: https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/

## NVIDIA claims strong ICML 2026 research footprint for Nemotron and GPUs
In a July 6 post, NVIDIA said 145 accepted ICML 2026 papers cite Nemotron models and datasets, and around 2,000 accepted papers cite NVIDIA GPUs. Even if the framing is self-promotional, the post is a notable signal that NVIDIA is pushing hard to make its open-model stack visible in mainstream academic research.

That matters because AI infrastructure leadership is increasingly being contested not just on chips, but on the surrounding software, models, datasets, and research mindshare.

Source: https://x.com/nvidia/status/2074161704456356216

## Research Radar

### Ultra-Low-Cost Hybrid Beamforming: A New Static-Connection Architecture with Sparse Phase-Shifter Sharing
**Authors:** Honghao Wang, Qingqing Wu, Yifei Wu, Yuxuan Chen, Wen Chen, Derrick Wing Kwan Ng  
**Venue:** arXiv  
This paper proposes a hybrid-beamforming architecture that reduces phase-shifter count while preserving most of the beamforming capability of conventional sub-connected designs. It looks practically relevant because it focuses on hardware-efficiency tradeoffs rather than only idealized performance.

Source: https://arxiv.org/abs/2607.02393v1

### Three-Dimensional Spatial Correlation Modeling for Cylindrical mMIMO Arrays in HAPS
**Authors:** Shasha Liu, Abla Kammoun, Mohamed-Slim Alouini  
**Venue:** arXiv  
This work derives a closed-form spatial-correlation function for cylindrical massive-MIMO arrays on high-altitude platform stations. That makes it useful for future non-terrestrial network modeling where cylindrical geometries are more realistic than the planar assumptions used in many terrestrial studies.

Source: https://arxiv.org/abs/2607.02111v1

### Robust Transmission Design for RIS-Assisted RSMA-SWIPT Systems With Movable Antennas Under Hardware Distortions
**Authors:** Muhammad Asif, Asim Ihsan, Irfan Muhammad, Mohd Hamza Naim Shaikh, Syed Tariq Shah, Zhu Shoujin, Symeon Chatzinotas  
**Venue:** arXiv  
This paper tackles a hard joint optimization problem involving movable antennas, RIS configuration, power splitting, and hardware impairments. It is dense, but it sits squarely in the broader trend of increasingly adaptive and software-defined wireless architectures.

Source: https://arxiv.org/abs/2607.02384v1

## MIT/Harvard Events This Week
- **July 7** — LL Technology Office Seminar: From Concept to Mission Impact @ MIT Virtual  
  Source: https://calendar.mit.edu/event/ll-technology-office-seminar-engine-for-change
- **July 7** — Founder Talk: Allison Byers of Scroobious @ Harvard Innovation Labs  
  Source: https://innovationlabs.harvard.edu/events/founder-talk-allison-byers-of-scroobious-author-of-fundraising-for-the-rest-of-us
- **July 8** — Venture Incubation Program Advancement Ceremony @ Harvard Innovation Labs  
  Source: https://innovationlabs.harvard.edu/events/venture-incubation-program-advancement-ceremony
- **July 9** — Virtual Founder Circle @ Online  
  Source: https://innovationlabs.harvard.edu/events/virtual-founder-circle

## Source Issues
- TNT’s event calendar was still stale and largely surfaced February–April listings, so current MIT and Harvard event pages were used instead.
- AST SpaceMobile and OneWeb did not yield usable fresh posts during this run.
- arXiv API requests began rate-limiting mid-run, so the paper shortlist was assembled from successfully fetched fresh results.

## Takeaway
The clearest through-line today is that advanced tech systems are becoming operational systems: humanoid robots are collecting production data, satellite networks are proving real adoption at scale, telecom AI is moving into the RAN, and research assistants are being built around reproducibility instead of novelty alone.
