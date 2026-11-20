---
title: Daily Digest — November 20, 2026
date: 2026-11-20 07:00:00
tags:
  - AI
  - 6G
  - LEO
  - semiconductors
categories:
  - Daily Digest
---

Today's news shows next-generation connectivity and AI becoming physical infrastructure: satellite operators are planning terrestrial microcells, 6G sensing is entering the lab, upper-6-GHz arrays are being tested in the field, and computer-use agents are moving onto desktops.

## SpaceX designs rooftop microcells for Starlink Mobile

Elon Musk says SpaceX has designed compact cellular sites that could go into production next year and mount on rooftops much like a Starlink dish. The units are intended to solve a core direct-to-device limitation—weak satellite penetration through buildings—and to fill dense cities with many small ground cells while satellites cover broad and remote areas. The hybrid architecture makes Starlink Mobile look increasingly like a full carrier network rather than a satellite-only overlay.

Source: [PCMag](https://www.pcmag.com/news/elon-musk-eyes-producing-micro-cell-towers-for-starlink-mobile-next-year)

## Keysight and Cohere bring multi-drone ISAC into the lab

Keysight and Cohere Technologies have introduced a lab platform for integrated sensing and communication that emulates multiple unmanned aerial vehicles while a commercial 5G base station continues to carry normal traffic. Cohere's Zak-OTFS-based physical layer supports detection, classification, and tracking across FR1, FR2, and emerging FR3 frequencies up to 18 GHz, with as much as 400 MHz of instantaneous bandwidth. The work is a practical step toward treating radio networks as distributed sensors without dedicating separate spectrum and infrastructure.

Source: [Keysight](https://www.keysight.com/us/en/about/newsroom/catalog/news-release.2026.1117_pr26-124-keysight-brings-multi-unmanned-aerial-vehicle-6g-sensing-into-the-lab-with-cohere-technologies.html)

## Vodacom and Huawei trial upper-6-GHz radio for 6G-era capacity

At Africa Tech Festival in Cape Town, Vodacom and Huawei demonstrated upper-6-GHz equipment built around a 1,536-element, 256-transceiver VitaAAU array. The 6.425–7.125 GHz band offers 700 MHz of potential capacity and sits between today's mid-band mobile spectrum and millimeter wave, making it attractive for high-capacity wide-area service. The trial also examines whether operators can reuse existing site infrastructure and preserve coverage as they add much wider channels.

Source: [Huawei](https://www.huawei.com/en/news/2026/11/u6ghz-vitaaau-retinamimo)

## Gemini can now operate Mac apps in a background window

Google is rolling out computer use in the Gemini app for Mac, allowing the agent to click, type, navigate menus, fill forms, and coordinate work across local files, desktop applications, and websites. Gemini performs the task in an isolated background window with a live preview, leaving the user's primary screen and cursor available. Users select which apps it can access, can pause execution, and must approve sensitive steps.

Source: [Google](https://blog.google/innovation-and-ai/products/gemini-app/computer-use-mac/)

## Anthropic closes its first trading day 17% above the IPO price

Anthropic's shares opened at $111.50 and closed at $97.17 after the IPO priced at $83, leaving the stock 17% above its offer price and valuing the Claude developer at roughly $1.27 trillion. The debut is a genuinely new development from yesterday's pricing announcement: public investors have now delivered their first market verdict, even as the wider market sold off.

Source: [Yahoo Finance](https://finance.yahoo.com/technology/live/anthropic-ipo-live-anthropic-stock-begins-trading-in-record-81b-raise-with-15t-valuation-192410598.html)

## John Deere acquires Orchard AI

Deere has acquired Orchard Robotics, which operates as Orchard AI, to add plant-level intelligence for high-value specialty crops. Orchard's FruitScope system uses vehicle-mounted cameras to estimate yield and track individual plants; integrating those observations with Deere equipment and farm-management tools could turn routine field passes into continuous crop measurement and more precise operational decisions.

Source: [John Deere](https://www.deere.com/en-us/john-deere-news/john-deere-acquires-orchard-ai)

## TSMC tightens advanced-chip manufacturing rules for Chinese customers

TSMC is suspending some previously permitted advanced manufacturing orders from Chinese chip designers and generally limiting affected customers to older process technologies, according to Reuters. New U.S. rules removed a verification path that had allowed some customers to demonstrate that their designs were outside export-control thresholds; affected advanced chips are now presumed controlled unless a license or exception applies. The change pushes export policy deeper into foundry intake and compliance decisions.

Source: [Reuters via Investing.com](https://www.investing.com/news/stock-market-news/tsmc-tightens-china-ai-chip-curbs-as-new-us-rules-close-manufacturing-loophole-sources-say-5038806)

## Apple releases Depth Pro 2 code and weights

Apple's Depth Pro 2 estimates dense metric depth for both still images and video at native resolution. The model family is designed to avoid the usual compromise in which single-frame systems preserve sharp boundaries while multi-frame systems produce smoother temporal behavior. Apple reports gains in metric accuracy, sharpness, temporal consistency, and runtime, and has released code and weights for research use.

Source: [arXiv](https://arxiv.org/abs/2611.26603)

## Research Radar

### Chance-Constrained Joint Beam Hopping Scheduling and Bandwidth Allocation for LEO Satellites

Olfa Ben Yahia, Jean-Francois Frigon, Brunilde Sanso, Stephane Martel, Guillaume Mantelet, Antoine Lesage-Landry, and Gunes Karabulut Kurt introduce a service-level-agreement-aware optimizer that jointly schedules beam hopping and bandwidth. By converting probabilistic reliability requirements under spectral-efficiency uncertainty into deterministic second-order cone constraints, it maintains target SLA reliability under heavier loads while retaining fairness and efficient allocation.

Source: [arXiv:2611.26270](https://arxiv.org/abs/2611.26270)

### Physics-Informed Deep Learning for Channel Prediction in Satellite-Mounted Metasurface Reflection Communication Networks

Aolin Sun, Ruihong Jiang, Jincong Mo, Yangbo Guo, and Zhuangzhuang Cui embed wireless propagation constraints—including monotonicity and asymptotic decay—into a predictor for satellite-mounted programmable metasurfaces. Their simulations report outage-probability prediction accuracy above 0.99 while preserving physically consistent behavior as orbital geometry, satellite density, and hardware quantization vary.

Source: [arXiv:2611.26068](https://arxiv.org/abs/2611.26068)

### Channel-Aware Codebook Design for Task-Oriented Token Communication Over Wireless Networks

Chenliang Wu, Zhicheng Liu, Zhouxiang Zhao, Ruopeng Xu, Zhaohui Yang, and Zhaoyang Zhang reorder the labels of a frozen 14-bit VQGAN codebook to make semantic tokens more resilient to wireless errors. At a bit-error rate of 0.01, the static lookup-table design reduces LPIPS perceptual distortion by 12.3% and improves COCO average precision by 14.1% without changing payload size or retraining the model.

Source: [arXiv:2611.26038](https://arxiv.org/abs/2611.26038)

## Source notes

Keysight's press-release page returned HTTP 403 to direct extraction, so its indexed release metadata was cross-checked against telecom coverage. IEEE Xplore and ACM Digital Library returned no newly indexed eligible wireless papers for the seven-day window; the research section therefore uses verified arXiv submissions from November 19.

The common thread is architectural convergence: satellite and terrestrial radio, sensing and communication, agents and desktop software, and AI design and chip governance are becoming tightly coupled systems.
