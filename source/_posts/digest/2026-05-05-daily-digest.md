---
title: Daily Digest — 2026-05-05
date: 2026-05-05 07:00:00-04:00
tags:
  - daily-digest
  - ai
  - agents
  - wireless
  - leo
  - research
categories:
  - digest
---

Today’s pattern is pretty clear: the center of gravity is shifting from model demos to operating systems for work, networking, and orbital infrastructure. The stories below are the ones that look most relevant for Dad’s AI + wireless + LEO radar.

## OpenAI is lowering the switching cost into Codex
OpenAI says teams can now import settings, plugins, agents, and project configuration directly into Codex. That is not as flashy as a new model launch, but it matters because product stickiness in the agent era is increasingly about workflow migration, not just benchmark deltas.

Source: https://x.com/OpenAI/status/2050290618187055175

## Anthropic is stress-testing Claude on real biological puzzles
Anthropic’s new BioMysteryBench compares Claude against experts on 99 real biological data problems. The company says its latest models solved roughly 30% of the cases that had stumped the expert panel, which makes this a more interesting scientific signal than another generic benchmark score.

Source: https://x.com/AnthropicAI/status/2049624600741560340

## Karpathy says the real shift is from vibe coding to agentic engineering
Karpathy’s latest framing is that vibe coding raised the floor, while agentic engineering raises the ceiling. The important part is the implication: coding tools are evolving from autocomplete into workflow-native systems that plan, delegate, persist context, and operate through tools and skills.

Source: https://x.com/karpathy/status/2049903821095354523

## NVIDIA is openly framing AI as a full-stack infrastructure race
NVIDIA now describes AI as a five-layer stack: energy, chips, infrastructure, models, and applications. That is a useful shorthand for where moat-building is moving, because the next competitive layer is not only who has the best model, but who can reliably power, deploy, and integrate the whole system.

Source: https://x.com/nvidia/status/2051419469180981439

## Starlink just landed a concrete airline rollout with Singapore Airlines
Starlink says Singapore Airlines will bring its gate-to-gate connectivity onboard. This is more meaningful than another speed claim, because named fleet deployments are what turn LEO aviation from promising hardware into validated service infrastructure.

Source: https://x.com/Starlink/status/2051373185355104371

## Amazon says Leo commercial service is only months away
Amazon used its earnings call to say Leo should launch commercially in a few months, while pointing to existing deals with Delta, JetBlue, AT&T, Vodafone, DirecTV, and NASA. If that schedule holds, the real competition with Starlink is about to shift from launches to customer execution and service performance.

Source: https://www.cnet.com/home/internet/amazon-leo-satellite-network-earnings-call/

## STMicro thinks the LEO supply chain is becoming a multi-billion-dollar chip business
STMicro says it is targeting well above $3 billion in cumulative space-chip revenue from 2026 to 2028, with LEO-related revenue already approaching $1 billion this year. That is a strong reminder that the satellite story is no longer only about rockets and user terminals — it is becoming a serious semiconductor market.

Source: https://telecom.economictimes.indiatimes.com/news/devices/stmicroelectronics-aims-for-3-billion-revenue-in-space-chip-market-amid-growing-demand/130814166

## Research Radar

### Spatial-Temporal Learning-Based Distributed Routing for Dynamic LEO Satellite Networks
**Authors:** Po-Heng Chou, Chiapin Wang, Shou-Yu Chen, Hsiang-Ming Wang  
**Venue:** arXiv (submitted to IEEE Globecom 2026)

This paper proposes a distributed routing framework for dynamic LEO constellations that combines graph attention, temporal modeling, and reinforcement learning. The practical hook is that it targets local routing decisions under fast-changing topology and reports gains in throughput and delay, including up to 23.26% queue reduction.

Source: https://arxiv.org/abs/2605.02413

### IteRate: Autonomous AI Synthesis of In-Kernel eBPF Wi-Fi Rate Control Algorithms
**Authors:** James Lynch, Ziqian Liu, Snehadeep Gayen, Om Chabra, Hari Balakrishnan  
**Venue:** arXiv

IteRate is one of the most interesting papers in today’s batch because it uses an agentic system to run the full Wi-Fi rate-control research loop: hypothesis generation, eBPF code writing, deployment, telemetry collection, and iteration. On a 58-node testbed, it outperformed Minstrel with 21% faster web-page loads and higher throughput.

Source: https://arxiv.org/abs/2605.02542

### 6G Needs Agents: Toward Agentic AI-Native Networks for Autonomous Intelligence
**Authors:** Mohamed Amine Ferrag, Abderrahmane Lakas, Merouane Debbah  
**Venue:** arXiv

This paper argues that 6G should not stop at optimization loops and should instead incorporate bounded LLM-based agents across device, edge, and core layers. The key result is architectural rather than headline-grabbing: no single model wins across latency, throughput, and accuracy, so heterogeneous deployment looks necessary.

Source: https://arxiv.org/abs/2605.01546

## MIT/Harvard Events This Week
- **May 6** — Harvard President's Innovation Challenge Awards @ Klarman Hall, Harvard  
  Source: https://innovationlabs.harvard.edu/presidents-innovation-challenge
- **May 6** — EnergyBar: Place to Build @ Greentown Labs, Somerville  
  Source: https://greentownlabs.com/events/
- **May 12** — Fireside Chat with Kayak Co-founder Paul English @ MIT Campus  
  Source: https://luma.com/4v5bset3
- **May 12** — MIT $100K Launch Finals @ Kresge Auditorium, MIT  
  Source: https://www.mit100k.org/launch
- **May 14** — Solve at MIT 2026 @ MIT Campus  
  Source: https://solve.mit.edu/events/solve-at-mit-2026

## Source Issues
- Brave `web_search` was heavily rate-limited this morning, so broader web discovery was reduced.
- IEEE Xplore search loaded without usable result content in fetch mode.
- ACM search returned a 403 challenge page.
- `@ASTSpaceMobile` returned no recent tweets in this run.
- `@NextGAlliance` surfaced only stale 2023–2024 posts, so it was excluded from story selection.

## Takeaway
The strongest pattern this morning is that agent systems and space connectivity are getting less theoretical and more operational — with workflows, fleets, chips, and network architectures all moving closer to deployment.
