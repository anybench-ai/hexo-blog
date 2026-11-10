---
title: "Morning Digest — November 10, 2026"
date: 2026-11-10 07:00:00
categories: [Digest, Technology]
tags: [5G, 6G, LEO, Direct-to-Device, AI, OpenAI, Anthropic, AWS]
---

Today’s strongest signals are about operational convergence: terrestrial-to-satellite handoffs, ordinary LTE hardware on LEO links, a commercial 5G Standalone launch, and AI companies building stronger control, distribution, and financing layers.

<!-- more -->

## AT&T and AST complete a terrestrial-to-satellite handoff

AT&T and AST SpaceMobile say they completed what they believe is the first successful handoff between a terrestrial cellular network and a direct-to-device satellite network. Ericsson and Nokia supplied supporting ground-network technology.

The milestone matters because direct-to-device service cannot become a seamless coverage layer if sessions break whenever a handset moves between tower and satellite footprints. A functioning handoff brings satellite coverage closer to behaving like another radio-access layer inside an operator network rather than a separate emergency service.

Source: [AST SpaceMobile business update](https://finance.yahoo.com/technology/articles/ast-spacemobile-provides-business-third-213000142.html)

## Standard LTE IoT modules connect through Starlink Direct to Cell

Fibocom’s LE270-EU and LE271-GL Cat.1 bis modules connected to SpaceX’s live Direct to Cell network in New Zealand using standard firmware and no satellite-specific hardware. Both registered, established IP sessions, and transferred data across outdoor, in-vehicle, and indoor tests.

With open sky, the modules delivered about 2.0–2.2 Mbps downlink and 0.3 Mbps uplink. Indoor performance fell to roughly 0.5 Mbps in some tests, and satellite uploads used 1.5–1.8 times the energy of terrestrial cellular. The result is especially relevant to asset trackers and remote sensors: existing low-cost LTE designs may gain fallback coverage without a second satellite modem.

Source: [Fibocom via PR Newswire](https://www.prnewswire.com/news-releases/fibocom-lte-cat1-bis-modules-starlink-dtc-field-test-report-302930788.html)

## SK Telecom targets a December 5G Standalone launch

SK Telecom plans to commercialize 5G Standalone service in December after completing technology optimization and commercial-network verification. A standalone core enables capabilities that non-standalone 5G cannot fully deliver, including more flexible slicing, lower-latency service control, and a cleaner path to 5G-Advanced features.

The carrier is validating 5G-Advanced upgrades while participating in 6G R&D and standardization, which it expects around 2029 ahead of post-2030 deployment. The near-term 5G SA launch is the more concrete milestone: it turns years of architecture work into an operating commercial platform.

Source: [RCR Wireless News](https://rcrwireless.com/20261109/5g/sk-telecom-5g-sa)

## China moves 6G sensing from lab concepts toward trials

Researchers at Purple Mountain Laboratories in Nanjing are conducting a new round of multi-base-station cooperative-sensing tests. The concept uses radio infrastructure not only to communicate but also to sense motion in a radar-like way, a core candidate capability for integrated sensing and communication in 6G.

The work sits on a large deployment base: China reports more than 26,000 industrial 5G private networks and 1,260 5G factories, with industrial internet coverage across all 41 major industrial categories. That installed base provides both demand and test environments for moving sensing, computing, and communications into one network platform.

Source: [China Internet Information Center / CCTV report](http://v.china.com.cn/2026-11/08/content_118766151.html)

## Anthropic releases Claude Fable 5.2 and Mythos 5.2

Anthropic released Claude Fable 5.2 and Claude Mythos 5.2, positioning them as its most capable models for ambitious technical work. The company highlights gains in coding, reasoning, and vision, with applications spanning software engineering, finance, science, and other complex projects.

The launch reinforces a broader shift in frontier-model competition: vendors are differentiating less on conversational fluency and more on whether models can reliably sustain difficult, open-ended professional workflows.

Source: [Anthropic](https://www.anthropic.com/news/models)

## OpenAI deploys a fail-closed Control Room for research workloads

OpenAI built Control Room as a central authorization system for model workloads across its research infrastructure. Every covered inference request carries a job identifier and checks whether the workload is still allowed to generate output. Once an intervention is ordered, further progress stops within a maximum of 35 seconds.

The safety design is implemented at the inference layer, where code paths are more centralized than fast-changing experiment code. It also fails closed: if the Control Room service is unavailable or tampered with, frontier research inference requests are denied until service returns. That turns emergency stopping from a researcher-level convention into infrastructure-level enforcement.

Source: [OpenAI](https://openai.com/index/control-room/)

## ChatGPT Enterprise lands in AWS Marketplace

ChatGPT Enterprise is now available through AWS Marketplace, allowing organizations to discover, purchase, and manage it through existing AWS procurement and billing relationships. Eligible spending can count toward AWS commitments, and customers receive the same OpenAI features and release timing as direct buyers.

The listing complements OpenAI models in Amazon Bedrock: developers can build applications through Bedrock while employees use ChatGPT, Codex, and related workplace tools. Procurement integration is unglamorous but consequential—it removes a recurring barrier to enterprise deployment.

Source: [OpenAI](https://openai.com/index/chatgpt-enterprise-aws-marketplace/)

## Anthropic launches its proposed IPO roadshow

Anthropic has launched the roadshow for a proposed initial public offering of Class A common stock. Its registration statement has been filed but is not yet effective, so the process remains subject to securities review and market conditions.

Public ownership would expose a frontier-model developer to recurring disclosure, governance, and profitability scrutiny while giving it access to a much broader capital base. That tension—between the immense cost of frontier development and the transparency expected of public companies—will be central to the offering.

Source: [Anthropic](https://www.anthropic.com/news/roadshow-launch)

## Research Radar

### Coexistence of Direct-to-Device Satellite Systems with 5G/6G Terrestrial Networks

Muneer M. Alzubi and colleagues model aggregate downlink interference from hypothetical D2D satellite systems in Jordan and Iraq into terrestrial mobile users along Saudi Arabia’s borders in the 698–960 MHz band. The protection criterion was exceeded up to 88% of the time, requiring as much as 27 dB of additional isolation.

A one-cell-diameter border exclusion zone provided only moderate improvement. Narrow beams with deep nulls reduced exceedance to about 40%, showing that cross-border D2D coexistence will require substantive antenna and coordination measures rather than simple geographic buffers.

Source: [arXiv](https://arxiv.org/abs/2611.12644)

### Neural Multipath Fields for 6G FR3 Digital Twins

Srijita Sanyal, Adam Umra, and Aydin Sezgin propose a latent-adaptive neural multipath field for site-specific channel twins at 7.5 GHz. Instead of retraining an entire model for a new scene, the method updates only a 16-dimensional scene representation.

Across six ray-traced indoor environments, adaptation required just 5–10 target links—0.42–0.83% of the available measurements. Compared with full-network fine-tuning, it reduced adaptation time by 28–30% and incremental peak GPU memory by 82–85%, a useful step toward practical, rapidly deployable FR3 digital twins.

Source: [arXiv](https://arxiv.org/abs/2611.12425)

### Wireless AI Networks: Co-Adapting Communication Resources and Distributed Intelligence

Ziqiang Ye and colleagues argue that distributed AI over wireless links should optimize the information value of transmissions, not merely allocate bandwidth and power. Their framework maps feasible AI configurations to communication budgets, then uses task-level value to choose model updates and wireless resources jointly.

Experiments show how update selection and statistical correction can improve federated learning under the same payload budget, while sensitivity-aware power allocation limits model-accuracy degradation under the same transmit-power constraint. The perspective is well aligned with AI-native 6G resource management.

Source: [arXiv](https://arxiv.org/abs/2611.11774)

## Source notes

One AST SpaceMobile press-release mirror returned a header-overflow error, so the business update was cross-checked through indexed copies and reporting. IEEE Xplore and ACM Digital Library returned no newly indexed matching papers; Research Radar uses verified arXiv records from the last seven days.

## Takeaway

Terrestrial and satellite networks are converging at the device and handoff layers just as AI companies harden infrastructure, distribution, and financing for the next deployment phase.
