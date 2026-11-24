---
title: "Daily Digest — November 24, 2026"
date: 2026-11-24 07:00:00
tags:
  - AI
  - 6G
  - LEO
  - Wireless
  - Cybersecurity
categories:
  - Daily Digest
---

Today’s strongest theme is operational AI: systems are leaving the demo layer and taking on concrete work in security, scientific design, and the radio stack. In parallel, direct-to-device trials and a successful Amazon Leo launch show non-terrestrial connectivity progressing at both the handset and constellation layers.

## Ariane 6 launches 36 Amazon Leo satellites after one-day delay

Ariane 6 Flight VA271/LE-04 lifted off early Tuesday and deployed 36 Amazon Leo broadband satellites. The successful flight is a genuine update to yesterday’s scrub, which followed a technical event in the launcher’s ground-support systems.

For Amazon, every deployment matters because its constellation rollout is working against a demanding schedule and recent launch setbacks. For Europe, the mission also adds another commercial success for the Ariane 64 configuration.

Source: [https://www.space.com/space-exploration/launches-spacecraft/arianespace-ariane-6-amazon-leo-internet-satellite-launch](https://www.space.com/space-exploration/launches-spacecraft/arianespace-ariane-6-amazon-leo-internet-satellite-launch)

## Smart and Elveo complete phone-to-satellite tests on a Philippine sea route

Smart Communications and Elveo Mobile tested direct-to-device satellite connectivity along the maritime route between Batangas and Calapan. Ordinary LTE smartphones connected directly to Elveo’s LEO satellites without specialized external antennas or satellite terminals.

The trial covered two-way text messages, emergency broadcasts, and voice calls. Maritime corridors are a valuable D2D test case because they expose the coverage gap between terrestrial cells while tying the technology to practical safety and continuity needs.

Source: [https://www.prnewswire.com/news-releases/smart-and-elveo-mobile-successfully-test-direct-to-device-satellite-connectivity-on-key-philippine-sea-route-302947592.html](https://www.prnewswire.com/news-releases/smart-and-elveo-mobile-successfully-test-direct-to-device-satellite-connectivity-on-key-philippine-sea-route-302947592.html)

## ZTE dual-band radio doubles 2.6 GHz traffic in Thailand field tests

TRUE has commercially deployed ZTE’s customized A9651D M2326 active antenna unit, which integrates 2.3 GHz and 2.6 GHz TDD operation in one radio. Joint field tests reported a 116% improvement in 2.6 GHz traffic and 1.7 Gbps throughput using standalone-5G carrier aggregation.

The deployment also reduced the number and weight of radio-frequency units, illustrating how radio consolidation can improve performance while simplifying crowded sites and lowering resource demands.

Source: [https://www.marketscreener.com/news/zte-unveils-customized-tdd-dual-band-aau-deployed-in-true-s-network-in-thailand-ce7851dad889f226](https://www.marketscreener.com/news/zte-unveils-customized-tdd-dual-band-aau-deployed-in-true-s-network-in-thailand-ce7851dad889f226)

## OpenAI and Cisco open-source live Linux defenses with Shirudo

OpenAI and Cisco introduced Shirudo, an open-source Linux runtime that lets defensive agents create dynamic eBPF controls to shield running systems from exploits. The controls can be loaded without a reboot, giving operators time to test and roll out a permanent patch without taking services offline.

The deployment design includes cryptographic signing, eBPF verifier checks, and kernel controls. That matters because AI-generated defenses need a trust and rollback model as much as they need speed.

Source: [https://openai.com/index/introducing-shirudo/](https://openai.com/index/introducing-shirudo/)

## GPT-6 Cyber validates 948 Linux kernel root-access bugs in one run

OpenAI reported that GPT-6 Cyber validated 948 Linux kernel bugs capable of granting local root access in a single run. The system reproduced vulnerabilities in isolated virtual machines and generated candidate patches for human and maintainer review.

The result suggests vulnerability research may scale faster than existing review and upstreaming processes. The operational bottleneck could move from finding bugs to triaging evidence, validating patches, and safely coordinating disclosure.

Source: [https://x.com/OpenAI/status/2125007927098699827](https://x.com/OpenAI/status/2125007927098699827)

## Gemini agent teams design formally verified quantum circuits

Google DeepMind used teams of Gemini 4 agents to optimize well-known quantum algorithms. Agents worked in parallel, periodically debated candidate ideas, and used the Lean proof assistant to verify that circuit transformations preserved correctness.

DeepMind reports that the resulting circuits could cut some future simulation costs by up to ten times. It also released its verified solutions and Lean library, making the claims more inspectable than an unverified agent-generated optimization.

Source: [https://deepmind.google/blog/finding-faster-quantum-algorithms-with-agents-and-formal-verification/](https://deepmind.google/blog/finding-faster-quantum-algorithms-with-agents-and-formal-verification/)

## NVIDIA reinstates Jensen Huang as CEO and board director

NVIDIA’s board reinstated Jensen Huang as president, chief executive officer, and board director effective immediately. The decision reverses a leadership disruption at a company whose roadmap and ecosystem remain unusually closely associated with its founder.

The immediate announcement provides continuity, but NVIDIA will still face close attention around governance, regulatory pressure, and execution across its expanding AI infrastructure portfolio.

Source: [https://nvidianews.nvidia.com/news/nvidia-board-reinstates-jensen-huang-as-president-ceo-and-board-director](https://nvidianews.nvidia.com/news/nvidia-board-reinstates-jensen-huang-as-president-ceo-and-board-director)

## Research Radar

### G-Wave: Bit-to-Waveform Generation for Adaptive Wireless Communications

Hanwen Zhang, Yunfang Leng, Zheng Shi, Bo Yuan, Zhenlin An, and Haijian Sun propose a channel-conditioned generative transceiver that synthesizes physical time-domain waveforms directly from bits. Across evaluated 3GPP environments, G-Wave reduced mean bit-error rate by 42.4% against DeepOFDM and 72.6% against conventional OFDM under estimated channel information.

Source: [https://arxiv.org/abs/2611.29885](https://arxiv.org/abs/2611.29885)

### Angular attenuation and temporal dispersion from a winter deciduous bush at FR2

Tomasz Grasza and collaborators measured a single leafless bush at 28 and 38 GHz using a wideband channel sounder and directional antennas over reception angles from 0 to 200 degrees. The results show substantial angular variability in excess attenuation and delay dispersion, providing useful measurement evidence for sparse-vegetation FR2 models.

Source: [https://arxiv.org/abs/2611.30431](https://arxiv.org/abs/2611.30431)

### Chance-constrained beam hopping and bandwidth allocation for LEO satellites

Olfa Ben Yahia and collaborators formulate LEO beam hopping as an SLA-aware chance-constrained optimization problem. By modeling spectral-efficiency prediction errors, the approach explicitly targets a probability of satisfying each cell’s demand while jointly allocating beam schedules and bandwidth.

Source: [https://arxiv.org/abs/2611.26270](https://arxiv.org/abs/2611.26270)

## Source notes

IEEE Xplore and ACM Digital Library searches returned no newly indexed eligible wireless papers, so the Research Radar uses verified arXiv records submitted November 19–23. ZTE’s primary release was not indexed by search; the Thailand deployment figures were verified through a syndicated copy of the company announcement.

The practical takeaway: AI agents are gaining the guardrails and formal verification needed to touch production systems, while wireless and LEO infrastructure keeps converting laboratory capability into field deployments.
