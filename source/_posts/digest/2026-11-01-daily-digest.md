---
title: "Morning Digest — November 1, 2026"
date: 2026-11-01 07:00:00
tags:
  - AI
  - 6G
  - Cybersecurity
  - NVIDIA
  - Research
categories:
  - Daily Digest
---

Today’s developments show AI moving beyond model releases into developer supply-chain security, infrastructure financing, public administration, edge hardware, and the emerging 6G stack.

## Malicious Claude Code extension planted SSH backdoors

Cursor disclosed that tampered versions 2.1.312 and 2.1.313 of the Anthropic.claude-code extension were distributed through its VS Code Extension Marketplace for roughly 11 hours on October 29. The malicious packages targeted Windows and macOS and attempted to establish persistent SSH access. Cursor removed the versions, revoked the publisher’s access, and published indicators of compromise and remediation instructions. Developers who installed either version should treat the machine as potentially compromised rather than merely updating the extension.

Source: [Cursor security notice](https://cursor.com/blog/claude-code-extension-security-notice)

## T-Mobile says it intends to lead the U.S. into 6G

T-Mobile CTO John Saw told investors that the carrier intends to be first to launch 6G in the United States. The ambition builds on T-Mobile’s spectrum position and its early 5G lead, but the meaningful part is the network direction: future traffic will include more uplink-heavy AI, sensing, wearable, and physical-AI workloads. Saw also rejected speculation that SpaceX could operate as an MVNO on T-Mobile’s network, preserving a clear boundary between their satellite partnership and the carrier’s retail business.

Source: [Light Reading](https://www.lightreading.com/6g/t-mobile-we-ll-be-first-with-6g-and-no-to-spacex-mvno)

## NVIDIA may backstop debt for a massive Anthropic data center

NVIDIA is reportedly in talks to guarantee billions of dollars of debt supporting Nscale’s 460 MW AI data-center campus in West Virginia. Anthropic has committed $44.6 billion for the first building, according to reporting cited by TechCrunch. If completed, the arrangement would deepen a notable industry pattern: chip suppliers are increasingly using investments, financing, and credit support to accelerate the infrastructure purchases that drive demand for their own hardware.

Source: [TechCrunch](https://techcrunch.com/2026/10/30/nvidia-weighs-playing-the-cosigner-for-nscales-ai-data-center-in-west-virginia/)

## OpenAI reportedly trims its fundraising target to $20 billion

OpenAI has reportedly reduced the target for its latest funding round from approximately $30 billion to $20 billion while maintaining a proposed post-money valuation of about $1.25 trillion. The round would still be extraordinary by conventional venture standards, but the lower target suggests that investors are applying more discipline to the enormous capital requirements of frontier-model development and AI infrastructure.

Source: [TechCrunch](https://techcrunch.com/2026/10/31/openai-reportedly-lowers-funding-target-for-new-round/)

## DeepMind expands PlanAssist after a 58% planning-time reduction

Google DeepMind and the UK government are expanding PlanAssist to 12 additional English councils. Built with Gemini, the system automates routine checks for householder planning applications while leaving decisions with human officers. Early pilots in Barnet, Camden, and Dorset reduced time spent on selected assessment work by up to 58%, offering a concrete example of generative AI improving a constrained public-sector workflow rather than simply adding a conversational interface.

Source: [Google DeepMind](https://deepmind.google/blog/speeding-up-planning-decisions-with-ai/)

## Google sunsets Jules and consolidates coding agents around Antigravity

Google is winding down Jules, its autonomous coding agent. Active sessions will end on November 11, when the service becomes read-only, and the product will close fully on December 31. Google says the lessons from Jules will feed into Antigravity, its broader agent-first development platform. The consolidation reflects a maturing coding-agent market in which companies are reducing overlapping surfaces and concentrating execution, context, and tooling in unified environments.

Source: [The Verge](https://www.theverge.com/tech/1022729/google-is-sunsetting-its-ai-coding-agent-jules)

## Qualcomm pushes 24-TOPS edge AI into industrial systems

IMD Technologies has introduced a system-on-module using Qualcomm’s Dragonwing Q-7790 platform, delivering 24 TOPS of local AI performance for robotics, industrial automation, and intelligent vision. The announcement matters less as a single module than as evidence of a broader architectural shift: increasingly capable agents and perception systems are moving onto edge hardware where latency, privacy, bandwidth, and reliability make cloud-only inference impractical.

Source: [Qualcomm](https://x.com/Qualcomm/status/2116334367978983649)

## Research Radar

### True 3D Holography: A Communication Service of Tomorrow and Its Requirements for a New Converged Cloud and Network Architecture on the Path to 6G

Ingo Friese and collaborators examine true 3D holography as a demanding 6G use case. Their proposed architecture tightly integrates wireless access with distributed split computing, arguing that immersive multi-user holographic communication requires not only high capacity and low latency but also a high-speed backbone able to place processing near geographically dispersed users.

Source: [arXiv:2610.40306](https://arxiv.org/abs/2610.40306)

### Sensing Fast and Distant Targets in Overspread Channels with Zak-OTFS and Modular Arithmetic

Andrea Novero, Mudasir Ahmad Sheikh, Danish Nisar, Saif Khan Mohammed, Michele Zorzi, and Robert Calderbank propose two superimposed Zak-OTFS frames that use modular arithmetic to resolve delay-Doppler aliasing in overspread channels. The design targets high-mobility settings including drones, aircraft, LEO satellites, and underwater links; in a 100 km drone scenario, its cross-pilot-cancellation receiver detected 98% of targets versus 81% for the strongest baseline.

Source: [arXiv:2610.39110](https://arxiv.org/abs/2610.39110)

### Keeping Inference in the Radio: Design and Measurement of a Spiking Accelerator for mmWave ISAC Activity Recognition

Anthony Sánchez, Rafael Ruiz, José A. Belloch, Jesús O. Lacruz, and Joerg Widmer move integrated-sensing inference into programmable radio logic. Their 132-neuron spiking accelerator achieved 94.7% accuracy on unseen subjects with 206-microsecond inference, while consuming 3.4 times less dynamic energy per decision than a comparable conventional network receiving the same binary spikes. The result points toward always-on ISAC sensing that can remain active while general-purpose processors sleep.

Source: [arXiv:2610.37480](https://arxiv.org/abs/2610.37480)

## Source notes

IEEE Xplore and ACM Digital Library searches returned no newly indexed matching papers, so this edition’s Research Radar uses verified arXiv records published within the past seven days.

## Takeaway

AI is moving from standalone models into financed infrastructure, public-sector workflows, industrial edge devices, and the radio stack itself—making security and capital discipline just as important as capability.
