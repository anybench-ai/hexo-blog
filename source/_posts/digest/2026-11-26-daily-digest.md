---
title: "Morning Digest — November 26, 2026"
date: 2026-11-26 07:00:00
tags:
  - AI
  - 5G
  - 6G
  - LEO
  - satellites
  - networking
categories:
  - Daily Digest
---

Today’s strongest signal is the convergence of communications and compute infrastructure: regulators have authorized orbital data centers at unprecedented scale, direct-to-cell service is reaching millions of users, and 5G slicing is proving useful during real emergencies. At the same time, AI platforms are adding stronger privacy and governance boundaries as agents gain deeper access to business systems and personal computers.

## FCC authorizes SpaceX to deploy up to one million orbital compute modules

The FCC granted SpaceX the first U.S. authorization for a space-based data-center constellation. The order covers up to one million orbital compute modules under the Starmind program, intended to process large AI workloads in orbit and send results back to Earth.

The number is an authorization ceiling, not a near-term deployment commitment. Building anything close to that scale would still require enormous launch capacity, power generation, communications bandwidth, collision avoidance, and environmental review. Even so, the decision creates a regulatory path for orbital compute to move from concept to infrastructure category.

Source: [FCC](https://www.fcc.gov/document/fcc-authorizes-1-million-satellites-data-centers-space)

## Starlink Mobile reaches three million users in Kazakhstan

Starlink says more than three million Beeline Kazakhstan customers have used its direct-to-cell service less than two months after launch. Ordinary phones can connect in terrestrial dead zones for messaging, supported apps, and maps without a separate satellite terminal.

The milestone matters because direct-to-device satellite services have often been measured by coverage claims and trials. A multi-million-user deployment begins to expose the operational realities that research must address: capacity allocation, mobility, service continuity, spectrum coexistence, and how satellite access integrates with a mobile operator’s core network.

Source: [Starlink on X](https://x.com/Starlink/status/2125665653432713405)

## T-Mobile deployed dedicated 5G slices during the FAA ground-stop crisis

During the November 13 FAA ground stop, T-Mobile offered temporary T-Priority and SuperMobile service codes to airlines, airport-support agencies, and local police. Participating responders received access to dedicated 5G slices designed to preserve communication quality during congestion.

This is a useful production case for network slicing beyond demonstrations. The operator used software-defined service controls to extend priority treatment quickly and selectively, showing how standalone 5G can support incident response without building a separate physical network.

Source: [SDxCentral](https://www.sdxcentral.com/news/t-mobile-us-served-emergency-5g-network-slices-during-faa-crisis/)

## NVIDIA pushes data-center-class AI into orbit

NVIDIA’s space-computing platform now spans Jetson Orin for power-constrained edge inference, IGX Thor for mission-critical autonomous systems, and the Space-1 Vera Rubin module for data-center-class orbital workloads. The company says the latter can deliver up to 25 times more AI inference compute per GPU for space deployments.

Partners include SpaceX, Kepler Communications, Planet Labs, EnduroSat, Firefly Aerospace, and Lunar Outpost. The use cases range from onboard RF and synthetic-aperture-radar processing to real-time geospatial intelligence and autonomous spacecraft operations, reducing the cost and latency of downlinking raw sensor data.

Source: [NVIDIA](https://www.nvidia.com/en-us/edge-computing/space-computing/)

## OpenAI begins limited testing of Private Inference

OpenAI is testing Private Inference with a small group of business customers as part of its Private Intelligence offering. The feature is intended to protect prompts and responses while models process them using confidential-computing techniques.

Sam Altman also said zero-data-retention customers can pair the feature with Private Safety Processing, enabling automated safety review without OpenAI personnel seeing the underlying content. If the guarantees hold under independent scrutiny, this could remove a major barrier to using frontier models with sensitive enterprise data.

Source: [Sam Altman on X](https://x.com/sama/status/2125638790593274259)

## Google makes Workspace MCP servers and CLI generally available—and mandatory for agents

Google has made its managed Workspace MCP servers and command-line interface generally available for agents accessing Gmail, Drive, Docs, Sheets, Calendar, Chat, Tasks, and other Workspace services. The interfaces add user confirmations, audit logging, DLP checks, access controls, and explicit agent identities.

The larger policy change is that AI agents must stop using traditional Workspace REST APIs and move to the MCP servers or CLI before technical enforcement begins February 1, 2027. This centralizes governance but may also constrain independent agent tooling around Google’s approved interfaces and usage tiers.

Source: [Google Workspace](https://workspace.google.com/blog/product-announcements/built-for-trust-and-control-new-ai-agent-protections-and-developer-tools-in-google-workspace)

## Claude Artifacts can now become installable desktop apps

Anthropic’s new “Install as app” beta turns Claude Artifacts into Mac and Windows applications with their own icons and windows. Apps can use Claude and configured connectors, send notifications, live in the menu bar or system tray, and update when the underlying artifact changes.

Permissions are divided into browser-like defaults, controlled app capabilities, and full computer access. Full access is limited to apps a user created or, for Team and Enterprise, apps made inside the organization; permission must be granted again after each update. Anthropic also warns that it does not review apps before installation.

Source: [Claude](https://claude.com/resources/articles/install-as-app)

## Research Radar

### Relieving Hotspot Congestion in Large-Scale Low Earth Orbit Satellite Networks via Distributed Dual-Timescale Traffic Splitting

Shuyang Li and colleagues propose BRACE, a distributed routing design that combines slower destination-aware traffic splitting with fast, constant-time per-hop reweighting based on local queue state. Across 144-satellite hotspot simulations, it achieved the best reward among tested distributed methods and reduced drop rates by 28–45% versus the lowest-loss baseline under the three heaviest loads. The authors also report gains without retuning in constellations up to 1,584 satellites.

Source: [arXiv](https://arxiv.org/abs/2611.34329)

### Decentralized Clustered Federated Learning for Cellular Traffic Forecasting over LEO Constellations

Jonas Kirch, Tiago Koketsu Rodrigues, and Yuichi Kawamoto extend decentralized federated clustering to moving LEO nodes forecasting cellular traffic. Satellites train through nearest-neighbor inter-satellite gossip without a ground aggregator, while zero-shot head selection adapts to the traffic regime under each satellite. On the Telecom Italia Milan and Trentino dataset, the design reduced RMSE by 15.3% over an equivalent decentralized FedAvg baseline and reached 85.3% cluster-recovery accuracy.

Source: [arXiv](https://arxiv.org/abs/2611.34049)

### SlicePlanner: Logic-Guided Agentic AI for Online QoS-Aware Network Slicing in Open RAN

Adhwaa Al-Chaab, Ayman Younis, and Dario Pompili present a two-agent closed loop for O-RAN slice control. SliceSense proposes admissible actions from live KPIs and historical evidence; SliceGuard validates results, rolls back harmful changes, and refreshes rules under drift. Over-the-air evaluation using OpenAirInterface, FlexRIC, and commercial Sierra Wireless 5G devices reduced SLA latency violations by up to 86% over static slicing and 50% over DRL-based slicing while keeping decisions auditable.

Source: [arXiv](https://arxiv.org/abs/2611.33664)

## Takeaway

Orbital compute, direct-to-cell scale, emergency 5G slicing, and governed agent access all point toward infrastructure that is becoming more autonomous—but also more policy-controlled.
