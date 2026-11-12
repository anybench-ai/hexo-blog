---
title: "Morning Digest — November 12, 2026"
date: 2026-11-12 07:00:00
categories: [Digest, Technology]
tags: [AI, 5G, LEO, NVIDIA, OpenAI, Google DeepMind, Private Networks, Agent Tools]
---

Today’s strongest advances turn AI and connectivity into deployable infrastructure: cell-aware models for genetics, new evidence about chain-of-thought monitoring, enterprise voice agents, sovereign private 5G, expanding direct-to-device satellite capacity, and standardized tools for agent skills.

<!-- more -->

## DeepMind’s AlphaGenome 2 resolves genetic effects by cell type

Google DeepMind introduced AlphaGenome 2, a conditional DNA-sequence model that predicts how genetic variants affect specific human cell types and states. It was trained on more than 100 million individual cell profiles across 68 tissues and can condition its predictions on a selected cell type or on data uploaded from a new single-cell experiment.

On the TenK10K immune-cell dataset, the model identified nearly twice as many causal variants as the original AlphaGenome fine-tuned on single-cell data. It can also generalize to previously unseen states without retraining, such as vaccine-activated immune cells. AlphaGenome 2 is available for non-commercial research through an API, with commercial research in private preview.

Source: [Google DeepMind](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)

## Better models may become harder to monitor through chain of thought

OpenAI studied how pretraining, model architecture, reinforcement learning, and synthetic training data affect two proxies for chain-of-thought monitorability: the ability to reason without visible reasoning tokens and the ability to control what appears in a reasoning trace.

Lower base-model perplexity strongly correlated with stronger no-chain-of-thought reasoning, while reinforcement learning increased control over reasoning traces even without direct process supervision. The study also found that this controllability can transfer through model-generated fine-tuning data. The results suggest that monitoring visible reasoning will become less reliable as models improve, strengthening the case for complementary action- and activation-based oversight.

Source: [OpenAI Alignment Research](https://alignment.openai.com/cot-monitorability-model-lifecycle)

## NVIDIA brings Nemotron models to ElevenLabs voice agents

NVIDIA expanded its collaboration with ElevenLabs by adding Nemotron models to the ElevenAgents platform. The integration gives enterprises and governments another customizable model family for building voice agents that can reason, retrieve information, and act through spoken interfaces.

The partnership is notable because production voice systems require more than speech synthesis: they need low-latency orchestration, controllable models, and deployment options suited to regulated organizations. NVIDIA’s move places its open model family inside a widely used voice-agent stack rather than limiting it to standalone inference endpoints.

Source: [NVIDIA on X](https://x.com/nvidia/status/2120627069952340361)

## Verizon and Nokia complete a five-site private 5G network

Verizon Business and Nokia completed one of Europe’s largest private 5G implementations across a 38-kilometer stretch of the Thames Freeport economic zone. The network spans five industrial sites serving port, logistics, and manufacturing operations, with each tenant running its own 5G core to preserve data sovereignty.

Current uses include asset tracking, video analytics, robotics, connected workers, and autonomous systems at facilities operated by DP World, Ford Dagenham, and the Port of Tilbury. The deployment also acts as a test bed for AI-based vehicle-damage detection, digital twins, drone video analysis, and operational decision support.

Source: [Light Reading](https://www.lightreading.com/private-networks/verizon-nokia-show-private-5g-chops-at-uk-s-thames-freeport)

## AST SpaceMobile accelerates its BlueBird deployment plan

AST SpaceMobile reported third-quarter revenue of $42.3 million, up from $14.7 million a year earlier, while detailing a faster satellite-production and launch plan. The company expects to reach six ASIC-equipped BlueBird satellites per month in December and says the new chips provide ten times the processing bandwidth of its first-generation spacecraft.

AST is targeting approximately 45 BlueBirds in orbit by mid-2027 and initial intermittent nationwide coverage in the United States, Canada, Japan, Saudi Arabia, and the United Kingdom. Satellites 14 through 16 are awaiting a SpaceX launch date, while later batches are scheduled across Blue Origin and dual-use government missions. The update is a meaningful shift from demonstrations toward constellation-scale service readiness.

Source: [The Journal of Space Commerce](https://www.exterrajsc.com/p/direct-to-smartphone-satellite-operator)

## An open agent-skills package manager reaches GitHub’s trend list

Vercel Labs’ open-source `skills` CLI is gaining attention as developers standardize reusable capabilities across coding agents. The tool can discover, install, update, and remove skill packages, supports multiple agent environments, and includes security-audit checks before installation.

Agent ecosystems are beginning to resemble conventional software ecosystems: prompts and workflows are being packaged as versioned dependencies rather than copied manually between projects. A cross-agent installer also reduces lock-in by making the same skill available across different assistants and development surfaces.

Source: [Vercel Labs on GitHub](https://github.com/vercel-labs/skills)

## White House officials split over tighter NVIDIA chip-diversion controls

Axios reports that President Trump approved proposed action three times against companies suspected of diverting NVIDIA AI chips to China, but Commerce Secretary Howard Lutnick resisted or delayed implementation. The dispute comes amid increasing scrutiny of remote access and intermediary routes that can weaken hardware export controls.

The policy question is no longer limited to which accelerators can be shipped directly. Enforcement now has to account for cloud access, shell companies, transshipment, and the broader supply chain around advanced computing. That makes export-control implementation a persistent operational issue for NVIDIA and its customers, not merely a licensing rule at the border.

Source: [Axios](https://www.axios.com/2026/11/11/trump-lutnick-nvidia-china-chip-export-controls)

## Research Radar

### Toward Pseudorange-Based PNT with Starlink: A Mock Fused LEO GNSS Implementation

Samuel C. Morgan, Zacharias M. Komodromos, Wenkai Qin, Andrew Graff, Zachary L. Clements, W. Jeremy Morrison, and Todd E. Humphreys combine live Starlink Ku-band time-of-arrival observations with high-fidelity, beam-specific orbit and clock models to emulate an operator-supported positioning, navigation, and timing service.

Despite using consumer-grade receiver hardware, the field campaign achieved 95% error bounds of 2.33 meters horizontally, 3.37 meters vertically, and 11.19 nanoseconds in timing. The work shows how a communications constellation could provide GNSS-competitive resilient PNT if operators expose sufficiently accurate timing and ephemeris assistance.

Source: [arXiv:2611.13655](https://arxiv.org/abs/2611.13655)

### Soft-then-Hard: Joint Link Association and Precoding Optimization for LEO Satellite Networks

Hyeongtak Yun, Wonjae Shin, and Jeonghun Park address a failure mode in joint LEO link association and precoding: hard updates can turn off weak links too early, leaving them unable to recover in later iterations. Their method relaxes associations into continuous weights, anneals those weights while updating precoders, and applies hard matching only at the end.

The authors also model space-time channels where distinct Doppler shifts help separate users beyond what angular geometry permits. Simulations show that the approach outperforms baselines by preserving candidate links long enough to find stronger joint configurations.

Source: [arXiv:2611.10482](https://arxiv.org/abs/2611.10482)

### Coexistence of LEO Satellite Communication Systems under Regulatory Protection Constraints

Sunwoo Min, Daesik Hong, Jemin Lee, and Ian P. Roberts study two LEO systems sharing a band when the secondary constellation must protect a primary operator under FCC short- and long-term criteria. Their satellite-selection scheme combines historical primary-link performance with forecasts for the next handover interval.

The resulting policy raises secondary-user throughput by up to 31% compared with approaches based on interference-to-noise limits tuned to meet the same protection requirement. The work translates regulatory rules into handover-time scheduling decisions rather than relying on a static interference threshold.

Source: [arXiv:2611.10462](https://arxiv.org/abs/2611.10462)

## Source Notes

IEEE Xplore and the ACM Digital Library returned no newly indexed papers matching the research topics, so today’s Research Radar uses verified arXiv submissions from the last seven days.

## Takeaway

Today’s strongest advances turn AI and connectivity into deployable infrastructure—cell-aware science, monitorable agents, sovereign private 5G, and regulation-aware LEO systems.
