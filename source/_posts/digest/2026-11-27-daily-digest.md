---
title: "Morning Digest — November 27, 2026"
date: 2026-11-27 07:00:00
tags:
  - 6G
  - LEO satellites
  - 5G
  - AI agents
  - NVIDIA
categories:
  - Daily Digest
---

Today’s strongest signal is convergence: terrestrial and non-terrestrial networks are being planned as one infrastructure layer, while AI systems are moving from individual assistants toward verified production migrations and thousand-agent swarms.

## China puts 6G and a national LEO network on its 2030 roadmap

China released an implementation plan for next-generation communications that targets broad coverage and leading performance by 2030. It calls for advancing 6G at an appropriate time, substantially completing a low-Earth-orbit satellite internet system, and coordinating mobile, fiber, computing, space-based, industrial, and vehicle networks.

The roadmap also emphasizes 6G and satellite standards, communications-compute integration, private-sector participation, and access to spectrum and other deployment resources. That makes it more than a radio roadmap: it is a national infrastructure program spanning terrestrial and orbital connectivity.

Source: [Xinhua](https://english.news.cn/20261126/de6010998cbb49f2a06fa8c715603441/c.html)

## Europe opens a 500-satellite-per-year megafactory

Aerospacelab inaugurated a 20,000-square-meter factory in Marcinelle, Belgium, designed to produce as many as 500 satellites annually. The company holds a €2.4 billion contract to manufacture 264 of the 348 satellites planned for IRIS², the EU’s sovereign secure-connectivity constellation.

Employees are expected to move into the facility in January, with production slated to begin by the end of 2028 and initial IRIS² launches targeted for late 2029. The capacity is strategically important, though the schedule also shows how far Europe remains from Starlink’s present scale.

Source: [CNBC](https://www.cnbc.com/2026/11/26/starlink-satellites-aerospacelab-factory-belgium.html)

## Elisa and Drei launch Europe’s first commercial 5G SA roaming link

Finland’s Elisa and Austria’s Drei moved standalone 5G roaming from technical trials into commercial consumer and enterprise traffic. The cross-border connection uses BICS’ 5G SA hubbing platform, avoiding the need for every operator pair to build a dedicated interface.

Commercial SA roaming matters because the 5G core—not only the radio icon—enables lower latency, more flexible enterprise services, and future IoT capabilities across national boundaries.

Source: [Elisa corporate release via 6ix](https://6ix.com/news/elisa-oyj-and-drei-launch-europes-first-commercial-5g-sa-roaming-connection-supported-by-bics-5g-sa-hubbing-platform)

## Ericsson brings a signature 6G sensing capability onto 5G-Advanced

Ericsson is developing integrated sensing and communication on current public and private 5G infrastructure rather than waiting for commercial 6G. Trials with AT&T, Finland’s Erillisverkot, Poland’s Play, and planned Verizon lab work explore how cellular networks can complement radar, optical, acoustic, and RF sensors—especially for low-flying drone detection.

The strategy is partly a response to the slow 5G standalone transition: vendors want new 6G capabilities to mature on 5G-Advanced so they are deployable when the next standard arrives, not years afterward.

Source: [RCR Wireless News](https://rcrwireless.com/20261126/6g/isac-and-the-5g-version-of-the-6g-trick-to-make-networks-see)

## Anthropic ports its highest-traffic API from Python to Rust with Claude agents

Anthropic migrated the Messages API—the primary route used by customers, Claude Code, and Cowork—from Python to Rust after traffic grew roughly 1,800-fold from early 2024 to fall 2026. Claude generated the first core request path in about a week, but verification took much longer.

The team shadowed production traffic, used the Python service as an oracle, and dispatched agents to investigate behavioral mismatches without exposing customer requests. The deployed Rust service uses about 70% less CPU per request and cuts median time to first token by about 20%, illustrating that verification rather than code generation is becoming the bottleneck in AI-assisted rewrites.

Source: [Anthropic](https://www.anthropic.com/research/migrating-api-to-rust)

## Hugging Face scales an open agent swarm to 1,000 workers

Hugging Face grew a swarm of 1,000 DeepSeek agents over nine days and tasked it with building PyBot, a helpful chatbot written in pure Python without learned weights. The swarm exchanged 175,000 messages and merged more than 8,500 pull requests, ultimately matching SmolLM-360M on everyday conversations in the team’s evaluation.

The project is valuable as an engineering field report, not merely a scale demo. Hugging Face open-sourced Legion for spawning agents across local, cluster, and hosted infrastructure, plus Msgboard for threaded coordination and shared documents. The report also details bottlenecks in Git, coordination, evaluation, and duplicated work.

Source: [Hugging Face Swarms](https://huggingfaceswarms-scaling-swarms.hf.space/)

## New U.S. remote-access rules send Nvidia GPU sellers hunting for buyers

New Commerce Department controls aimed at preventing China-linked customers from renting advanced AI compute in third-country data centers took effect November 19. Market participants told CNBC that unusually high volumes of Nvidia GPUs subsequently appeared for sale, including proposed deals involving thousands of B300 chips.

The development shows export policy moving beyond physical shipment controls toward the location and identity of remote compute users. Nvidia expects overall demand to remain strong, but the rules are already reshaping who can finance and operate overseas AI infrastructure.

Source: [CNBC](https://www.cnbc.com/2026/11/25/nvidia-china-ai-chip-remote-access.html)

## Research Radar

### Spectrum Adaptation of AI-Native Autoencoder Communications with Transfer Learning

Yalin E. Sagduyu and Tugba Erpek study end-to-end learned physical layers under channel mismatch. By selectively fine-tuning a small subset of transmitter and receiver layers, their approach removes the mismatch-induced error floor and approaches full retraining while reducing time, MAC operations, energy, and updated parameters.

Source: [arXiv:2611.34942](https://arxiv.org/abs/2611.34942)

### Device-Referred Channel Sounding With Commodity Wi-Fi Receivers

Raghuram C. Kamath, Carlos Aldana, and Kavya Guruswamy show that commodity Wi-Fi CSI can support device-referred channel sounding at 5 and 6 GHz if five receiver impairments are corrected. Their pipeline brings median delay-spread bias into a −6% to +14% range and demonstrates body-worn measurements across six indoor sites.

Source: [arXiv:2611.34769](https://arxiv.org/abs/2611.34769)

### Feasibility-Aware Deep Reinforcement Learning for O-CU and O-DU Mapping in 6G O-RAN

Mohammad Asif Habibi, Xavier Costa-Perez, and Hans D. Schotten compare DQN and Double DQN placement of O-RAN functions against six conventional baselines. Double DQN placed 99.6% of functions in the largest scenario, but simple heuristics matched that quality with lower cost and decision time—an unusually candid result on where neural orchestration does not yet win.

Source: [arXiv:2611.34516](https://arxiv.org/abs/2611.34516)

## Source notes

Telecoms.com blocked automated retrieval of its 5G SA roaming report, so the milestone was cross-checked against Elisa’s syndicated corporate announcement. IEEE Xplore and ACM Digital Library searches did not surface additional newly indexed eligible wireless papers; today’s Research Radar uses verified arXiv records submitted November 25.

## Takeaway

The infrastructure stack is converging across terrestrial 5G, LEO constellations, AI-native radios, and thousand-agent software systems—while policy and verification increasingly determine what can scale safely.
