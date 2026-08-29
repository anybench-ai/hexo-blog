---
title: Morning Digest - Saturday, August 29, 2026
date: 2026-08-29 04:00:00
tags:
  - AI
  - 6G
  - LEO
  - Semiconductors
  - Research
categories:
  - digest
---

## OpenAI will cut Cursor off after its SpaceX acquisition

OpenAI says it intends to wind down Cursor's access to its models, proposing a November 12 shutoff after SpaceX acquired the coding-tool company. OpenAI says the change-of-control clause gives it a limited cancellation window and cites prior contract and terms-of-service violations by Elon Musk's companies. The immediate developer impact is that future OpenAI frontier models will not reach users through the Cursor integration unless the dispute changes course.

Source: https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/

## Claude autonomously finds fixes for alignment failures

Anthropic reports that Claude autonomously researched, trained, and tested mitigations for ten categories of alignment failure, closing substantial safety gaps without degrading general capabilities. The best methods transferred to held-out benchmarks and models up to 4.7 times larger; Claude also outperformed a constrained comparison group of 28 human safety researchers. In a production-scale experiment, Sonnet 5 brought an early Opus 4.8 checkpoint close to production alignment scores in 60 hours using a compact training set, pointing toward automated safety research that scales alongside model capability.

Source: https://www.anthropic.com/research/automated-researchers-mitigate-alignment-failures

## AST SpaceMobile and 2degrees open a New Zealand gateway

New Zealand operator 2degrees opened the Marton satellite ground station and completed voice, video, and data tests using ordinary smartphones over AST SpaceMobile's network. The facility links AST's satellites into the carrier core and is described as one of the company's first commercial gateways. This is a concrete direct-to-device deployment milestone: satellite coverage is being integrated into terrestrial mobile infrastructure rather than offered as a separate terminal service.

Source: https://www.telecompaper.com/news/2degrees-opens-ast-spacemobile-ground-station-and-completes-smartphone-tests--1580913

## SpaceX pulls a satellite spectrum fight into the Rocket Lab-Iridium review

SpaceX asked the FCC to examine Iridium's conduct while the agency reviews Rocket Lab's proposed $8 billion acquisition of the satellite operator, although SpaceX explicitly says it does not oppose the transaction. The underlying technical dispute concerns next-generation Starlink ground gateways sharing 19.4–19.6 GHz and 29.1–29.3 GHz spectrum with Iridium. Iridium says some proposed gateways could exceed interference limits; SpaceX argues the objections are anticompetitive. The proceeding shows how gateway spectrum coordination can become strategically important as LEO networks chase gigabit service.

Source: https://www.pcmag.com/news/spacex-pushes-fcc-to-scrutinize-rocket-lab-iridium-deal-amid-spectrum-clash

## Starlink launches service in Equatorial Guinea

Starlink says high-speed, low-latency broadband is now commercially available in Equatorial Guinea. The announcement is a small but useful deployment marker: Starlink's constellation advantage only becomes economically meaningful when landing rights, local distribution, and usable capacity turn orbital coverage into country-level service. The launch further expands the operator's African footprint.

Source: https://x.com/Starlink/status/2093591226016829662

## Texas A&M's NVIDIA supercomputer compresses years of drug screening into a week

Texas A&M's VISION DGX SuperPOD used nearly 760 NVIDIA Hopper GPUs to screen 10.4 million compounds in one week, work the university says would previously have taken years. The run identified more than 22,000 drug candidates, compared with roughly 120 across earlier efforts, while the shared system operates at 95–98% utilization across 26 projects and seven institutions. Beyond the NVIDIA showcase, the case illustrates what sustained academic access to dense GPU infrastructure changes: researchers can use higher-precision models and explore targets that would otherwise be computationally uneconomic.

Source: https://www.nvidia.com/en-us/case-studies/texas-a-m-university/

## Washington reportedly targets remote Chinese access to AI chips

The Trump administration is reportedly preparing a narrower successor to the AI diffusion rule that would restrict Chinese access to advanced US chips through remote overseas servers, not only direct hardware shipments. The proposal could be shared with industry as soon as September. If adopted, the enforcement boundary would shift from tracking physical chip destinations toward monitoring where cloud compute is ultimately consumed, a much harder technical and compliance problem.

Source: https://www.tomshardware.com/tech-industry/policy/new-us-export-controls-reportedly-target-chinese-access-to-remote-ai-servers-trump-admins-cut-down-ai-diffusion-rule-could-be-shared-with-industry-as-soon-as-september

## Research Radar

### Knowledge Distillation Driven Semantic NOMA with GAN Refinement for 6G Robotic Vehicle Networks

Qifei Wang, Zhen Gao, Li Qiao, Ziwei Wan, De Mi, Dapeng Li, and Ying Sun, IEEE VTC-Spring 2026 / arXiv. The paper combines a DeepJSCC visual link, an orthogonal-transmission teacher for training an interference-tolerant NOMA student, and conditional GAN refinement. The result targets high-fidelity robotic-vehicle perception under tight bandwidth and energy budgets without adding distillation overhead at inference time.

Source: https://arxiv.org/abs/2608.27198

### Spectral-Efficient MIMO-OFDM: Low-Complexity Solution based on Random Multiplexing

Jie Yang, Wanchen Hu, Yi Song, Shuangyang Li, Burak Çakmak, Lei Liu, Xin Wang, and Giuseppe Caire, arXiv. The proposed system intentionally compresses symbols across subcarriers through random-multiplexing precoding and uses orthogonal approximate message passing for linear-complexity detection. The authors report higher achievable rates and favorable error performance while preserving compatibility with current 5G architectures.

Source: https://arxiv.org/abs/2608.26838

### PRO-RAN: Processor-Level Characterization of Open RAN Centralized and Distributed Units

Moojan Kamalzadeh, Larry Horner, Linqi Xiao, Abhishek Bhattacharyya, Ehsan Bahaloo Horeh, Padmapriya Patil, Venkateswarlu Gudepu, and Andrea Fumagalli, arXiv. PRO-RAN independently profiles Open RAN CU and DU functions with Intel VTune after validating end-to-end registration and traffic. Its contribution is methodological: aggregate CPU utilization hides different execution paths and bottlenecks, so function-level characterization can guide placement, provisioning, optimization, and acceleration.

Source: https://arxiv.org/abs/2608.26498

## Source Issues

- IEEE and ACM searches returned no stronger fresh wireless papers; Research Radar uses new arXiv records, including one paper presented at IEEE VTC-Spring 2026.
- X worked normally; the Starlink availability item uses the official company post as its primary source.

## Takeaway

Today's strongest thread is infrastructure control—who supplies frontier models, who governs scarce spectrum and chips, and how satellite and GPU systems move from capacity into deployed service.
