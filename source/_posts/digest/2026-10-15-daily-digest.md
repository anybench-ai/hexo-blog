---
title: "Morning Digest — October 15, 2026"
date: 2026-10-15 07:00:00
categories: [Daily Digest]
tags: [AI, 5G, 6G, LEO, NVIDIA, networking, semiconductors, research]
---

Programmable infrastructure is today’s common thread. LEO access is expanding, Nokia is placing a high-stakes bet on GPU-based radio networks, carriers are prioritizing autonomy, and AI agents are moving from enterprise software into semiconductor design and manufacturing.

<!-- more -->

## Starlink goes live in Curaçao

Starlink has begun commercial service in Curaçao, extending its low-latency LEO broadband footprint into another Caribbean market. The launch follows the island government’s recent telecom concession and gives homes and businesses a satellite alternative where terrestrial backhaul and island geography can constrain competition. It is a geographically modest expansion, but each new licensed market strengthens the operational reach of a constellation increasingly positioned as both consumer broadband and emergency-connectivity infrastructure.

Source: [Starlink](https://x.com/Starlink/status/2110410786925641854)

## Nokia bets its 6G RAN roadmap on NVIDIA GPUs

Nokia is preparing NVIDIA GPU-based AI-RAN products for commercial availability early next year and has stopped developing new custom RAN silicon with Marvell, though existing 4G and 5G systems will remain supported. The company argues that a software-upgradable GPU platform can run more advanced signal-processing algorithms and potentially double spectral efficiency by 2028. The wager is consequential: operators must accept new hardware, tight CUDA dependence, and unresolved power and cost questions in exchange for a more programmable path into 5G-Advanced and 6G.

Source: [Light Reading](https://www.lightreading.com/5g/nokia-to-start-dealing-out-gpus-in-high-stakes-ai-ran-gamble)

## Ericsson returns to organic growth as operators seek autonomous networks

Ericsson reported third-quarter sales of SEK 59.5 billion, up 6% as reported and 7% organically, with Networks providing the main lift. Adjusted EBITA reached SEK 10.1 billion and net income was SEK 5.8 billion. New CEO Per Narvinger says customers consistently emphasized intelligent and autonomous networks that improve efficiency, resilience, and performance. That demand is strategically encouraging, although Ericsson still describes the RAN market as flat and expects higher component costs to pressure margins next year.

Source: [Ericsson / PR Newswire](https://www.prnewswire.com/news-releases/ericsson-reports-third-quarter-results-2026-302909534.html)

## More than half of OpenAI’s EU business usage is now agentic

OpenAI’s Economic Research team says Codex and ChatGPT Work now account for more than half of output tokens among sampled EU Enterprise and Business customers. Weekly active users of those tools at small and medium businesses have grown more than eightfold since May, but adoption is uneven: agentic output ranged from 22% of sampled usage in Slovenia to 85% in Lithuania. The report’s more important warning is depth—Europe’s most intensive AI users still generate less than half the output per active user of frontier firms outside the EU.

Source: [OpenAI](https://openai.com/index/the-eus-next-chapter-in-ai-is-agentic/)

## Anthropic opens in Singapore and signs a government AI-safety pact

Anthropic opened its fifth Asia-Pacific office in Singapore and signed an MOU with the Ministry of Digital Development and Information. Planned cooperation covers model evaluation, testing standards, incident response, adoption research, workforce skills, and responsible public- and private-sector deployment. Singapore already ranks second among 121 countries in Claude usage relative to population, while more than 1,500 GovTech engineers use Claude Code. The agreement makes the city-state both a commercial hub and a live test bed for safety-oriented frontier-AI governance.

Source: [Anthropic](https://www.anthropic.com/news/singapore-office-opening)

## NVIDIA brings agents and accelerated simulation into chip fabs

NVIDIA introduced cuPotential, a CUDA-X library for atomic-scale simulation, and expanded the accelerated software stack used by semiconductor designers and manufacturers. Early-access tests show cuPotential adding a further 2–3× speedup to workflows already optimized for GPUs; NVIDIA also cites partner results including 30× simulation gains with NanoVDB and sizable acceleration in Synopsys and Cadence engineering workloads. The larger ambition is an AI-defined fab where agents can run simulations, inspect defects, test process changes in digital twins, and help engineers improve yield before touching a production line.

Source: [NVIDIA](https://nvidianews.nvidia.com/news/nvidia-and-semiconductor-leaders-advance-ai-across-chip-design-and-manufacturing-for-ai-defined-labs)

## Research Radar

### Opportunities for Direct-to-Cell Polarization MIMO in the S-band Downlink of a LEO Satellite Footprint

Rainer Bachl, Matteo Ferro, Bingguang Peng, and Muhammad Nabeel investigate whether a LEO satellite’s two polarizations can carry a second spatial layer to ordinary handsets, a capability current 5G NR NTN does not exploit. In a modeled 330-km-altitude S-band footprint over Munich, closed-loop precoding selected rank two for 99% of a nadir-track pass and increased mean spectral efficiency across the footprint by 49% at 13 dB SNR. The result identifies polarization as a practical capacity lever for direct-to-cell systems without requiring multiple satellites for spatial multiplexing.

Source: [arXiv:2610.20296](https://arxiv.org/abs/2610.20296)

### Hardware-friendly Baseband Design and Performance Analysis for LEO Broadband LoS-MIMO Systems

Peixin Zhang, Fengkui Gong, Guo Li, and Tony Q. S. Quek propose an OFDM transceiver for line-of-sight MIMO links affected by oscillator and timing errors. Subband-adaptive truncation, dynamic timing recovery, and coding-and-modulation scheduling jointly avoid outages caused by spatial notches. Simulations place the potential average throughput of a single dual-polarized beam above 100 Gbps, offering a relatively low-complexity baseband route toward next-generation high-throughput satellites.

Source: [arXiv:2610.19639](https://arxiv.org/abs/2610.19639)

### On the Investigation of Antenna Beam Pattern Models for Fast Beam Placement in LEO Satellite Networks

Ninh Thi-Thanh Tam, Nguyen Viet Anh, Nguyen Minh Quan, and Trinh Van Chien compare Bessel, combined Bessel, Gaussian, and 3GPP antenna patterns in a graph-based LEO beam-placement framework. Their results show that the assumed pattern changes active-beam counts, load balance, channel-gain statistics, SINR, and spectral efficiency. The ATC 2026 paper is a useful warning for system studies: antenna modeling is not a cosmetic choice when evaluating placement and interference-management algorithms.

Source: [arXiv:2610.18930](https://arxiv.org/abs/2610.18930)

## Source notes

IEEE Xplore returned no newly indexed target-topic papers from the last seven days. ACM search surfaced the IMC 2026 proceedings but no newly indexed paper matching today’s research priorities, so Research Radar uses verified arXiv submissions. Mobile World Live blocked automated retrieval, so its Amazon Leo–AT&T item was excluded rather than summarized from a search snippet alone.

Today’s strongest signal is that connectivity and compute are becoming programmable at every layer—from satellite access and radio basebands to enterprise workflows and semiconductor fabs.
