---
title: "Morning Digest — November 13, 2026"
date: 2026-11-13 07:00:00
categories: [Digest, Technology]
tags: [AI, NVIDIA, OpenAI, Google, 5G, LEO, Direct-to-Device, 6G, Wi-Fi]
---

Leadership upheaval and legal pressure are colliding with faster work models and increasingly concrete 5G, Wi-Fi, and satellite deployments.

<!-- more -->

## NVIDIA begins its first CEO search after Jensen Huang resigns

NVIDIA founder Jensen Huang resigned as president, CEO, and a member of the board effective immediately after leading the company for 33 years. The board appointed longtime executive vice president and CFO Colette Kress as interim CEO while it searches for a permanent successor among internal and external candidates.

Harvey C. Jones becomes NVIDIA’s first-ever board chair. The company says its operations, customer commitments, and technology roadmap will continue without interruption, with fiscal third-quarter results still scheduled for November 17. The transition is consequential well beyond NVIDIA: Huang shaped the modern accelerated-computing market and turned CUDA and GPUs into the core infrastructure of the AI boom.

Source: [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-announces-ceo-transition)

## Google launches Gemini 4 Hydrogen for fast agentic work

Google introduced Gemini 4 Hydrogen as its high-efficiency execution model for coding, multimodal synthesis, and everyday agent workflows. It is available through Google AI Studio, the Gemini API, Gemini for business, the Gemini app, Search, and paid Antigravity plans, with a one-million-token context window and pricing of $1.50 per million input tokens and $7.50 per million output tokens.

At its default high reasoning setting, Google says Hydrogen finishes tasks 2.5 times faster than Gemini 3.8 Flash while more than tripling its Terminal-Bench 4.1 score. A new Antigravity Orchestrator can switch dynamically between Carbon for deep judgment and Hydrogen for execution; in Google’s test it approached Carbon’s success rate while using 24% less quota and finishing 19% faster.

Source: [Google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/)

## OpenAI expands GPT-6 Astra across professional workflows

OpenAI has made GPT-6 Astra available in ChatGPT Work, Codex, and the API for complex professional tasks spanning computer use, browsing, coding, cybersecurity, science, and document production. Pricing starts at $10 per million input tokens and $50 per million output tokens, with enterprise access disabled by default until administrators enable it.

The deployment pairs stronger tool use with explicit safety controls. OpenAI reports that Astra produced unintended outcomes 89% less often than GPT-5.6 Sol and 74.7% less often than Claude Fable 5.1 on an internal computer-use benchmark. Administrators can restrict approved sites and applications, control transfers and browsing history, and require confirmation before consequential actions.

Source: [OpenAI](https://openai.com/index/gpt-6-astra-next-generation-work/)

## Equatys clears the regulatory gate for a 2,800-satellite D2D constellation

Space42 says Equatys, its direct-to-device joint venture with Viasat, has cleared the regulatory approval that had blocked further progress. The partners can now move toward contracting a prime contractor for a proposed constellation of as many as 2,800 low-Earth-orbit satellites.

Equatys aims to provide a shared space-and-ground infrastructure layer for direct-to-device and advanced mobile-satellite connectivity. The approval does not put spacecraft in orbit, but it advances another major competitor from corporate formation toward system procurement in a market increasingly shaped by Starlink, AST SpaceMobile, and sovereign connectivity requirements.

Source: [Space Intel Report](https://www.spaceintelreport.com/space-42-regulatory-ok-for-equatys-d2d-jv-with-viasat-is-now-in-hand-we-can-now-proceed-with-constellation-development/)

## India-developed 5G radio moves from research to commercial orders

WiSig Networks has opened commercial orders for a Made-in-India 5G radio developed from wireless research led by Professor Kiran Kuchi at IIT Hyderabad and supported by the IIITB COMET Foundation. The multi-antenna system is designed to improve network capacity, coverage, and performance, with bulk deliveries expected in 2027.

The project is a notable research-to-product transfer: WiSig licensed publicly supported technology, demonstrated the radio at Mobile World Congress in March, and opened orders after an India Mobile Congress showcase. If production scales, it could reduce operator dependence on imported radio-access equipment while broadening the supplier base for 5G and 5G-Advanced deployments.

Source: [ETTelecom](https://telecom.economictimes.indiatimes.com/news/telecom-equipment/wisig-networks-opens-commercial-orders-for-made-in-india-5g-radio/135786262)

## Nonprofits sue five AI developers seeking a frontier-model freeze

Irreplaceable Education Fund, Public Citizen, Heat Initiative, and The Alliance for Secure AI filed suit in San Francisco Superior Court against Anthropic, Google, Meta, OpenAI, and SpaceXSI. The plaintiffs want the court to freeze development of increasingly advanced systems they argue could escape human control or facilitate catastrophic cyberattacks and biological threats.

The complaint invokes California’s Unfair Competition Law and asks a court to intervene before a mass-casualty event occurs. The case is an aggressive attempt to convert AI safety claims into a judicially enforceable development limit; whether it survives procedural and evidentiary challenges will matter as much as its immediate publicity.

Source: [Public Citizen](https://www.citizen.org/news/coalition-of-nonprofits-files-landmark-lawsuit-to-stop-development-of-advanced-ai-systems-at-anthropic-google-meta-openai-and-spacexsi-that-proliferate-bioweapons-and-cyberattacks/)

## Research Radar

### Topology-Aware Handover Management for Service Continuity in LEO Satellite Networks

Jui-Che Han, Nasir Khan, Siva Satya Sri Ganesh Seeram, and Cicek Cavdar propose a proximal-policy-optimization controller that decides when a user should hand over and which satellite should take over. Unlike signal-only methods, the policy considers received power, satellite-to-ground-station associations, remaining visibility time, and elevation angles.

The simulated policy achieved 99.32% service availability at a 40-degree minimum elevation angle, exceeding optimized handover-margin/time-to-trigger and least-delay baselines by 1.67 and 1.41 percentage points. Availability stayed above 97.52% even when the minimum elevation increased to 55 degrees.

Source: [arXiv:2611.16878](https://arxiv.org/abs/2611.16878)

### Empowering AI towards 6G: Realistic UAV Channel Data Acquisition using Open-Source Solutions

Qiuheng Zhou, Sergiy Melnyk, Hans D. Schotten, Robert Vilter, and Nick Stuckert present an open-source UAV-to-ground measurement platform built with OpenAirInterface and commodity software-defined radios. It records raw sub-6-GHz channel-state information synchronized with flight telemetry, creating hardware-inclusive data for AI-native non-terrestrial-network research.

Flight experiments show that dominant spectral ridges can depart sharply from theoretical kinematic Doppler trajectories unless guided tracking is used. That finding warns against training aerial-network models only on idealized channels. The paper is linked to IEEE VTC 2026-Spring.

Source: [arXiv:2611.16644](https://arxiv.org/abs/2611.16644)

### Machine Learning for Scalable Multi-AP Coordination in IEEE 802.11bn Networks

Maksymilian Wojnar and Szymon Szott tackle the hard scheduling problem introduced by IEEE 802.11bn multi-access-point coordination: selecting which nearby access points should transmit together and how they should be configured. Their stack progresses from hierarchical multi-armed bandits to a generative pipeline combining graph neural networks and flow matching.

Simulation and hardware-testbed results show higher throughput than legacy random access while scaling coordination to dozens of access points, beyond the practical reach of analytical and search-based methods. The work appears in MSWiM 2026.

Source: [arXiv:2611.16634](https://arxiv.org/abs/2611.16634)

## Source Notes

An Investing.com mirror of a Reuters report returned HTTP 403, so the related TSMC investment story was omitted rather than summarized from an inaccessible source. IEEE Xplore and the ACM Digital Library returned no newly indexed matching papers; Research Radar therefore uses verified arXiv records, including two conference-linked papers.

## Takeaway

Leadership upheaval and legal pressure are colliding with faster work models and increasingly concrete 5G, Wi-Fi, and satellite deployments.
