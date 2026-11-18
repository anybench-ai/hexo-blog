---
title: "Morning Digest — November 18, 2026"
date: 2026-11-18 07:10:00
tags:
  - AI
  - 6G
  - LEO Satellites
  - Telecom
  - NVIDIA
categories:
  - Daily Digest
---

Today's news is unusually coherent: companies are integrating every layer of the stack, from satellite access and radio spectrum to frontier models, accelerators, packaging, and enterprise-agent platforms.

<!-- more -->

## Iridium activates standards-based global NB-IoT from space

Iridium has activated NTN Direct across its operational LEO constellation. The service uses 3GPP-standard NB-IoT and direct-to-device connectivity, extending low-power links beyond terrestrial mobile coverage with global reach.

The immediate engineering significance is compatibility. Nordic Semiconductor's nRF9151 is the first approved module, and a firmware update planned for January 2027 will let existing devices add satellite support without new hardware. Iridium is also working with Altair, Deutsche Telekom IoT, Mlink, and Vodafone IoT on commercial integrations.

Source: [Iridium / PR Newswire](https://www.prnewswire.com/news-releases/iridium-activates-iridium-ntn-direct-worlds-first-standards-based-nb-iot-and-d2d-service-with-truly-global-coverage-302941447.html)

## T-Mobile seeks 58 more 600 MHz licenses

T-Mobile has filed with the FCC to acquire 58 low-band licenses from Bluewater Wireless. The licenses cover 435 counties across 27 states and would generally add 10 MHz to T-Mobile's holdings, with 20 MHz additions in parts of Colorado and South Carolina.

Low-band spectrum is especially useful for wide-area coverage and indoor reach, so the transaction could strengthen the coverage layer underneath T-Mobile's higher-capacity mid-band 5G network.

Source: [PhoneArena](https://www.phonearena.com/news/t-mobile-buying-600-mhz-spectrum-from-bluewater-wireless_id184912)

## OpenAI launches GPT-6.2 Astra and Sol

OpenAI introduced GPT-6.2 Astra for difficult professional and scientific tasks and GPT-6.2 Sol as its efficient everyday model. The company says Astra improves by 5.2 points over GPT-6 Astra on Agents' Last Exam while costing less than one-third as much, and scores nine points higher on Terminal-Bench-Science 0.1.

Astra's API input and output prices are 20% below GPT-6 Astra, with cached input discounted 60%. The larger product shift is toward measuring complete work products—code, spreadsheets, documents, slides, and computer use—rather than isolated question answering.

Source: [OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol/)

## NVIDIA revenue doubles as Vera Rubin begins shipping

NVIDIA reported fiscal Q3 2027 revenue of $115.8 billion, up 103% from a year earlier. Data-center revenue reached $107.6 billion, up 110%, while Vera Rubin NVL72 racks and Vera CPUs entered volume shipments.

The company guided to $130 billion for the next quarter, plus or minus 3%, while explicitly assuming no China data-center compute revenue. That combination captures both the scale of AI-infrastructure demand and the growing impact of export controls on planning.

Source: [NVIDIA](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-third-quarter-fiscal-2027)

## NVIDIA locks in more AI-factory manufacturing capacity

NVIDIA also expanded long-term agreements across substrates, advanced packaging, wafers, and contract manufacturing. Partners include Kinsus, Samsung Electro-Mechanics, Amkor, SPIL, TSMC, and Foxconn.

Kinsus plans to expand NVIDIA-dedicated ABF substrate capacity by more than 3.5 times, while NVIDIA is supporting additional Amkor capacity in Arizona and South Korea and multibillion-dollar SPIL packaging expansion in Taiwan. The commitments show that advanced packaging and substrates—not only leading-edge wafers—remain strategic bottlenecks.

Source: [NVIDIA](https://nvidianews.nvidia.com/news/nvidia-expands-commitments-with-supply-chain-partners-to-support-ai-infrastructure-buildout)

## Microsoft turns Copilot into a multi-agent work platform

Microsoft's Ignite announcements reposition Copilot as an operating layer for work. Copilot Workspaces gives people and agents shared context for collaborative tasks, while Microsoft IQ externalizes the organizational context behind Copilot across Fabric, Foundry, Microsoft 365, and third-party connectors.

Microsoft also made Decision-1.1 generally available, announced its Code 2 agentic coding family, brought GPT-6.2 and new Meta models to Foundry, and introduced licensed access to MAI model weights for selected customers.

Source: [Microsoft](https://blogs.microsoft.com/blog/2026/11/17/ignite-2026-building-the-frontier-ecosystem/)

## AMD completes its acquisition of World Labs

AMD completed its acquisition of World Labs, adding Fei-Fei Li's spatial-intelligence research team to the company. Li becomes AMD executive vice president and chief scientist, reporting to CEO Lisa Su.

The strategic logic is broader than talent acquisition: AMD wants models, software, and systems research to shape future hardware. World Labs' work on interactive 3D world models gives AMD a differentiated path into robotics, simulation, and physical AI.

Source: [AMD](https://newsroom.amd.com/news/amd-completes-acquisition-world-labs/)

## U.S. advances restrictions on new Chinese data-center optics

The Trump administration is advancing FCC restrictions on imports of new Chinese optical-transceiver models despite lobbying from Amazon, Google, and Meta. The proposal focuses on new models rather than removing installed equipment, limiting immediate disruption.

The longer-term risk is supply concentration. Optical transceivers move data over fiber inside AI data centers and telecom networks, and industry estimates suggest replacing Chinese production volumes could take years. The policy may benefit non-Chinese suppliers, but it could also raise infrastructure costs and slow deployments.

Source: [Reuters via Yahoo Finance](https://finance.yahoo.com/technology/articles/exclusive-trumps-china-data-center-110205689.html)

## Research Radar

### Semantic Communication via Analog RF Computing: When the Radio Computes the Meaning

Christo Kurisummoottil Thomas proposes executing a semantic encoder inside the receiver RF front end by reusing passive mixers. The paper unifies analog-computing and uplink noise in one model and derives a semantic-aware water-filling allocation across clients, encoder layers, and uplinks.

Source: [arXiv 2611.22100](https://arxiv.org/abs/2611.22100)

### Hardware Impairment Parameter Estimation in Fluid Antenna Systems by Inverse Optimization

Songling Zhang, Zhaohui Yang, Ruopeng Xu, and Hao Xu formulate hardware-impairment estimation as an inverse-optimization problem. Their method outperforms KKT residual minimization and improves spectral efficiency by up to 22.86% over an ideal-hardware assumption. The work has been accepted by IEEE GLOBECOM 2026.

Source: [arXiv 2611.22322](https://arxiv.org/abs/2611.22322)

### Multi-connectivity in Wireless Access

Danny De Vleeschauwer and colleagues analyze whether connecting a user simultaneously to multiple access points improves application-level quality of experience. The central tradeoff is a potentially lower average bit rate in exchange for smoother throughput that adaptive applications can use without building latency-inducing queues.

Source: [arXiv 2611.22869](https://arxiv.org/abs/2611.22869)

## Source Notes

Mobile World Live blocked direct retrieval of its T-Mobile report with HTTP 403, so the filing details were corroborated through indexed results and PhoneArena. IEEE Xplore and ACM Digital Library returned no newly indexed eligible wireless papers; the research section therefore uses verified arXiv records, including one accepted at IEEE GLOBECOM 2026.

## Takeaway

Today's clearest trend is vertical integration: satellite and terrestrial connectivity, frontier models, and the semiconductor supply chain are all being assembled into tightly controlled end-to-end platforms.
