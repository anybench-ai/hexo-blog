---
title: Daily Digest — November 22, 2026
date: 2026-11-22 07:00:00
tags:
  - AI
  - 5G
  - satellite
  - wireless
  - technology
categories:
  - Daily Digest
---

Today's technology picture is unusually coherent: AI services are being forced to prove that privacy promises hold across their supply chains, smaller open models are becoming useful on local hardware, and wireless researchers are designing smarter control across unlicensed spectrum, O-RAN slices, and regenerative satellite payloads.

## OpenRouter removes providers after data-policy failures

OpenRouter off-boarded three inference providers after security researchers found evidence that data had been compromised or that advertised handling policies were not being upheld. It also removed 125 endpoints from Zero Data Retention eligibility, notified potentially affected customers, and said it will adapt the researchers' canary-token tests for continuous checks. OpenRouter emphasized that the findings did not show a breach of OpenRouter itself; the failures occurred at specific downstream providers.

Source: [OpenRouter](https://openrouter.ai/blog/announcements/data-processing-incidents-on-inference-providers/)

## Inkling 2 Mini brings looped reasoning to laptops

Thinking Machines Lab released Inkling 2 Mini with open weights. The 26.4-billion-parameter mixture-of-experts model activates 5.4 billion weights per token after accounting for its looped middle layers, and its approximately 20 GB memory footprint allows it to run locally on suitably equipped laptops and compact AI desktops. The company reports that looping improves long-horizon reasoning without forcing the model to emit longer hidden reasoning traces, an architecture worth watching for both efficiency and monitorability.

Source: [Thinking Machines Lab](https://thinkingmachines.ai/news/inkling-2-mini/)

## OpenAI introduces MedChemBench

MedChemBench evaluates whether models can connect molecular structure with experimental evidence across 99 medicinal-chemistry problems drawn from 117 papers and patents. GPT-6.2 Astra earned 84.5% of available credit at the highest reasoning setting, but the detailed results are more revealing than the headline score: molecular reconstruction and evidence-based explanation were much stronger than compound selection and numerical property prediction. OpenAI explicitly cautions that the benchmark does not establish real-world drug-discovery ability.

Source: [OpenAI](https://openai.com/index/introducing-medchembench/)

## NVIDIA reportedly comes under SEC scrutiny

Reuters reports that the U.S. Securities and Exchange Commission is examining NVIDIA's accounting practices. The reported inquiry adds regulatory uncertainty after a major selloff in the chipmaker's shares, although NVIDIA and regulators have not publicly detailed the scope or status of the probe. For the AI infrastructure sector, the episode is a reminder that extraordinary demand growth also brings closer scrutiny of revenue recognition, customer concentration, and disclosure practices.

Source: [Reuters via Yahoo Finance](https://finance.yahoo.com/markets/article/nvidia-stock-extends-25-trillion-rout-as-sec-probe-reportedly-investigates-its-accounting-194945274.html)

## FCC grants 71 technology-import waivers

The FCC approved waivers allowing 71 companies to continue importing restricted drones, wireless routers, robots, and power inverters. The approvals are tied to commitments totaling $4.4 billion in U.S. investment and 4,700 jobs, illustrating how national-security controls are being paired with incentives for domestic production rather than applied as uniform bans.

Source: [ETTelecom](https://telecom.economictimes.indiatimes.com/news/policy/fcc-grants-tech-import-waivers-as-firms-boost-us-investment/136041939)

## Starlink supports flood recovery on Florida's Space Coast

Starlink announced free residential service through December 20 for new and existing customers affected by flooding in Brevard County, Florida. The region includes Kennedy Space Center and Cape Canaveral, and the company says it is coordinating with local responders. Satellite connectivity's resilience value is most tangible in exactly these circumstances, when terrestrial access and power restoration may be uneven.

Source: [Starlink on X](https://x.com/Starlink/status/2123917635058328025)

## Gemini turns noisy wildfire radio into faster alerts

Google engineers embedded with Watch Duty for six months and used more than 20,000 hours of past radio recordings to build a Gemini-powered transcription tool for noisy VHF wildfire traffic. The system reduced word error rate on degraded audio from 38% to 22.34%, processes more than 200 hours of speech daily across roughly 400 feeds, and can flag a new dispatch in under 30 seconds. During Washington's Railroad Fire, that speed helped Watch Duty issue its first overnight Critical Alert before flames reached homes.

Source: [Google](https://blog.google/company-news/outreach-and-initiatives/google-org/watch-duty-gemini-tool/)

## Qualcomm expands into rack-scale inference evaluation

Qualcomm announced a collaboration with Cirrascale that makes its Dragonfly AI200 rack-scale inference platform available for evaluation by select customers. The move broadens Qualcomm's AI story beyond phones, PCs, and embedded devices toward data-center inference, where memory efficiency, deployment economics, and software compatibility will determine whether new accelerators can break into NVIDIA-dominated workloads.

Source: [Qualcomm on X](https://x.com/Qualcomm/status/2123944563135963191)

## Research Radar

### SimPyWireless: Wi-Fi and 5G NR-U coexistence

Md Rashedur Rahman and Paulo Costa present an open-source, PHY-aware discrete-event simulator for Wi-Fi and 5G NR-U sharing the 5 GHz band. It combines propagation, interference, SINR, heterogeneous traffic, mobility, and technology-specific channel access, aiming for a practical middle ground between analytical models and hardware testbeds.

Source: [arXiv:2611.25350](https://arxiv.org/abs/2611.25350)

### CoSlice: coordinated multi-agent control for O-RAN slicing

Pengxin Wang, Nakjung Choi, and Jingdi Chen combine fast preference-conditioned slice agents with a slower LLM coordinator that adjusts objectives from global observations. In an ORANSlice and RFsim evaluation environment, CoSlice reduced both average and tail SLA violations relative to centralized and multi-agent baselines.

Source: [arXiv:2611.23909](https://arxiv.org/abs/2611.23909)

### Hierarchical traffic engineering for regenerative satellites

Mohamed Khiari and colleagues model both constellation routing and each satellite's internal modem-bank network. Their hierarchical payload-aware allocation algorithm delivered about nine times the throughput of shortest-path routing under heavy load, with 17% lower end-to-end delay and no packet loss, showing why regenerative payload constraints must be part of constellation-level control.

Source: [arXiv:2611.24777](https://arxiv.org/abs/2611.24777)

## Source notes

IEEE Xplore and ACM Digital Library returned no newly indexed eligible wireless papers, so today's Research Radar uses verified arXiv submissions from November 18–19. Yahoo Finance blocked direct page extraction for the Reuters NVIDIA report, and the FCC waiver item was verified through indexed coverage rather than a directly indexed FCC release.

The broader takeaway is that trustworthy AI infrastructure now depends as much on provider accountability and efficient deployment as on model intelligence, while the wireless frontier is moving intelligence deeper into spectrum sharing, RAN control, and satellite payloads.
