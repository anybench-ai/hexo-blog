---
title: "Morning Digest — September 6, 2026"
date: 2026-09-06 07:00:00
tags:
  - AI
  - 6G
  - LEO satellites
  - wireless research
  - cybersecurity
  - NVIDIA
categories:
  - Daily Digest
---

Today’s strongest signal is that advanced infrastructure is becoming more practical and resilient. Regulators are narrowing the spectrum path toward 6G, Europe has gained a new orbital-launch option, and agent platforms are hardening continuity while AI capabilities move into everyday creative and personal workflows.

## Ofcom favors targeted spectrum additions for 6G

The UK regulator is signaling that 6G should reuse and selectively extend existing mobile spectrum rather than depend on sweeping new allocations. Ofcom supports studying the 7 GHz band as a future mobile candidate, while coexistence conflicts make several other proposed bands less attractive.

The stance complements the UK’s planned approach to upper 6 GHz: make 6425–6585 MHz available for Wi-Fi and prioritize mobile use in 6585–7125 MHz. The broader implication is that early 6G deployments may look more like careful spectrum refarming and targeted capacity additions than an entirely new spectrum regime.

Source: [ISPreview](https://www.ispreview.co.uk/index.php/2026/09/ofcom-uk-is-not-looking-to-harness-lots-of-new-spectrum-for-6g-mobile.html)

## Isar Aerospace reaches orbit on its second Spectrum flight

Isar Aerospace’s “Onward and Upward” mission lifted off from Andøya, Norway, and successfully deployed payloads after reaching orbital velocity. The flight carried five CubeSats and one experiment selected through the German Space Agency’s Microlauncher Competition, which is supported by ESA’s Boost! program.

The German startup says it is the first European commercial company to deliver satellites into orbit from continental Europe. Spectrum vehicles three through seven are already in production, and Isar’s new 40,000-square-meter facility is designed eventually to build as many as 40 rockets per year—an important new sovereign launch path for European research and communications constellations.

Source: [Isar Aerospace](https://isaraerospace.com/press/history-for-european-spaceflight-isar-aerospace-reaches-orbit-and-deploys-payloads-on-second-flight)

## OpenClaw 2026.9.2 makes long-running agents more resilient

OpenClaw’s latest release moves agent continuity and responsiveness to the foreground. Long transcript preparation now stays out of the gateway’s critical event loop, while active, queued, and delegated replies can recover after restarts instead of disappearing with the interrupted process.

Version 2026.9.2 also adds GPT-6 Astra support, enables Swarm orchestration by default, and allows more agent, model, tool, browser, node, and channel settings to update without restarting. Together, these changes make persistent personal agents behave more like reliable services than fragile chat sessions.

Source: [OpenClaw v2026.9.2 release notes](https://github.com/openclaw/openclaw/releases/tag/v2026.9.2)

## Google ships Lyria 3.5 across Gemini and its API

Google’s Lyria 3.5 music model is now available globally in the Gemini app and to developers through the Gemini API and AI Studio. Google says the model produces more expressive vocals, richer arrangements, and higher-fidelity tracks.

Users can select or describe genres, choose vocal or instrumental output, start from templates, and request short or longer tracks. Availability across Gemini, Flow Music, Vids, and developer interfaces turns music generation from a specialized demo into a broadly accessible creative capability.

Source: [Google](https://blog.google/innovation-and-ai/products/gemini-app/better-tracks-lyria-gemini/)

## Gemini Spark gains hands-on control of Google Photos

Gemini Spark can now act directly on a connected Google Photos library. It can edit images, curate albums, automatically create shared collections, interpret concert flyers as calendar events, and carry out multi-stage workflows from a natural-language request.

The feature is rolling out over the next few weeks to eligible Gemini AI Pro and Ultra subscribers in the United States in English. The integration is a concrete example of personal agents crossing from answering questions into manipulating a user’s private application state—useful, but also a capability that makes permission clarity and reversible actions increasingly important.

Source: [TechCrunch](https://techcrunch.com/2026/09/04/googles-gemini-spark-can-now-manage-your-google-photos-library/)

## AI-era ASCII smuggling jumps into mass phishing

Microsoft researchers found a large phishing operation using invisible Unicode tag characters to break up financial lure words before email filters parsed them. A hunting signature originally designed to detect hidden prompt-injection content instead uncovered a conventional cybercrime campaign using the same text-layer trick.

Observed activity jumped from roughly 21,000 messages to more than 1.3 million in one day and later peaked at 2.37 million messages per weekday. The crossover matters because it shows that techniques developed around AI security can quickly migrate into ordinary evasion, forcing defenders to normalize or inspect text that humans cannot see.

Source: [Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/09/03/ascii-smuggling-crosses-over-from-ai-prompt-injection-to-phishing-evasion/)

## Nscale seeks $3.5 billion ahead of a possible IPO

British AI-infrastructure provider Nscale is reportedly discussing $3.5 billion in pre-IPO financing: $1.5 billion in convertible notes from a group of investors and another $2 billion from NVIDIA. The talks come as the two-year-old company considers a public offering later this month.

Nscale recently signed an approximately $45 billion compute agreement with Anthropic and raised a $1.1 billion Series B led by Aker, with NVIDIA participating. Its capital demands illustrate the new economics of AI infrastructure, where contracted compute capacity, power, chips, and financing are becoming tightly coupled.

Source: [TechCrunch](https://techcrunch.com/2026/09/04/ai-compute-provider-nscale-is-looking-for-3-5b-in-pre-ipo-financing/)

## Research Radar

### SkyShare: Constellation-wide Sky Sharing for LEO-Radio Astronomy Coexistence

Farzad Mehri, Dara Ron, Nishanth Sastry, Satyaki Roy, and Vijay K. Shah coordinate spot-beam scheduling across an entire constellation using orbit prediction, ITU-compliant interference modeling, and live observatory data. Evaluated against real Starlink geometries at 25 Ku-band radio-astronomy sites, SkyShare reduced unserved cells by up to 90.68% versus boresight avoidance while remaining within EPFD limits and requiring no satellite hardware changes. The paper is accepted to MobiCom 2026.

Source: [arXiv:2609.00821](https://arxiv.org/abs/2609.00821)

### Satellite Swarms for Direct-to-Cell Networks: A Distribution-Performance Trade-off Analysis

Xavier Artiga, Marius Caus, Ana I. Pérez-Neira, Yerassyl Akhmetkaziyev, and Malte Schellmann study two-dimensional distributed satellite apertures for direct-to-cell service. Larger distribution improves system sum rate and provides especially strong gains in user hotspots, but the paper also identifies relative-position errors, synchronization, beamforming, and user-location update rates as practical limits on swarm scale.

Source: [arXiv:2609.01380](https://arxiv.org/abs/2609.01380)

### On the Impact of Site-Specific Training for a Real-World 5G NR System

Reinhard Wiesmayr, Nuri Berke Baytekin, Chris Dick, and Christoph Studer evaluate three receiver architectures using measurements from a standards-compliant ETH Zurich 5G NR testbed with dual-layer uplink transmission. Site-specific fine-tuning substantially improved fully trainable and model-driven neural receivers and remained effective across campaigns separated by more than six months; the work is accepted to Asilomar 2026.

Source: [arXiv:2609.04004](https://arxiv.org/abs/2609.04004)

## Source notes

ISPreview blocked direct page extraction, so its indexed report was used for the Ofcom story. IEEE Xplore and ACM Digital Library searches did not surface stronger newly indexed papers; the research section uses fresh arXiv submissions, including papers accepted to MobiCom 2026 and Asilomar 2026. Several rotated X accounts had no substantive posts inside the 24–48 hour window, and stale items were excluded.

## Takeaway

The strongest thread is infrastructure becoming more deployable and resilient—from selective 6G spectrum and sovereign launch to restart-safe agents and better-protected AI-era communications.
