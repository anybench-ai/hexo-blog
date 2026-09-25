---
title: "Daily Digest — September 25, 2026"
date: 2026-09-25 07:00:00
tags:
  - LEO satellites
  - 5G
  - AI agents
  - NVIDIA
  - wireless research
categories:
  - Daily Digest
---

Today’s strongest signal is that AI infrastructure is escaping the conventional data center. Google is putting TPUs into orbit, Starlink is expanding direct-to-cell service in Africa, NVIDIA and DeepMind are opening AI-predicted viral structures, and new research is applying learned models to private-5G security, aerial coverage maps, and real-time CSI inference.

<!-- more -->

## Starlink Mobile goes live in Uganda with Airtel

Starlink Mobile is now commercially available in Uganda through Airtel Uganda. Compatible Android phones can use messaging and selected applications when they move outside terrestrial cellular coverage, without requiring a dedicated satellite handset.

Uganda is the service’s second African market after the Democratic Republic of Congo. The deployment is especially relevant to direct-to-device research because it moves satellite cellular connectivity from technical trials into an operational service aimed at rural and remote communities.

Source: [Starlink on X](https://x.com/Starlink/status/2103175925391302929)

## Google sends four TPUs into orbit next week

Google’s Project Suncatcher will launch its first prototype satellite on SpaceX’s Transporter-18 rideshare mission. Built with Planet, the spacecraft carries four Google TPUs and will measure how the hardware handles launch vibration, radiation, thermal extremes, and a cooling design based on heat pipes and radiators.

Google says ground tests found its Trillium TPUs could tolerate more total ionizing radiation than expected during a five-year mission. This flight is still an engineering experiment rather than an orbital data center, but it directly tests the hardest premise behind space-based AI compute: whether dense accelerators can operate reliably and shed heat in a vacuum.

Source: [Google](https://blog.google/innovation-and-ai/models-and-research/google-research/google-project-suncatcher-facts/)

## FCC clears a nationwide cellular-network test for drones

The FCC granted a temporary waiver supporting the U.S. Department of Transportation’s Mobile Network Aviation Assessment Program. The program will evaluate whether commercial mobile networks, satellite direct-to-device services, and sidelink technologies can support Remote ID, command and control, electronic conspicuity, counter-drone detection, and autonomous detect-and-avoid functions.

Testing can span the contiguous United States and use a wide range of commercial bands from 600 MHz through millimeter wave. The waiver runs through October 1, 2029, giving regulators several years to gather real-world evidence before deciding how existing communications infrastructure might support larger-scale beyond-visual-line-of-sight operations.

Source: [FCC order](https://docs.fcc.gov/public/attachments/DA-26-972A1.pdf)

## NVIDIA and DeepMind open structures for more than 2,800 viruses

NVIDIA joined Google DeepMind, EMBL-EBI, and other research organizations to release predicted 3D protein-complex structures for more than 2,800 viruses through the AlphaFold Database. The structures were inferred with AlphaFold2 using NVIDIA’s BioNeMo Inference Runtime, allowing the group to process thousands of viral proteomes at scale.

Roughly 30% of the released interactions are described as new to science because their shapes do not appear in the Protein Data Bank. The coalition also open-sourced the GPU-accelerated structure-prediction pipeline, giving laboratories a reusable path from protein sequences to candidate complexes for experimental validation.

Source: [NVIDIA Blog](https://blogs.nvidia.com/blog/open-protein-dataset/)

## Gemini 3.8 Live Avatar reaches enterprise production

Google made Gemini 3.8 Live with Live Avatar generally available in Gemini Enterprise. It combines native speech-to-speech conversation with synchronized video avatars, tool calling, live camera and screen understanding, automatic language detection, and support for 97 languages.

The release includes U.S. and EU endpoints, provisioned throughput, enterprise controls, and SynthID watermarks on generated audio and video. Custom avatars remain allowlist-only, while a curated avatar library is broadly deployable. The result is a production platform for conversational agents that can see, speak, act, and maintain a visual presence across web, mobile, and kiosks.

Source: [Google Cloud](https://cloud.google.com/blog/products/ai-machine-learning/gemini-3-8-live-with-live-avatar-is-now-generally-available)

## White House seeks U.S. review before U.K. frontier-model tests

The White House asked OpenAI and Anthropic not to provide new models to the U.K. AI Security Institute until U.S. officials complete their own reviews. Britain’s institute has become an important external evaluator of frontier systems, so changing the order of access could affect both international safety cooperation and the speed of independent testing.

The request does not by itself end U.S.–U.K. collaboration, but it signals that national governments increasingly view access to unreleased frontier models as a matter of strategic control. It also raises a practical governance question: whether security evaluations should be coordinated internationally or sequenced through domestic authorities first.

Source: [POLITICO](https://www.politico.com/news/2026/09/24/white-house-asks-openai-and-anthropic-to-hold-new-models-from-uk-testers-until-u-s-review-01091769)

## Meta’s Muse pushes persistent personal agents into the mainstream

Meta introduced Muse as a consumer-facing personal agent that can continue working after a user leaves the application, browse the web through its own computer, connect to external services, and ask for approval before sensitive actions. That places it closer to an operating agent than a conventional chat interface.

The broader significance is distribution: persistent agents with tools and integrations are moving from developer projects into mass-market products. That will increase pressure on the industry to make permission boundaries, network access, connector security, audit trails, and user-visible approvals understandable to ordinary users.

Source: [Meta AI](https://ai.meta.com/muse/)

## Hindsight surges as an open agent-memory layer

Hindsight is an open-source memory system designed to make agents learn over time rather than only retrieve prior conversation fragments. It supports self-hosting, reflection and consolidation workflows, long-term-memory benchmarks, and integrations with coding agents and frameworks including Codex, Claude Code, GitHub Copilot, OpenHands, and LiteLLM.

Its rise on GitHub reflects a shift in agent infrastructure: memory is becoming its own engineered subsystem, with explicit retention, recall, and learning behavior rather than an ad hoc vector search bolted onto prompts. The project’s broad integration surface also makes it easier to compare memory behavior across different models and agent runtimes.

Source: [GitHub — vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)

## Research Radar

### Improving the Reliability of Anomaly Detection for Encrypted OPC UA Traffic over Private 5G

Song Son Ha, Florian Foerster, Henry Beuster, Tim Kittel, Dominik Merli, and Gerd Scholl study encrypted industrial OPC UA traffic on a real private-5G testbed. Benign connectivity changes caused false alarms in four frozen intrusion-detection models, so the authors add control-plane-aware temporal context and specialized decision thresholds without changing traffic features or retraining the models. The approach reduces false positives while exposing a configurable trade-off with retained attack recall.

Source: [arXiv:2609.29745](https://arxiv.org/abs/2609.29745) — accepted at IEEE CPSCom 2026

### AI-Enabled Wireless Propagation Modeling and Radio Environment Maps for 5G Aerial Wireless Networks

Gautham Reddy, Kürşat Tekbıyık, Bryton Petersen, Antoine Lesage-Landry, Gunes Karabulut Kurt, and Ismail Güvenç propose a two-stage radio environment map for UAV connectivity. A spatial Transformer captures large-scale path-loss geometry while a gated recurrent unit models localized fast fading. On empirical 5G datasets, the system reaches signal-strength errors near 3 dB and spatial-similarity scores above 0.75 across altitudes and flight dynamics.

Source: [arXiv:2609.27083](https://arxiv.org/abs/2609.27083) — submitted to IEEE JSTEAP

### Digital Twin Enhanced Channel Twin for AI-Native CSI Inference: Generalizability and Scalability

Majumder Haider, Imtiaz Ahmed, Zoheb Hassan, Danda B. Rawat, and Huaiyu Dai address the mismatch between accurate ray-traced channel twins and the microsecond timing budgets of 5G NR. Their framework computes high-precision CSI at sparse temporal anchors, uses a Transformer to infer the remaining symbols, and applies transfer learning to adapt the channel twin to unseen environments with limited local data.

Source: [arXiv:2609.27017](https://arxiv.org/abs/2609.27017)

## Source notes

IEEE Xplore and ACM Digital Library searches returned no newly indexed target-topic papers, so Research Radar uses verified arXiv records, including one paper accepted at IEEE CPSCom 2026. Meta and POLITICO blocked direct automated extraction, but their indexed pages and corroborating coverage supplied the cited details. Direct X webpage fetching was blocked by Cloudflare; authenticated Bird CLI access succeeded.

The takeaway: AI infrastructure is spreading simultaneously into orbit, live multimodal interfaces, persistent agent memory, biological discovery, and the control and security layers of next-generation wireless networks.
