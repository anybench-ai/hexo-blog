---
title: "Morning Digest — November 7, 2026"
date: 2026-11-07 07:00:00
categories: [Digest, Technology]
tags: [6G, 5G-Advanced, LEO, AST SpaceMobile, NVIDIA, AI, Security, Agents]
---

Today’s strongest signals come from deployable infrastructure: dedicated satellite launch capacity, commercial Upper 6 GHz, AI-native radio tools, and agents that can remember, reason over experiments, and help construct scientific models.

<!-- more -->

## AST SpaceMobile plans its own 20-ton Blacklift rocket

AST SpaceMobile announced Blacklift, a heavy launcher intended to place its large BlueBird direct-to-cell satellites into low Earth orbit. The company says the rocket will use Miranda engines from Firefly Aerospace, carry roughly 20 metric tons, and target its first flight in 2028.

Owning a launch path could reduce AST’s dependence on scarce third-party manifests as it scales a constellation built around unusually large spacecraft. The tradeoff is execution risk: launch vehicles are expensive, schedule-sensitive systems far outside a conventional telecom operator’s core business.

Source: [AST SpaceMobile](https://x.com/AST_SpaceMobile/status/2118683507744727260)

## NVIDIA’s open 5G/6G tools pass one million downloads

NVIDIA says adoption of AI Aerial and Sionna grew tenfold over the past year, with its open-source 5G and 6G software exceeding one million downloads across more than 8,000 research and academic institutions.

The highlighted projects connect simulation to over-the-air testing: SoftBank reported up to 60% higher uplink throughput from a neural receiver, a University of Leeds system cut RAN power consumption by 45.6% while maintaining connectivity, and CTTC reduced some network simulations from about three hours to 10–20 minutes. Open tools are becoming a shared experimental substrate for AI-native wireless research.

Source: [NVIDIA](https://blogs.nvidia.com/blog/telco-open-source-tools-research-6g-networks/)

## Upper 6 GHz reaches a live commercial 5G-Advanced network

ZTE and du activated Upper 6 GHz radio equipment on du’s live UAE 5G-Advanced network. The deployment uses 350 MHz between 6775 and 7125 MHz, GigaMIMO antennas, and commercially available customer equipment.

Upper 6 GHz is strategically important because it combines far more contiguous bandwidth than traditional mid-band holdings with better coverage economics than millimeter wave. A live deployment helps turn the band from a WRC and standards debate into measurable operational evidence for future 5G-Advanced and 6G planning.

Source: [ZTE and du release](https://www.webwire.com/ViewPressRel.asp?aId=363592)

## DeepMind agents expose weaknesses in legacy 1024-bit RSA

Google DeepMind says human-guided AI agents produced two significant cryptanalytic advances in weeks, including methods that can bypass older digital-signature protections and factor legacy 1024-bit RSA keys in bulk. The company emphasizes that modern 2048-bit deployments are not vulnerable to these specific results.

The deeper implication is methodological: historical hardness assumptions may need continuous adversarial retesting as AI systems gain better mathematical search and tool-use capabilities. Cryptographic migration timelines should account for AI-assisted discovery, not only improvements in raw computing power.

Source: [Google DeepMind](https://x.com/GoogleDeepMind/status/2118755418675765656)

## Anthropic gives Claude a “dreaming” phase for long-term memory

Anthropic describes an agent-memory architecture built from salience judgments, persistent storage, retrieval, and a process it calls “dreaming.” Between active sessions, Claude can review logs and transcripts, consolidate useful information, correct mistakes, and reorganize memory for later access.

This separates immediate task execution from slower memory maintenance. Persistent agents need more than a large context window: they need mechanisms for deciding what deserves retention, revising stale conclusions, and retrieving the right fact without flooding every future session.

Source: [Anthropic](https://www.anthropic.com/research/components-of-agent-memory)

## OpenAI launches a benchmark for everyday wet-lab reasoning

OpenAI and Ligo introduced BioBasicsBench, a 100-task evaluation built from raw wet-lab evidence including gels, microscopy, sequencing files, instrument exports, notes, and failed experiments. The benchmark rewards agents for detecting errors and recognizing when the available evidence does not support a conclusion.

At the highest reasoning setting shared across models, GPT-6 Astra averaged 66.7% of available credit, compared with 43.8% for GPT-5.6 Sol. The result shows meaningful progress while leaving substantial room for improvement before agents can be trusted with routine experimental interpretation.

Source: [OpenAI](https://openai.com/index/measuring-how-ai-agents-handle-wet-lab-science/)

## Anthropic maps the next step for AI-built scientific models

Anthropic’s guest researchers outline how AI can participate across the scientific-modeling loop: writing executable models, fitting them to observations, comparing alternatives, and revising their structures. Simulation-based inference already lets neural networks infer plausible parameters for models that are easy to run but difficult to invert analytically.

The caution is as important as the capability. A model that reproduces data is not automatically an explanation; scientists still need to understand which assumptions distinguish competing models and whether those assumptions generalize beyond the fitted observations.

Source: [Anthropic](https://www.anthropic.com/research/teaching-ai-to-build-scientific-models)

## Research Radar

### Joint Delay--Doppler Modeling of Multipath LEO Channels

Kuan-Po Chiu and Sumit Roy propose a geometry-based stochastic model that generates wall reflections, ground reflections, and roof-edge diffraction over a complete LEO satellite pass. It jointly tracks delay, Doppler, power, and channel-impulse-response evolution as slant range, elevation, and azimuth change.

Omnidirectional results broadly reproduce 3GPP NTN elevation trends, but beamforming creates a mid-elevation K-factor peak absent from TR 38.811 and current 6G NTN assumptions. That mismatch matters for realistic beam-aware link simulation and receiver design.

Source: [arXiv](https://arxiv.org/abs/2611.02350)

### From Reactive to Agentic Resilience: Multi-Timescale AI-RAN Orchestration Under Signaling Storms

Sotiris Chatzimiltis, Mahdi Boloursaz Mashhadi, Mohammad Shojafar, and Rahim Tafazolli present a three-tier Open RAN controller: a slow orchestrator sets policy, a per-site agent anticipates events, and a deterministic near-real-time loop enforces decisions.

In a mass-attachment simulation, the agent read a scheduled event and provisioned capacity before the signaling surge, approaching fully provisioned resilience with one-quarter of the server capacity. Previously unseen free-text operator intents were grounded into directives at 94% exact match.

Source: [arXiv](https://arxiv.org/abs/2611.03406)

### Re-Planning Budgets under Admission Control in Grant-Free LEO Beam-Hopping Access

Joon-Young Park and Young-Chai Ko analyze how reordering LEO beam-hopping visits affects grant-free update delivery even when every region receives the same total service time. They derive the maximum allowable position change for a prescribed delivery-rate loss.

In a 40-group example, accepting a 1% loss raised the safe reordering budget from 17 to 24 positions while retaining more than 90% of the priority-weighted waiting-cost reduction achieved by unrestricted ordering. The work is submitted to IEEE ICC 2027.

Source: [arXiv](https://arxiv.org/abs/2611.07592)

## Source notes

IEEE Xplore and ACM Digital Library searches returned no newly indexed matching papers. Research Radar therefore uses verified arXiv records published within the last seven days.

## Takeaway

Wireless and AI systems are converging around deployable infrastructure—launch capacity, upper-midband spectrum, AI-native RAN control, persistent agent memory, and benchmarks grounded in real work.
