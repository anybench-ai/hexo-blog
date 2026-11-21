---
title: "Daily Digest — November 21, 2026"
date: 2026-11-21 07:00:00
categories: [Digest, Technology]
tags: [5G, 6G, satellite, AI, semiconductors, O-RAN]
---

China's industrial 5G buildout, a terrestrial-to-satellite mobility test, and Nokia's AI-native radio platform lead a morning in which connectivity and compute are becoming more programmable at the same time.

<!-- more -->

## China passes 26,000 private industrial 5G networks

China has built more than 26,000 private industrial 5G networks nationwide, according to CCTV reporting cited by Bloomberg. The deployment base now reaches manufacturing at a scale large enough to turn private cellular from a collection of pilots into production infrastructure.

The same report says Chinese researchers are testing 6G's ability to sense moving objects, with autonomous driving among the possible applications. That pairing—industrial connectivity today and integrated sensing tomorrow—shows how the 5G-to-6G transition may happen through operational upgrades rather than a clean generational break.

Source: [Bloomberg](https://www.bloomberg.com/news/articles/2026-11-21/china-deploys-5g-across-manufacturing-base-as-6g-testing-advances-cctv-reports)

## AT&T, AST SpaceMobile and Nokia demonstrate seamless terrestrial-to-satellite handoff

AT&T, AST SpaceMobile, and Nokia report that they successfully handed an active user session between terrestrial coverage and AST's direct-to-device satellite network—and back again. Preserving both connectivity and application state is essential if satellite coverage is to feel like an extension of a mobile network instead of a separate emergency mode.

The test is especially relevant to FirstNet, where users may move rapidly across coverage boundaries while relying on active public-safety applications. The partners expect satellite direct-to-device service to support those users next year.

Source: [Urgent Communications](https://urgentcomm.com/satellite-direct-to-device/at-t-ast-spacemobile-test-terrestrial-satellite-d2d-handoff)

## Nokia unveils an AI-native RAN with a software path to 6G

Nokia describes its AI-RAN as a common programmable platform for 5G and 5G-Advanced with an upgrade path to 6G and O-RAN compliance. Operators can add acceleration to existing AirScale basebands, deploy dedicated AI-RAN nodes, or run the cloud-native stack on commercial servers.

The company says AI-driven radio innovations have already demonstrated efficiency gains above 20%, with advanced models and accelerated computing intended to push spectral efficiency beyond twice that of conventional architectures. The strategic shift is that radio improvement increasingly arrives through software and models rather than only through a hardware refresh.

Source: [Nokia](https://www.nokia.com/radio-access/ai-ran/)

## Google opens Genie 4 world simulation to developers

Google has made Genie 4 available through the Gemini Interactions API and Google AI Studio. From text, a reference image, or both, it streams continuous interactive worlds at 720p and 24 frames per second with synchronized ambient sound, effects, and dialogue.

Developers can navigate with keyboard controls and alter lighting, weather, objects, or events through live prompts while Gemini reasoning maintains the world's state. Google positions the model for interactive prototyping, spatial design, and environments used to train robotics or AI agents; outputs carry SynthID watermarking.

Source: [Google](https://blog.google/innovation-and-ai/technology/developers-tools/genie-4-in-gemini-api/)

## Tencent releases the open weights for Hy4 Flash

Tencent's Hy4 Flash is a multimodal mixture-of-experts model with 220 billion total parameters, including 64 billion Engram parameters, while activating only about 12 billion parameters per token. It accepts text and images, produces text, and supports contexts up to one million tokens.

The architecture combines sparse and sliding-window attention, 512 routed experts, learned bigram and trigram representations, and a built-in 0.85-billion-parameter DFly2 drafter for speculative decoding. Tencent has published standard, base, and quantized deployment resources for local inference and further training.

Source: [Tencent on Hugging Face](https://huggingface.co/tencent/Hy4-flash)

## OpenAI reports a sharp reduction in reasoning-extraction attacks

OpenAI published its approach to adversarial distillation: attempts to reproduce frontier capabilities without the safeguards wrapped around the original model. Its defenses combine adversarial training, request and response classifiers, API restrictions, automated red-teaming, account-level investigations, and campaign enforcement.

In an internal adaptive evaluation, OpenAI says the average success rate for extracting protected reasoning fell from 54.0% against GPT-6 Astra with its original safeguards to 0.2% against GPT-6.2 Astra. The accompanying experiments also suggest that exact reasoning traces can transfer more cyber capability to a student model than summaries, making trace protection a safety issue beyond intellectual property.

Source: [OpenAI](https://openai.com/index/combatting-adversarial-distillation/)

## U.S. extends advanced-chip controls to remote data-center access

The Commerce Department's Bureau of Industry and Security has issued an interim final rule covering remote access to advanced computing. Overseas data centers that supply significant U.S.-technology compute to companies headquartered in Country Group D:5 or Macau now face restrictions and expanded customer due diligence.

The rule also adds licensing requirements for advanced chips sent to Indonesia, Malaysia, Singapore, Thailand, and Brazil because of diversion risk, narrows some foundry and packaging pathways, and formally rescinds the never-enforced AI Diffusion Rule. It took effect November 19, with comments due January 19, 2027.

Source: [Federal Register](https://www.federalregister.gov/documents/2026/11/19/2026-23529/addressing-remote-access-to-advanced-semiconductors)

## Canva adds user controls to switch generative AI off

Canva has introduced two controls for Free and Pro users: one disables generative AI features, while the other reduces AI-generated material shown in Canva's content library. The controls bring an individual-user choice to a category that has often been managed only through organization-level settings.

The move is notable because it treats the amount of generative content in a creative tool as a preference rather than an unavoidable product direction. It may also set a useful precedent for other productivity platforms embedding AI throughout their interfaces.

Source: [Canva](https://www.canva.com/newsroom/news/ai-controls-canva/)

## Research Radar

### An LLM-Driven Traffic-Control xApp for Dynamic 5G RAN Intents

Valerio Triolo, Luca Valcarenghi, and Emilio Paolini combine operator intents, live E2 telemetry, and the deployed configuration in an LLM-controlled xApp. In an OpenAirInterface testbed, the system reached 0.91 average intent satisfaction versus 0.52 for a static TC-RAN setup, and remained near 0.88 as channels degraded.

Source: [arXiv](https://arxiv.org/abs/2611.25736)

### Benchmarking Open-Source O-RAN and 5G NTN Stacks on Embedded ARM Platforms for Space Payloads

Esteban Municio and colleagues benchmark OpenAirInterface/Duranta, srsRAN/OCUDU, the O-RAN Software Community near-real-time RIC, and FlexRIC on ARMv8 hardware representative of small-satellite payloads. Every examined combination could host a joint gNB and near-RT RIC, but performance and standards compliance varied enough to require mission-specific selection and more work before carrier-grade flight use.

Source: [arXiv](https://arxiv.org/abs/2611.25206)

### Software-Defined Internet Integration of Satellite Networks

Michael Menth, Moritz Flüchter, and Jens Haala propose SDISN, an architecture in which a controller continually updates forwarding as user terminals and gateways change serving satellites. Keeping terminals out of the routing system reduces onboard complexity and improves compatibility, while alternative gateways and serving satellites provide traffic-engineering and latency options.

Source: [arXiv](https://arxiv.org/abs/2611.25837)

## Source notes

Bloomberg, Urgent Communications, and Canva blocked direct text extraction, so their details were cross-checked against indexed results. IEEE Xplore and the ACM Digital Library returned no newly indexed eligible wireless papers; the research section uses arXiv records submitted November 18–19.

## Takeaway

AI-native radio, terrestrial-satellite mobility, interactive world models, and compute export controls are converging around one contest: who can turn scarce infrastructure into programmable capability fastest.
