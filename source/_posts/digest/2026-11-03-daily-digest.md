---
title: "Morning Digest — November 3, 2026"
date: 2026-11-03 07:00:00
tags:
  - AI
  - 6G
  - satellites
  - wireless
  - research
categories:
  - Daily Digest
---

Today's strongest signal is systems integration: seamless satellite handoffs, AI-native radio control, compute-access policy, and robotics security increasingly matter as much as raw model or link performance.

## AST SpaceMobile highlights terrestrial-to-satellite handoff work with AT&T

AST SpaceMobile published a new look at its engineering work with AT&T on handoffs between terrestrial cellular coverage and space-based broadband. Handoff reliability is one of the central systems problems in direct-to-device service: a useful network must preserve sessions as ordinary phones move between ground infrastructure and rapidly changing satellite coverage, not merely demonstrate an isolated satellite link.

Source: [AST SpaceMobile and AT&T on engineering handoffs](https://x.com/AST_SpaceMobile/status/2117301012750901466)

## Nokia and Elisa widen their AI-RAN collaboration

Nokia and Finnish operator Elisa are exploring AI-RAN alongside AI education and new communications experiences. The partnership adds another operator-backed test bed for combining radio workloads and AI compute, and it provides a path for evaluating whether AI-native network ideas create practical customer value rather than remaining platform demonstrations.

Source: [Nokia on its collaboration with Elisa](https://x.com/nokia/status/2117539219501441341)

## NVIDIA reportedly limits how much cloud capacity can serve Chinese buyers

NVIDIA has reportedly told cloud and data-center customers that at least 51% of services built on its chips must be sold to non-Chinese companies. The measure targets a growing export-control workaround in which restricted customers rent advanced accelerators located outside China. If broadly enforced, the rule would turn NVIDIA's partner contracts into another layer of geopolitical compute governance.

Source: [Bloomberg report on NVIDIA's cloud-client restrictions](https://www.bloomberg.com/news/articles/2026-11-03/nvidia-tells-data-center-clients-to-trim-china-business-ft-says)

## Anthropic's amended IPO filing exposes the scale of the AI infrastructure race

Anthropic's amended S-1 reports $33.24 billion in revenue for the first nine months of 2026, up roughly 1,200% year over year. It also discloses about $895.4 billion in purchase commitments and leases, substantially all related to compute and infrastructure. The company recorded a $104 billion net loss over the period, although much of it reflects changes in the fair value of convertible notes and derivative liabilities. The filing makes the central tradeoff unusually visible: extraordinary demand paired with extraordinary capital and capacity requirements.

Source: [Anthropic amended Form S-1/A](https://www.sec.gov/Archives/edgar/data/2130357/000162828026068676/anthropicpbc-sx1ax1.htm)

## AI-assisted research surfaces 28 potential robotics zero-days

VicOne says AI-assisted research found 28 previously unknown vulnerabilities across software and tools associated with Google, NVIDIA, Meta, and other physical-AI projects in under two days. The findings still await vendor and vulnerability-authority review, and some lack CVE identifiers, so the count should be treated as preliminary. Still, the distribution is notable: 75% involved development, training, simulation, or validation tools, showing how robot safety can be undermined before deployment through poisoned models, compromised simulations, or misleading test evidence.

Source: [The Robot Report on VicOne's robotics findings](https://www.therobotreport.com/28-zero-day-findings-in-less-than-two-days-what-ai-speed-discovery-means-for-robotics/)

## Amazon Leo schedules a 40-satellite Vulcan mission

United Launch Alliance is targeting November 13 for a Vulcan mission carrying 40 Amazon Leo broadband satellites from Cape Canaveral. The flight will add another batch of production spacecraft as Amazon works toward service availability, while also marking an important return-to-flight milestone for Vulcan after a booster-related pause.

Source: [Amazon Leo to launch 40 satellites on November 13](https://broadbandbreakfast.com/amazon-leo-to-launch-40-more-broadband-satellites-nov-13/)

## OpenBMB open-sources a compact OCR-and-verification pair

OpenBMB's MiniCPM-OCR release pairs a 1.3-billion-parameter document parser with MiniCPM-OCR Jev, a 2-billion-parameter model designed to check whether parsing results are correct. Separating extraction from verification is a useful design choice for document pipelines because it adds an explicit quality-control stage while keeping both models small enough for comparatively modest hardware.

Source: [OpenBMB MiniCPM-V repository and MiniCPM-OCR release](https://github.com/OpenBMB/MiniCPM-V)

## Andrej Karpathy builds HackerTube from 20 years of Hacker News comments

Andrej Karpathy used an AI coding agent to filter 43 million Hacker News comments into a catalog of 6,454 repeatedly recommended videos. The login-free site stores state locally and replaces engagement-optimized thumbnails with representative video frames. More than the recommendation site itself, the project is a compact example of agentic development collapsing data processing, product implementation, infrastructure hardening, and deployment into a weekend workflow.

Source: [Andrej Karpathy's HackerTube project thread](https://x.com/karpathy/status/2116957135661945283)

## Research Radar

### From Reactive to Agentic Resilience: Multi-Timescale AI-RAN Orchestration Under Signaling Storms

Sotiris Chatzimiltis, Mahdi Boloursaz Mashhadi, Mohammad Shojafar, and Rahim Tafazolli propose a three-tier Open RAN control architecture that keeps slow language-model reasoning away from the fast control loop. In signaling-storm simulations, an agent anticipated scheduled crowds and approached the resilience of a fully provisioned server pool with only one-quarter of its capacity; unseen free-text operator intents mapped to control directives at 94% exact match.

Source: [arXiv:2611.03406](https://arxiv.org/abs/2611.03406)

### Joint Delay--Doppler Modeling of Multipath LEO Channels

Kuan-Po Chiu and Sumit Roy introduce a geometry-based stochastic model for jointly generating delay, Doppler, power, and time-varying channel impulse responses over a LEO pass. Its omnidirectional results broadly track 3GPP NTN behavior, but beamforming creates a mid-elevation K-factor peak not predicted by TR 38.811, highlighting a modeling gap relevant to 6G NTN evaluation.

Source: [arXiv:2611.02350](https://arxiv.org/abs/2611.02350)

### AI-Aided and AI-Oriented Integrated Sensing, Communication, and Computation: A Survey

Yaya Etiabi, Wessam Ajib, El Mehdi Amhoud, and Halima Elbiaze organize ISCC research around two complementary roles: AI as a tool for optimizing sensing, communications, and computation, and integrated networks designed around the needs of learning and inference workloads. The survey compares architectures, metrics, and evaluation practices while identifying open problems in scalable and trustworthy co-design.

Source: [arXiv:2611.01521](https://arxiv.org/abs/2611.01521)

## Source Notes

IEEE Xplore and ACM Digital Library searches returned no newly indexed matching papers, so today's Research Radar uses verified arXiv records.

## Takeaway

The competitive frontier is shifting from isolated AI models and radio links toward integrated systems where compute access, network orchestration, satellite handoffs, and software security determine real-world performance.
