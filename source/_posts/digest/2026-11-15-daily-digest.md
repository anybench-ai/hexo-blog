---
title: "Morning Digest — November 15, 2026"
date: 2026-11-15 07:00:00
categories: [Digest, Technology]
tags: [AI, 5G, 6G, LEO, Amazon Leo, OpenAI, Anthropic, NVIDIA, Robotics]
---

AI is beginning to reshape both ends of infrastructure—from agent-authorized payments and generalist robot control to uplink-heavy 6G traffic and risk-aware radio design.

<!-- more -->

## Amazon Leo’s first Vulcan mission targets today with 40 satellites

Amazon’s LV-01 mission is targeting liftoff at 12:11 p.m. EST on November 15 after slipping from Saturday. The mission will carry 40 Amazon Leo satellites in Vulcan’s most powerful VC6L configuration, making it the constellation’s largest payload so far.

LV-01 is also the first of 38 contracted Amazon Leo missions on Vulcan and uses a shorter, LEO-optimized Centaur V upper stage. Amazon says it has already launched nearly 400 satellites across 14 missions as it prepares to begin commercial broadband service.

Source: [Amazon Leo mission tracker](https://www.aboutamazon.com/news/innovation-at-amazon/project-kuiper-satellite-rocket-launch-progress-updates)

## Nokia says AI will drive 44% of network traffic by 2035

Nokia’s 2026 Global Network Traffic Report projects worldwide traffic will nearly quadruple to 3,789 exabytes per month by 2035, with AI responsible for 44%. Agentic-AI traffic is forecast to grow 160-fold and physical-AI traffic 105-fold over the decade.

The directional change matters as much as the volume. Nokia expects uplink to reach 24% of access traffic in the cells with the heaviest AI use, while more than 90% of physical-AI traffic will originate upstream. It also projects that edge and metro-core infrastructure will serve 36% of AI-native traffic.

Source: [Nokia Global Network Traffic Report 2026](https://www.nokia.com/insights/global-network-traffic-report/)

## OpenAI launches ChatGPT Wallet for agent purchases

OpenAI introduced ChatGPT Wallet, a payment layer that allows agents to complete purchases without seeing a user’s actual card details. Each purchase currently requires the customer to review the order and approve it with a security check such as Face ID or a fingerprint, after which the payment network issues a token for checkout.

Built with American Express, Mastercard, and Visa, the wallet preserves eligible card rewards and dispute protections and works with existing merchant checkout systems. It begins rolling out through dots to US ChatGPT Pro subscribers aged 18 and older, with fully delegated purchases governed by spending limits presented as a future direction.

Source: [OpenAI](https://openai.com/index/introducing-chatgpt-wallet/)

## OpenAI folds its standalone robotics team into core groups

OpenAI confirmed that it has dissolved its standalone robotics team and reassigned its researchers. Robotics research moves into the main research organization under Mark Chen, while applied robotics and hardware move into the Applied organization under Greg Brockman.

The reorganization reflects OpenAI’s view that general-purpose frontier models can increasingly control robots directly, making robotics a downstream application of broad language, vision, and reasoning capabilities. The company says it remains committed to a humanoid demonstration in 2027, though specialists note that onboard latency and deployment-specific data still favor smaller purpose-built models in many settings.

Source: [Fortune](https://fortune.com/2026/11/13/openai-disbands-robotics-team-as-its-general-models-start-running-robots/)

## Anthropic’s IPO order book reaches roughly six times the shares offered

Investor orders for Anthropic’s IPO are reportedly about six times larger than the available share pool. That is a material new development following the company’s IPO filing and roadshow, which were covered in yesterday’s digest.

The demand points to strong institutional appetite despite the scale and risk of the offering. Anthropic is targeting a November 19 Nasdaq debut under the ticker ANT, with pricing expected November 18 if the schedule holds.

Source: [Bloomberg](https://www.bloomberg.com/news/articles/2026-11-12/anthropic-s-ipo-is-said-to-be-about-six-times-oversubscribed)

## NVIDIA highlights vision AI and robotics for waste sorting

NVIDIA highlighted startups applying vision AI and robotics to used clothing, bottles, and mixed recycling streams. Computer vision can identify material as it passes on conveyors, giving operators better real-time information and enabling robotic systems to recover more reusable material.

The use case is a practical example of physical AI outside factories and warehouses: perception and actuation are being combined in messy, high-throughput environments where classification errors have immediate economic and environmental costs.

Source: [NVIDIA on X](https://x.com/nvidia/status/2121647261155570145)

## Airtel’s founder expects India’s 6G rollout around 2030

Bharti Airtel founder Sunil Bharti Mittal told NDTV that India should be ready for 6G around 2030. He characterized the next generation as a sensing network connecting glasses, rings, earbuds, and AI agents rather than merely delivering faster smartphone data.

Mittal also emphasized the financing problem behind the vision: Indian operators have invested heavily in spectrum and 5G infrastructure but have not yet created enough new revenue streams. His argument is that sustainable 6G deployment depends on monetizing 5G before another capital cycle begins.

Source: [NDTV](https://www.ndtv.com/india-news/rollout-in-2030-a-sensing-network-sunil-mittal-to-ndtv-on-6g-12321203)

## Research Radar

### Criticality-Aware RAN Function Placement for Robust 6G Networks

Gabriel M. Almeida, Joao F. Santos, Walid Saad, Nicola Marchetti, and Kleber V. Cardoso study how disaggregated RANs become vulnerable when centralized and distributed units share cloud locations. Their optimization jointly minimizes functional dependency and placement cost while enforcing cloud criticality, compute, and transport constraints.

On a real mobile-network topology, the approach left up to 75% more radio units operational than existing placement methods after random failures and targeted attacks. The result connects cloud-native RAN economics to a concrete resilience metric rather than treating centralization as an unqualified benefit.

Source: [arXiv:2611.14121](https://arxiv.org/abs/2611.14121)

### Risk-Aware Joint Inference and Resource Control for Physical AI in 6G Networks

Amin Farajzadeh and Melike Erol-Kantarci propose RACE, a controller that maps predicted action-failure probability and task criticality into adaptive SINR targets for wireless edge inference. A slow-timescale LLM proposes task requirements for deterministic validation, while a fast hybrid actor selects inference configurations and transmit power.

Simulations improved the combined accuracy-latency-energy objective by 11% over fixed high-SINR control with near-zero constraint outage. The design avoids wasting radio resources on low-risk actions while protecting safety-critical ones more aggressively.

Source: [arXiv:2611.14696](https://arxiv.org/abs/2611.14696)

### Privacy-Preserving Spectrum Data Obfuscation in Next-Generation Spectrum Coexistence Systems

Yalin E. Sagduyu, Tugba Erpek, Sastry Kompella, and Joseph A. Molnar show that naive randomized disclosures can leak protected spectrum-occupancy patterns because an observer can exploit Markovian or periodic temporal structure. The paper introduces history-based, belief-based, cycle-dominance, and decoy schemes to frustrate that inference.

The work is relevant to shared-spectrum systems where primary-user activity must be disclosed enough to prevent interference but cannot be revealed exactly for security or regulatory reasons. It frames disclosure as an adversarial sequential-inference problem rather than a one-shot privacy mechanism.

Source: [arXiv:2611.15770](https://arxiv.org/abs/2611.15770)

## Source Notes

Spaceflight Now returned HTTP 403, so the Amazon mission schedule was verified against Amazon’s official tracker instead. IEEE Xplore and ACM Digital Library returned no newly indexed eligible papers; Research Radar therefore uses verified arXiv records from the last seven days, including one manuscript submitted to IEEE.
