---
title: "Morning Digest — October 25, 2026"
date: 2026-10-25 07:00:00
tags:
  - AI
  - 6G
  - Satellite
  - Semiconductors
  - NVIDIA
categories:
  - Daily Digest
---

Today’s news makes the infrastructure constraint impossible to miss. Satellite operators and terrestrial carriers are contesting the same spectrum, AST is assembling the ground segment needed for direct-to-phone service, AWS is booking compute years ahead, and the U.S. is directing semiconductor R&D money toward the power systems beneath advanced computing. At the model layer, Moonshot is pushing a very large open-weight architecture toward coding and agentic use, while researchers are making 6G algorithms more aware of interference graphs and real baseband hardware.

## U.S. carriers challenge the FCC’s satellite-spectrum expansion

AT&T, Verizon, and T-Mobile are pressing the Federal Communications Commission to narrow a proposal that would make an additional 482 MHz available for Supplemental Coverage from Space. The carriers specifically object to including the 2.5 GHz and 3.45 GHz bands, arguing that satellite use could interfere with spectrum already carrying terrestrial 5G traffic. The dispute goes beyond one SpaceX proceeding: it is an early test of how regulators will share valuable mid-band frequencies when satellite systems begin behaving more like mobile networks. The commission is scheduled to consider the proposal on October 29.

Source: [https://www.pcmag.com/news/att-t-mobile-verizon-fight-fcc-satellite-proposal-that-helps-spacex](https://www.pcmag.com/news/att-t-mobile-verizon-fight-fcc-satellite-proposal-that-helps-spacex)

## AST SpaceMobile says its global ground network has passed 60 gateways

AST SpaceMobile says more than 60 gateways are deployed, being installed, or in planning around the world. The company is targeting initial intermittent direct-to-phone coverage before the end of 2026 in the United States, Canada, Japan, the United Kingdom, and Saudi Arabia. Its broader ecosystem includes more than 60 mobile-network operators representing over 3 billion subscribers. Satellites attract most of the attention, but the gateway buildout is equally important: it is what connects space-based radio access to partner cores, local spectrum, and ordinary mobile services.

Source: [https://x.com/AST_SpaceMobile/status/2113632854806507643](https://x.com/AST_SpaceMobile/status/2113632854806507643)

## Moonshot launches the 2.8-trillion-parameter Kimi K3.1 Pro

Moonshot AI introduced Kimi K3.1 Pro, a multimodal mixture-of-experts model with 2.8 trillion total parameters, 104 billion active parameters, and a one-million-token context window. The company is positioning it for full-project coding in engines such as Unreal, Unity, and Godot; parametric 3D work in Blender and CAD; financial analysis; and long-horizon agent tasks. K3.1 Pro and a faster Highspeed variant are available through Kimi’s products and API, while the company says full weights are due by November 4. Independent evaluation will matter, but the combination of scale, context, and promised open weights makes this a consequential Chinese frontier-model release.

Source: [https://x.com/Kimi_Moonshot/status/2113680701770068067](https://x.com/Kimi_Moonshot/status/2113680701770068067)

## AWS capacity is largely booked through 2027

Amazon CEO Andy Jassy says AWS has effectively sold its available 2026 capacity, is largely booked for 2027, and has already committed a meaningful portion of 2028. The bottlenecks extend beyond accelerators to power, data-center buildings, networking, and memory, which means additional capital expenditure does not translate immediately into usable cloud supply. For AI developers, this makes long-term capacity contracts and model efficiency strategic concerns rather than simple procurement choices. For the industry, it is evidence that demand is still colliding with the physical pace of infrastructure construction.

Source: [https://www.reuters.com/business/retail-consumer/amazon-cloud-capacity-sold-out-through-2027-ceo-jassy-says-2026-10-23/](https://www.reuters.com/business/retail-consumer/amazon-cloud-capacity-sold-out-through-2027-ceo-jassy-says-2026-10-23/)

## NVIDIA’s neocloud financing strategy faces a market stress test

NVIDIA has evolved from supplying accelerators to helping finance and backstop the companies buying them. CNBC estimates that the chipmaker has roughly $7 billion invested in AI infrastructure companies and about $164.5 billion in guarantees and other commitments. That ecosystem is now being tested as prominent neocloud partners including CoreWeave, Nebius, and IREN have suffered sharp October share declines. The arrangement can accelerate GPU deployment and create customers, but it also connects NVIDIA’s future demand more closely to the financing health and utilization rates of those same customers.

Source: [https://www.cnbc.com/2026/10/24/nvidias-role-as-ai-financier-faces-first-big-test-as-neoclouds-take-market-hit.html](https://www.cnbc.com/2026/10/24/nvidias-role-as-ai-financier-faces-first-big-test-as-neoclouds-take-market-hit.html)

## U.S. Commerce lines up $389 million for energy-semiconductor R&D

The U.S. Department of Commerce signed four letters of intent for up to $389 million in CHIPS and Science Act research awards. The projects target power-semiconductor devices and critical materials used in fusion energy, advanced computing, and semiconductor manufacturing. This is a different layer of the chip supply chain from leading-edge logic: power conversion, delivery, and specialized materials increasingly determine how much compute can be installed and operated. The awards remain proposed rather than final, but they show industrial policy expanding toward the energy hardware required by AI factories and other high-power systems.

Source: [https://www.nist.gov/news-events/news/2026/10/department-commerce-announces-letters-intent-4-companies-389-million-rd](https://www.nist.gov/news-events/news/2026/10/department-commerce-announces-letters-intent-4-companies-389-million-rd)

## MIT’s X-Hinges turns 3D-printed objects into touch-aware devices

MIT researchers developed X-Hinges, a design system for building 3D-printable objects with conductive hinges that act as embedded sensors. Users assemble shapes in software, define how components should move, and print objects whose joints can detect motion and human contact without requiring a separate sensor at every articulation. Demonstrations include interactive lamps and gloves. The work points toward fabrication tools that generate not only an object’s geometry but also its sensing behavior, lowering the barrier to customized wearables, interfaces, and adaptive devices.

Source: [https://news.mit.edu/2026/design-software-reimagines-everyday-objects-as-self-aware-devices-1022](https://news.mit.edu/2026/design-software-reimagines-everyday-objects-as-self-aware-devices-1022)

## Research Radar

### Interference-Graph-Aided Multi-Agent Reinforcement Learning for Beam Hopping LEO Satellite Networks

Hao Yuan, Ziyi Yang, and Xing Zhang represent coupling among satellite beams as an interference graph, then feed graph-convolved neighbor information into each reinforcement-learning agent before Q-value mixing. In simulation, the method delivered 34.4% more throughput than QMIX and more stable interference management under nonuniform traffic and co-channel interference. The result is directly relevant to dynamic LEO capacity allocation, where treating beams as independent agents discards the structure of the radio problem.

Source: [https://arxiv.org/abs/2610.28248](https://arxiv.org/abs/2610.28248)

### Toward Agentic AI for the 6G Physical Layer: From Algorithm Discovery to Verified Baseband Silicon

Eric Mittag, Lukas Brechtel, Maximilian Stark, and Hans D. Schotten present an agentic workflow that ports, optimizes, and validates physical-layer algorithms on a commercial baseband system-on-chip. Applied to OTFS detection on the open 6G4All platform, the agent produced 12 cycle-exact kernels and a hardware-shaped detector that used 13.9% fewer cycles than the ported discovered algorithm while matching its error rate. The paper, accepted at an IEEE GLOBECOM 2026 workshop, is valuable because it closes the gap between AI-generated algorithms and the numeric, memory, and timing limits of deployable silicon.

Source: [https://arxiv.org/abs/2610.27797](https://arxiv.org/abs/2610.27797)

### Revolutionizing 6G Wireless Networks with RISs: Enhancements in Sensing and Communications

Jiguang He and collaborators survey how reconfigurable intelligent surfaces can support both communications and sensing in 6G. Beyond familiar coverage extension and interference suppression, the paper distinguishes passive and active sensing roles and maps RIS control to integrated sensing-and-communication applications. Accepted by IEEE Communications Magazine, it frames RIS as a programmable aperture that can improve both the radio link and the network’s ability to observe its environment.

Source: [https://arxiv.org/abs/2610.27695](https://arxiv.org/abs/2610.27695)

## Source note

IEEE Xplore and ACM Digital Library searches returned no newly indexed matching papers. The research section therefore uses verified arXiv records, including two manuscripts accepted for IEEE venues.

## Takeaway

AI demand is forcing infrastructure decisions all the way down the stack—from spectrum and satellite gateways to power chips, booked cloud capacity, and hardware-aware 6G algorithms.
