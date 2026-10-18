---
title: "Morning Digest — October 18, 2026"
date: 2026-10-18 07:00:00
tags:
  - AI
  - 6G
  - LEO
  - Open RAN
  - NVIDIA
categories:
  - Daily Digest
---

Today’s signal is adaptation across the stack: AI agents are beginning to improve the systems around their models, open-weight releases are targeting full-project execution, and wireless researchers are making RAN policies and beam prediction responsive to changing conditions. At the same time, 6G architecture and satellite-market access remain constrained by standards, spectrum, and regulation.

## Google open-sources Harness² for self-improving agent systems

Google Research released Harness² under Apache 2.0 as a framework for recursively improving the system around a fixed model: prompts, tools, memory, guardrails, skills, scripts, plugins, and subagent orchestration. Its task-level loop proposes harness edits, probes them on the same task, and composes a better configuration; a second loop retains evidence-backed lessons across tasks. Google reports gains of up to 11.5 points on WorkBuddy-Bench, 4.5 points on JobBench, and 11.8 percentage points on LAB partial-pass rate without changing model weights.

Source: [https://github.com/google-research/harness2](https://github.com/google-research/harness2)

## DeepSeek ships V4.1-Flash-1017 with stronger project-building skills

DeepSeek says V4.1-Flash-1017 improves benchmark performance, finishes tasks faster, and produces shorter outputs than the previous release. The model uses reinforcement learning with self-feedback to tackle end-to-end projects such as games and 3D environments, and the weights are available on Hugging Face and ModelScope. DeepSeek also opened its Search and Fetch APIs at $0.75 per 1,000 calls, with temporary free server-side tool use for DeepSeek API customers through October 31.

Source: [https://api-docs.deepseek.com/news/news261017/](https://api-docs.deepseek.com/news/news261017/)

## Claude designs substantially leaner quantum circuits

Anthropic reports that Claude Mythos 5 can turn plain-language objectives into quantum-circuit designs that sometimes improve on the best published circuits by an order of magnitude. Reducing circuit size and resource demands could make useful quantum algorithms in chemistry and materials science more practical, although the claims still need careful independent replication across hardware assumptions and problem families.

Source: [https://www.anthropic.com/research/designing-efficient-quantum-circuits](https://www.anthropic.com/research/designing-efficient-quantum-circuits)

## 6G standards face disputes over spectrum, migration, and AI architecture

Analyst Stéphane Téral says the industry broadly agrees that 6G should evolve from 5G rather than replace it wholesale, retaining technologies such as OFDM and existing channel coding. The harder questions remain unsettled: spectrum positions differ around 4 GHz and 6 GHz, 3GPP has not agreed on every 5G-to-6G migration path, and stakeholders disagree on whether AI should live in a separate domain, inside network functions, or as embedded agents. Those technical arguments are increasingly entangled with geopolitical competition and an unclear commercial case for sensing services.

Source: [https://rcrwireless.com/20261016/6g/6g-standards-teral](https://rcrwireless.com/20261016/6g/6g-standards-teral)

## Starlink says its India infrastructure is approved and launch-ready

Starlink says it has spent more than five years working with Indian regulators and has built dedicated in-country gateways and systems with the necessary government approvals. Commercial launch is not automatic, however: spectrum assignment and final security requirements still matter even after a satellite-communications licence is granted. Reliance Jio Satcom and Eutelsat OneWeb are also waiting on parts of the process, making India a revealing test of how regulators manage competition among terrestrial and LEO connectivity providers.

Source: [https://www.business-standard.com/industry/news/satcom-row-starlink-says-india-infra-has-govt-approvals-ready-for-launch-126101700036_1.html](https://www.business-standard.com/industry/news/satcom-row-starlink-says-india-infra-has-govt-approvals-ready-for-launch-126101700036_1.html)

## Reflection releases Beam with open weights

Reflection made Beam available across platforms under Apache 2.0 with model weights, tokenizer, and reference implementation. The release includes BF16, FP8, and NVFP4 variants plus a DFlash2 drafter for faster decoding, and the company says more than 40 ecosystem partners are participating. The breadth of formats matters because open models increasingly compete on deployability and serving efficiency, not only raw benchmark scores.

Source: [https://x.com/reflection_ai/status/2111079965529968798](https://x.com/reflection_ai/status/2111079965529968798)

## NVIDIA brings zero-trust agent building to Berlin

NVIDIA’s Build-a-Claw event drew more than 500 developers for autonomous-agent demos, talks, and a competition ahead of GTC Berlin. Participants used NVIDIA OpenShell, a containment layer intended to apply zero-trust principles to agent execution. The event leads into Jensen Huang’s October 21 keynote and highlights an increasingly important part of agent infrastructure: restricting tool and system access without eliminating useful autonomy.

Source: [https://blogs.nvidia.com/gtc-berlin-2026-news/](https://blogs.nvidia.com/gtc-berlin-2026-news/)

## Research Radar

### Objective-Aware Policy Orchestration for O-RAN Service Provisioning

Sebastian Racedo, Brigitte Jaumard, Meysam Masoudi, and Oscar Delgado propose selecting among heterogeneous O-RAN provisioning policies according to the current network context and operator objective. Linear Thompson Sampling and a Bootstrap Tree ensemble adapt policy selection over time, improving objective-aware performance over static policies while keeping existing provisioning algorithms modular.

Source: [https://arxiv.org/abs/2610.20949](https://arxiv.org/abs/2610.20949)

### O-RAN-Native Jamming Detection Under Network Heterogeneity

Sneihil Gopal, Fernando J. Cintrón, and Richard A. Rouil evaluate jamming detection using roughly 25 hours of testbed logs from eight heterogeneous 5G environments. Their statistical ensemble can start without labeled data and retains detection capability under distribution shift better than trained ML and deep-learning models, though the tradeoff is more false alarms; its parameter refinement maps naturally to a Non-RT RIC rApp.

Source: [https://arxiv.org/abs/2610.20816](https://arxiv.org/abs/2610.20816)

### Beam-STeP: Generative Site-Specific Beam Prediction with Spatio-Temporal Priors

Ziyue Wang, Zongyao Zhao, Zhaolin Wang, and Yuanwei Liu combine site-specific propagation, mobility information, and prior beam observations in a history-conditioned diffusion model. The model samples multiple future beam candidates and selects the strongest; across three urban simulations, it improves normalized beamforming gain under the same probing budget and exposes a tunable latency-versus-gain tradeoff.

Source: [https://arxiv.org/abs/2610.20282](https://arxiv.org/abs/2610.20282)

## Source notes

Mobile World Live blocked automated retrieval of its AT&T–Amazon Leo report, so it was excluded rather than summarized from a search result. IEEE Xplore returned no newly indexed matching paper from the last seven days, while ACM surfaced the IMC 2026 proceedings but no newly indexed paper aligned with today’s priority topics; the Research Radar therefore uses verified arXiv records.

The common thread is clear: intelligence is migrating from isolated models into the surrounding execution harness, radio controller, and physical-layer prediction loop—but standards, security boundaries, and spectrum policy will determine how quickly those capabilities become dependable infrastructure.
