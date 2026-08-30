---
title: Morning Digest - Sunday, August 30, 2026
date: 2026-08-30 04:00:00
tags:
  - AI
  - 6G
  - LEO
  - NVIDIA
  - Research
categories:
  - digest
---

## NVIDIA says Vera Rubin delivers 30× more agent throughput per megawatt

NVIDIA says Vera Rubin NVL72 achieved up to 30 times the throughput per megawatt of the GB300 NVL72 on SemiAnalysis's AgentX workload. AgentX is designed to represent the bursty inference, tool use, and long-running execution patterns of coding agents, making the result more operationally relevant than a conventional token-throughput headline. The vendor-reported comparison still needs independent replication, but it frames the next AI-factory contest clearly: electrical efficiency and useful workload throughput will matter as much as peak accelerator specifications.

Source: https://x.com/nvidia/status/2093722690049695780

## Starlink offers emergency connectivity after Nepal floods

Starlink says it is ready to send terminals and provide free service to Nepal's government and humanitarian organizations as soon as authorities permit deployment. Severe flooding in Nepal and the Tibet border region damaged roads, bridges, and cellular networks, conditions where a self-contained satellite terminal can restore coordination without waiting for terrestrial backhaul repairs. The announcement is also a practical reminder that LEO broadband's resilience value depends on pre-positioned hardware, power, regulatory clearance, and local response partners—not orbital capacity alone.

Source: https://x.com/Starlink/status/2093756028752134449

## Qualcomm unifies edge-AI and multimedia development

Qualcomm introduced Intelligent Multimedia SDK 2.0, describing it as a unified toolkit for edge-AI and multimedia applications on Dragonwing platforms. The SDK is intended to connect on-device inference with camera, audio, video, and heterogeneous compute pipelines without requiring developers to assemble each layer independently. Alongside Qualcomm's recent push into robotics and developer boards, the release suggests that competition in edge AI is shifting from TOPS figures toward the software paths that turn accelerators into deployable physical-AI systems.

Source: https://x.com/Qualcomm/status/2093488870411153434

## Google DeepMind pilots cryptographically double-blind model evaluations

Google DeepMind is working with Singapore's AI Safety Institute, OpenMined, AVERI, and MLCommons on a double-blind evaluation of a proprietary Gemini Flash Lite model. Confidential test sets remain inside a privacy-preserving environment so the model developer cannot inspect them or optimize against them, while evaluators do not need access to model weights. The project targets benchmark contamination—a growing trust problem when test questions can leak into training data or evaluation-driven tuning—and adds technical safeguards to the contractual controls traditionally used for external testing.

Source: https://deepmind.google/blog/piloting-the-worlds-first-double-blind-ai-evaluations/

## SK Telecom spins out a $2.2B-backed AI infrastructure company

SK Telecom plans to split SK Broadband's data-center and submarine-cable operations into a new company called SK Horizon. KKR and an IMM Investment-Stonebridge consortium will provide KRW 3.08 trillion in combined equity, taking 29% and 20% stakes respectively while SK Telecom retains 51% and management control. SK Horizon will oversee eight operating data centers, new facilities, cable expansion, and a planned 318 MW capacity footprint; sister company SK Hyper will focus on projects targeting 5 GW from 2029 and as much as 15 GW by 2035. This is telecom infrastructure being reorganized explicitly around the capital intensity of AI compute.

Source: https://www.prnewswire.com/news-releases/sk-telecom-launches-ai-data-center-infrastructure-company-sk-horizon-and-secures-investments-from-kkr-and-imm-302861694.html

## Omdia forecasts satellite IoT connections near 198 million by 2035

Omdia projects satellite IoT connections will grow from 7.7 million in 2023 to 197.7 million by 2035, equivalent to a 31% compound annual rate. LEO links are forecast to expand much faster—88.6% annually—as launches accelerate, bandwidth grows, and connectivity prices decline. Automotive use is the standout forecast, rising from 11,000 satellite-connected vehicles in 2023 to more than 112 million by 2035 as manufacturers pursue systems that roam between terrestrial and non-terrestrial networks. The numbers are forecasts rather than deployments, but they identify seamless NTN integration as the commercial center of gravity.

Source: https://cyprus-mail.com/2026/08/28/leo-satellites-set-to-drive-explosive-growth-in-iot-connections

## Australia's NBN details its Amazon LEO migration timeline

Australia's National Broadband Network says Sky Muster customers will begin moving from geostationary satellites to an Amazon LEO service around mid-2027, roughly a year later than the launch timing discussed when the agreement was announced. The customer transition could then take 18 months to two years while the existing satellites remain in service. About 60,000 current Sky Muster users are expected to migrate, making the program a consequential national-scale test of commercial LEO capacity, customer equipment logistics, and service continuity for remote broadband.

Source: https://www.farmonline.com.au/story/9339029/amazon-leo-nbn-customers-to-gain-lower-latency-new-speeds/

## Research Radar

### FaulT-Bench: Towards Benchmarking Network Troubleshooting LLM Agents under Unreliable User Tickets

Kuan-Hao Tseng, Niruth Bogahawatta, Yasod Ginige, Kunjan Patel, Kosta Dakic, and Suranga Seneviratne, arXiv. FaulT-Bench contains 200 troubleshooting scenarios across eight emulated network topologies, including real faults, false reports, incorrect device attribution, and wrong root-cause claims. SADE, ReAct, and Claude Code perform strongly when tickets are accurate but degrade when a healthy network is paired with a false report, often turning benign observations into invented root causes. The benchmark exposes a critical gap for autonomous network operations: knowing when not to diagnose a fault.

Source: https://arxiv.org/abs/2608.27021

### Radio Imaging and Resource Allocation in Frugal Multistatic D-MIMO ISAC Systems

Sauradeep Dey, Musa Furkan Keskin, Dario Tagliaferri, Gonzalo Seco-Granados, and Henk Wymeersch, arXiv. The paper proposes a distributed-MIMO ISAC system that assigns orthogonal subcarriers to communications and sensing, eliminating interference between the two functions. A long-timescale optimizer selects access-point roles and subcarrier assignments, while a short-timescale controller adjusts power splitting to protect spectral efficiency. The communication-centric design improves the imaging-communications tradeoff compared with superposition and identifies when coherent versus non-coherent imaging is preferable.

Source: https://arxiv.org/abs/2608.27041

### Over-The-Air Extreme Learning Machines with Nonlinear Stacked Intelligent Metasurfaces

Kyriakos Stylianopoulos, Mattia Fabiani, Giulia Torcolacci, Davide Dardari, and George C. Alexandropoulos, IEEE SPAWC 2026 / arXiv. The proposed XL-MIMO receiver uses a nonlinear front metasurface as an activation function and tunable downstream metasurfaces to approximate trained network weights directly in the wave domain. Terminating the stack in a single RF chain reduces hardware complexity, while simulations show classification accuracy close to idealized digital models. The work is an unusually literal form of over-the-air learning: the propagation and metasurface hardware execute part of the model.

Source: https://arxiv.org/abs/2608.27137

## Source Issues

- IEEE and ACM searches returned no stronger fresh wireless papers; Research Radar uses new arXiv records, including one accepted for IEEE SPAWC 2026.
- General web search was sparse for the weekend window; official company posts and primary announcements were preferred where available.

## Takeaway

The common thread is infrastructure efficiency—more useful AI work per watt, resilient connectivity beyond terrestrial coverage, and tighter integration between compute, networks, and evaluation.
