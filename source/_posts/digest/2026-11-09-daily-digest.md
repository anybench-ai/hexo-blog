---
title: "Morning Digest — November 9, 2026"
date: 2026-11-09 07:00:00
categories: [Digest, Technology]
tags: [LEO, Direct-to-Device, 6G, AI, NVIDIA, Security, Robotics, Starlink]
---

Today’s strongest signals sit below the model layer: sovereign satellite and AI infrastructure, firm power for data centers, external red teaming, robot-edge offload, and practical tools for long-running agents.

<!-- more -->

## Rakuten and AST form a sovereign direct-to-device venture in Japan

Rakuten Group and AST SpaceMobile agreed to establish Rakuten AST, a 51/49 joint venture tasked with building a Japanese low-Earth-orbit network that connects directly to ordinary smartphones. Japan’s J-LEO program selected the proposal for up to ¥148 billion—about $1 billion—in support over roughly three years, with domestic operations targeted by the end of March 2029.

The network is intended to extend broadband beyond terrestrial coverage and preserve service during disasters through emergency inter-carrier roaming. AST will supply satellites compatible with mid-band spectrum, while Rakuten plans work on AI-driven spectrum management and edge computing. The project turns direct-to-device satellite service into sovereign national infrastructure rather than merely a roaming add-on.

Source: [Rakuten Group](https://global.rakuten.com/corp/news/press/2026/1109_01.html)

## NVIDIA links Korean AI chips to its rack-scale infrastructure

NVIDIA, Korean AI-chip startup Rebellions, and SK Telecom announced a sovereign-AI infrastructure collaboration supported by Korea’s Ministry of Science and ICT. Rebellions plans to connect its next-generation R200 NPUs through NVIDIA NVLink Fusion and use the MGX rack architecture; SK Telecom plans to deploy the resulting systems in its AI data center.

The design targets disaggregated inference, with NVIDIA GPUs handling model prefill and Rebellions NPUs handling decode. That could pair general-purpose accelerator capacity with specialized, energy-efficient token generation while sharing rack, power, cooling, and networking standards. R200 systems are expected to be ready for deployment in 2028.

Source: [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-rebellions-and-sk-telecom-announce-collaboration-to-advance-sovereign-ai-infrastructure-with-nvidia-nvlink-fusion)

## Anthropic reportedly locks up 1.7 GW of gas generation

Anthropic has reportedly agreed to spend about $3.4 billion for commitments covering 1.7 gigawatts of heavy-duty gas-fired generators for its data centers. The deal involves equipment ordered from Caterpillar through Texas supplier OnePWR Solutions and would be the largest known single purchase of power-generation equipment by an AI laboratory.

The scale illustrates how the AI race is moving beyond chips and data-center buildings into generation assets themselves. Securing firm power years ahead can reduce exposure to grid interconnection delays, but it also intensifies questions about emissions, local infrastructure, and whether private generation will become a standard component of frontier-model economics.

Source: [CNBC](https://www.cnbc.com/2026/11/08/anthropic-generator-deal-ai-data-centers.html)

## OpenAI expands its external red-team partnership with Hacktron

OpenAI is expanding Hacktron’s access to frontier models through its Daybreak Red program. The security company is building AI agents for code review, penetration testing, and red teaming, with the partnership focused on finding vulnerabilities in OpenAI systems and in the ways those systems interact with third-party platforms.

Giving an outside specialist deeper model access is a meaningful governance choice: it lets independent offensive-security work scale with the capabilities being deployed. It also tests whether frontier cyber models can create a practical defender advantage when paired with clear authorization, controlled access, and responsible disclosure.

Source: [OpenAI](https://openai.com/index/partnering-with-hacktron/)

## SpaceX targets November 13 for Starship Flight 15

SpaceX says Starship Flight 15 is preparing for a tower catch and is targeting launch as early as Friday, November 13, pending regulatory approval. The mission follows continued work on recovering both stages and shortening the turnaround between integrated flight tests.

A successful catch would matter beyond launch spectacle. Rapid, repeatable recovery is central to the economics of deploying large satellite constellations and any future orbital-compute infrastructure, where payload mass and launch cadence become system-level constraints.

Source: [SpaceX on X](https://x.com/SpaceX/status/2119093662957060389)

## Mistral stress-tests Voxtral 3 on a live conference stage

Mistral used Voxtral 3 Transcribe to capture every main-stage talk at AI Engineer Paris in real time. The team applied context biasing by feeding the model speaker names and technical terms from the conference agenda, a practical way to improve recognition in jargon-heavy live events.

The demonstration shows the value of controllable transcription beyond benchmark accuracy. Live systems need domain vocabulary, low latency, robust turn handling, and predictable integration with downstream search and summarization workflows; context biasing is a simple lever developers can reuse in their own events and applications.

Source: [Mistral AI on X](https://x.com/MistralAI/status/2119651192737259701)

## A context-compression plugin climbs GitHub’s AI trends

The open-source `billion-context` project is drawing attention for its attempt to keep agent sessions alive for weeks or months without requiring a billion-token model window. The project claims continual compression can support billion-token cumulative histories inside a roughly 100K active context and reduce token consumption by about fivefold.

Those figures remain project claims rather than an independent benchmark, but the demand signal is real. As agents become persistent, context engineering is turning into an infrastructure problem: systems must decide what to preserve verbatim, what to summarize, and how to recover details without letting memory cost grow linearly with time.

Source: [GitHub](https://github.com/ranxianglei/billion-context)

## Research Radar

### DeepRT-Cal: Learning to Calibrate Ray-Traced Twin Channel Statistics with Low-Fidelity Environmental Geometry

Shaoyi Liu and colleagues propose a cross-fidelity calibration framework for 6G digital-twin channels. The model uses low-fidelity geometry and ray-tracing features at deployment while learning from detailed geometry as privileged information during training.

In an outdoor non-line-of-sight region, DeepRT-Cal reduced received-power mean absolute error from 16.80 to 3.88 dB and RMS delay-spread error from 304.89 to 98.19 ns. The result suggests that useful channel twins may not require prohibitively expensive high-fidelity 3D maps everywhere.

Source: [arXiv](https://arxiv.org/abs/2611.09079)

### VLA Handover: Failure-Prediction-Based Switching from On-Robot to Server VLA Models

Takayuki Nishio proposes a handover mechanism in which a robot runs a small vision-language-action model locally and calls a larger server model only when the local model is predicted to fail. The approach is designed for beyond-5G and 6G remote inference without sending every action decision over the network.

Across three LIBERO suites, the method improved success by 11–22 percentage points over the small on-robot model while issuing 49–77% fewer server requests than server-only control. Completion time also degraded less as network latency increased. The paper is submitted to IEEE ICC 2027.

Source: [arXiv](https://arxiv.org/abs/2611.08987)

### A First Look at Starlink Maritime on Cruise Ships

Jinwei Zhao, Kousar Malekinasab, and Jianping Pan present the first systematic measurement study of Starlink on commercial cruise ships, combining terminal telemetry with inside-out and cloud-based measurements on two vessels.

The onboard network largely determined passenger experience because cruise lines rate-limited individual devices and distributed sessions across several terminals through multi-WAN routers. Public IPs changed both at and within points of presence, while PoP selection followed neither maritime jurisdiction nor geographic proximity alone.

Source: [arXiv](https://arxiv.org/abs/2611.07191)

## Source notes

IEEE Xplore and ACM Digital Library returned no newly indexed matching papers, so Research Radar uses verified arXiv records from the last seven days.

## Takeaway

The competitive frontier is shifting from standalone models toward the infrastructure that makes AI and ubiquitous connectivity deployable—power, interconnects, satellites, security, and efficient context management.
