---
title: "Morning Digest — November 11, 2026"
date: 2026-11-11 07:00:00
categories: [Digest, Technology]
tags: [AI, Formal Verification, 5G, 6G, LEO, NVIDIA, OpenAI, Google DeepMind]
---

Today’s strongest signals are about systems that can be trusted and deployed: machine-generated formal proofs, long-horizon models, business-facing agents, onboard autonomous-driving reasoning, portable satellite terminals, and more resilient terrestrial and space networks.

<!-- more -->

## DeepMind formally verifies Signal’s protocol down to code

Google DeepMind introduced AlphaProof Code, an agentic formal-verification framework that turns software properties into machine-checkable Lean proofs. Applied to selected parts of Signal’s cryptographic protocol and implementation, Gemini agents generated more than six million lines of proof code while human specialists focused on the critical 1%.

The team also reintroduced two real, previously repaired Signal bugs into an isolated codebase. AlphaProof Code distinguished the faulty version from the correct one, providing an important check that the proof pipeline was not merely producing plausible-looking formal artifacts. This is a meaningful step toward AI-assisted verification of infrastructure where testing alone cannot cover the full state space.

Source: [Google DeepMind](https://deepmind.google/blog/introducing-alphaproof-code/)

## Gemini 4 Carbon reaches broad developer availability

Google made Gemini 4 Carbon broadly available to paying developers and enterprises through the Gemini API in AI Studio and its business products. The model is aimed at extended, verification-heavy work in software engineering, cybersecurity, science, and complex knowledge tasks.

Carbon launches at the same introductory API pricing as Gemini 4 Argon: $2 per million input tokens and $10 per million output tokens, with cached inputs discounted by 95%. The combination of long-horizon capability and relatively aggressive pricing makes the economics of sustained agent work—not only benchmark performance—a central part of frontier-model competition.

Source: [Google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-carbon-now-available/)

## OpenAI brings verified businesses and shopping agents into ChatGPT

OpenAI launched Businesses in ChatGPT in beta. Eligible businesses can claim and verify their profiles through Business Hub, update company information, provide product feeds with current pricing and availability, and see aggregated insights about mentions, website clicks, and common topics.

Eligible U.S. ecommerce and online-service businesses can also publish clearly labeled Business Agents that answer questions and help customers compare offerings. OpenAI says businesses do not receive users’ ChatGPT conversations or Business Agent chats. The product turns ChatGPT from an independent discovery interface into a new managed surface where brands can maintain structured information and operate customer-facing agents.

Source: [OpenAI](https://openai.com/index/introducing-businesses-chatgpt/)

## NVIDIA shrinks autonomous-driving reasoning into a 2B edge model

NVIDIA released technical details for Alpamayo 2 Edge, a two-billion-parameter vision-language-action model designed to perform adaptive driving reasoning within onboard compute and latency limits. It produces trajectories and, when useful, causal explanations for decisions such as yielding to pedestrians or making space for an approaching bus.

The model is post-trained with closed-loop reinforcement learning in AlpaGym, where its actions alter subsequent driving states and expose compounding errors that static datasets miss. NVIDIA reports a 48.9% improvement in closed-loop driving performance over its strongest checkpoint without closed-loop reinforcement learning. The result matters because practical autonomous systems need reasoning that runs locally and reacts at vehicle timescales.

Source: [NVIDIA Technical Blog](https://developer.nvidia.com/blog/running-av-reasoning-models-within-onboard-compute-and-latency-limits/)

## Starlink unveils a battery-powered Mini 2 terminal

Starlink introduced Mini 2 as its next-generation portable satellite terminal. The device integrates Wi-Fi, can connect within about 60 seconds with a clear view of the sky, and promises up to 4.5 hours of operation from a quick-swap battery. It can also run from USB-C power.

Invitation-only U.S. preorders are beginning first. A self-contained battery option changes the operational envelope of a portable LEO terminal: connectivity can travel farther from vehicles, buildings, and fixed power, making it more useful for field research, emergency response, and temporary remote deployments.

Source: [Starlink on X](https://x.com/Starlink/status/2120206875581186293)

## Microsoft pushes back on a proposed U.S. ban on Chinese optical transceivers

Microsoft is pressing the U.S. administration not to impose a broad ban on Chinese-made optical transceivers used in AI data centers. The policy debate sits at the intersection of supply-chain security and the enormous optical-connectivity demand created by clustered accelerators.

Supporters of stronger restrictions argue that China-linked communications components should be excluded from critical networks. Microsoft and other opponents warn that rules applied too broadly or too quickly could constrain AI infrastructure while domestic suppliers expand capacity. The dispute shows that AI bottlenecks are moving beyond chips and power into networking components that join large compute systems together.

Source: [Reuters via Investing.com](https://www.investing.com/news/stock-market-news/exclusivemicrosoft-presses-trump-to-scuttle-expected-ban-on-chinese-data-center-technology-5014745)

## Upper 6 GHz gains momentum as a bridge from 5G-Advanced to 6G

Telecom leaders participating in the GCC’s 10Giga initiative highlighted upper-6-GHz spectrum as a practical route to wider channels and greater capacity for 5G-Advanced. The band is drawing attention because it can offer more bandwidth than traditional midband spectrum while retaining a more manageable coverage profile than millimeter wave.

The discussion connects near-term deployment to the longer 6G roadmap, where operators expect communications, sensing, AI, and non-terrestrial access to become more tightly integrated. Spectrum policy will determine whether upper 6 GHz becomes a globally harmonized mobile layer or a fragmented regional resource.

Source: [Telecom Review Group via The Manila Times](https://www.manilatimes.net/2026/11/10/tmt-newswire/pr-newswire/telecom-review-group-accelerates-the-journey-to-10giga-gcc-with-u6ghz/2466051)

## Research Radar

### Criticality-Aware RAN Function Placement for Robust 6G Networks

Gabriel M. Almeida, Joao F. Santos, Walid Saad, Nicola Marchetti, and Kleber V. Cardoso study how disaggregating base stations into cloud-hosted centralized and distributed units can create shared failure points. Their optimization model places RAN functions to reduce dependencies and cloud-location criticality while respecting compute, transport, and cost constraints.

On a real-world mobile-network topology, the method left up to 75% more radio units operational after random disruptions and targeted attacks than existing placement approaches. The paper turns RAN resilience into an explicit placement objective rather than treating it as a byproduct of cost optimization.

Source: [arXiv:2611.14121](https://arxiv.org/abs/2611.14121)

### Energy-Harvesting-Aware Cell-Free LEO Satellite Networks

Wali Ullah Khan studies downlink control for user-centric cell-free LEO networks whose satellites depend on intermittent solar harvesting and finite onboard batteries. A perturbed Lyapunov controller coordinates clustering and hybrid beamforming using observed battery state and causal energy forecasts.

Multi-orbit simulations show that queue-aware scheduling can preserve larger battery reserves under stressed conditions, although the protection comes at an effective-energy-efficiency cost. The work makes energy state a first-class part of satellite association and beam decisions rather than assuming uniform, always-available power.

Source: [arXiv:2611.11283](https://arxiv.org/abs/2611.11283)

### Multi-Granularity Resource Mapping for MEO-Assisted LEO Networks

Yi Jing, Chunxiao Jiang, Jiawei Wang, Jiachen Sun, and Yafeng Zhan model LEO satellites as communication-computing nodes whose user association depends on radio links as well as CPU, GPU, NPU, memory, storage, energy, queue, and thermal state. MEO aggregators relay telemetry while a network-control center maintains the global resource view.

In experiments using a 1,584-satellite shell and real service-bandwidth traces, the method improved realized utility by 10.64% and reduced end-to-end outage by 5.70 percentage points relative to static mapping. Quantizing resource targets cut signaling by 19.84% with negligible utility loss.

Source: [arXiv:2611.11208](https://arxiv.org/abs/2611.11208)

## Takeaway

AI is moving from impressive outputs into verifiable code, customer-facing agents, and edge autonomy while wireless systems simultaneously harden their resilience, spectrum, and spaceborne compute layers.
