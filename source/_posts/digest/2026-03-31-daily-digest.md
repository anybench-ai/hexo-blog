---
title: "Daily Digest — March 31, 2026"
date: 2026-03-31
tags:
  - digest
  - ai
  - security
  - nvidia
  - spacex
  - 6g
  - supply-chain
categories:
  - Daily Digest
---

## 🚨 Axios npm Supply Chain Attack — 100M+ Weekly Downloads Compromised

Attackers compromised the npm account of an axios maintainer ("jasonsaayman") and published malicious versions (v1.14.1 and v0.30.4) that pulled in a fake dependency called `plain-crypto-js@4.2.1`, which drops a cross-platform Remote Access Trojan (RAT). Axios is one of npm's most depended-upon packages with over 100 million weekly downloads.

Andrej Karpathy flagged the broader systemic issue: unpinned dependencies mean a single temporary compromise can spread to users at random and at scale. Multiple security firms (Wiz, StepSecurity, Socket, OX Security) issued advisories urging immediate key rotation for anyone who recently installed axios.

The malicious package was published on March 30, 2026 at ~23:59 UTC. Remediation efforts are focused on revoking tokens and tightening publish controls.

Source: [The Hacker News](https://thehackernews.com/2026/03/axios-supply-chain-attack-pushes-cross.html) | [Wiz Blog](https://www.wiz.io/blog/axios-npm-compromised-in-supply-chain-attack) | [Socket.dev](https://socket.dev/blog/axios-npm-package-compromised) | [Karpathy on X](https://x.com/karpathy/status/2038849654423798197)

---

## 🏎️ NVIDIA Hyperion 8 Autonomous Mercedes Wows at GTC 2026

A TechRadar journalist took a ride through San Jose streets in an NVIDIA-powered autonomous Mercedes CLA at GTC 2026 and came away convinced it's "the future." The vehicle runs on NVIDIA's Hyperion 8 platform and handled real traffic — lane changes, intersections, and unexpected situations — with confidence.

NVIDIA continues expanding its autonomous driving ecosystem, working with Mercedes and other OEMs on production-ready self-driving systems.

Source: [TechRadar](https://www.techradar.com/pro/i-took-a-ride-in-an-nvidia-powered-autonomous-mercedes-at-gtc-2026-and-its-convinced-me-this-is-the-future)

---

## 🚀 SpaceX Sets Reuse Record — Falcon 9 Booster Completes 34th Flight

SpaceX launched 29 Starlink satellites from Florida using a Falcon 9 booster that has now flown and landed 34 times — making it the first orbital-class rocket to reach that milestone. The Starlink constellation now exceeds 10,020 active satellites, constituting 65% of all active satellites in orbit.

Source: [SpaceX on X](https://x.com/SpaceX/status/2038761235852718561) | [Wikipedia - Starlink](https://en.wikipedia.org/wiki/Starlink)

---

## 🤖 Qualcomm Puts Qwen3-4B On-Device — 100+ Language LLM on Snapdragon

Qualcomm added Alibaba's Qwen3-4B to its AI Hub, optimized for next-gen Snapdragon and Dragonwing platforms. The 4-billion parameter model supports over 100 languages and runs entirely on-device — no cloud required. This continues the trend of capable LLMs shrinking to fit mobile chipsets.

Source: [Qualcomm on X](https://x.com/Qualcomm/status/2037666042093109496)

---

## 🧠 Sam Altman Endorses Boaz Barak's "AI Safety in Four Fake Graphs"

Sam Altman highlighted Harvard CS professor Boaz Barak's new blog post that uses satirical graphs to illustrate how the AI safety debate gets distorted by extremists on both sides. The post argues for a middle ground between doomers and accelerationists.

Source: [Sam Altman on X](https://x.com/sama/status/2038640963036626971) | [Boaz Barak on X](https://x.com/boazbaraktcs/status/2038606572046172443)

---

## ☁️ AWS Commits $4.6B to South Korea AI & Cloud Infrastructure

Amazon Web Services announced plans to invest 7 trillion won ($4.6 billion) in South Korea by 2031 to expand AI and cloud infrastructure. The investment joins a global wave of hyperscaler buildouts as AWS, Microsoft, and Google race to meet surging AI compute demand worldwide.

Source: [Yonhap News Agency](https://en.yna.co.kr/view/AEN20260331001500320)

---

## 🛡️ Anthropic Economic Index: Experienced Users Iterate More, Delegate Less

Anthropic's latest study of Claude usage patterns reveals that longer-term users are more likely to iterate carefully with the model and less likely to hand it full autonomy — but they attempt higher-value tasks and receive more successful responses. Consumer use is also diversifying: the top 10 task categories now represent only 19% of conversations, down from 24% in November 2025.

Source: [Anthropic on X](https://x.com/AnthropicAI/status/2036499691571953848)

---

## 📡 Research Radar

### AI Lifecycle-Aware Split-RIC for NTN O-RAN
**Authors:** Tarchi et al. | **Venue:** Submitted to IEEE TNSM

Derives closed-form expressions for lifecycle energy and latency when distributing O-RAN control across Ground, LEO, and GEO segments. The Split-RIC architecture identifies operator-relevant feasibility regions that determine when on-board satellite inference is preferable to terrestrial offloading.

🔗 [arXiv:2603.23252](https://arxiv.org/abs/2603.23252)

### Aerial Agentic AI: LLM+SLM for Low-Altitude Wireless Networks
**Authors:** Jiang et al. | **Venue:** arXiv preprint

Proposes a hierarchical framework for 6G drone networks that pairs UAV-side Small Language Models (SLMs) for real-time perception and decision-making with Base Station-side Large Language Models (LLMs) for deep reasoning and strategy optimization. Addresses computational, bandwidth, and latency constraints in Low-Altitude Wireless Networks.

🔗 [arXiv:2603.22866](https://arxiv.org/abs/2603.22866)

### NTIA Preparing Funding for AI-Enhanced 6G Technologies
NTIA is drafting a Notice of Funding Opportunity for organizations developing technologies and use cases for AI-native 6G networks, signaling federal investment in next-gen wireless R&D.

🔗 [Telecompetitor](https://www.telecompetitor.com/technologists-foresee-advances-through-ai-applied-to-6g-wireless/)

---

## 🎓 MIT/Harvard Events This Week

- **Apr 1** — Fireside Chat with Cloudflare CEO Matthew Prince @ MIT Building 3 | [RSVP](https://luma.com/uaoh8rxz)
- **Apr 1** — Agents & APIs Boston Developer Meetup @ Two International Place | [RSVP](https://luma.com/0413g8uy)
- **Apr 3-4** — HBS-MIT Sloan Technology & National Security Conference @ HBS/MIT | [Tickets](https://www.eventbrite.com/e/technology-national-security-conference-2026-tickets-1977520516097)
- **Apr 8** — MIT Decentralized AI Summit + Startup Showcase @ MIT Media Lab | [Info](https://www.media.mit.edu/events/mit-decentralized-ai-summit/)
