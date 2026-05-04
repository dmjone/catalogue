# The Catalogue · dmj.one

> **Fifty-nine products. One engineer. Built for the India most software forgets.**

A working catalogue of every product built or mentored to ship under [dmj.one](https://dmj.one) since August 2022 · the entire body of work from Divya Mohan's Shoolini University journey, designed for slow phones, bad networks, and small towns where things have to actually work.

[![Live](https://img.shields.io/badge/live-dmj.one%2Fcatalogue-d8631a?style=for-the-badge)](https://dmj.one/catalogue/)
[![Products](https://img.shields.io/badge/products-59-1f3a5f?style=for-the-badge)](#the-catalogue)
[![Built for Bharat](https://img.shields.io/badge/Built%20for-Bharat-138808?style=for-the-badge)](https://dmj.one)
[![Accessibility](https://img.shields.io/badge/WCAG-2.2%20AAA-2D5A3E?style=for-the-badge)](https://www.w3.org/WAI/standards-guidelines/wcag/)
[![Licence](https://img.shields.io/badge/licence-AGPL%20v3-blue?style=for-the-badge)](LICENSE)

> **Read it live at [dmj.one/catalogue](https://dmj.one/catalogue/)** · the catalogue is deployed; this repository is the source.

---

## What is this?

This repository ships a single, static, accessibility-first product catalogue for **dmj.one** · a public welfare initiative for free, accessible computer science education and Bharat-scale software, sustained since August 2022.

The catalogue documents every shipped product across six categories:

- **Bharat-First** · twenty products built for the India that speaks twenty-two languages and lives on a ₹6,000 phone
- **AI · Agents** · twelve production multi-agent and on-device AI systems
- **Enterprise · Security** · eight post-quantum, zero-trust, military-grade security builds
- **Cloud · Infrastructure** · eight carbon-aware, audit-ready, ONDC-native cloud platforms
- **Tools** · five developer productivity tools
- **Research · Education** · six research builds, hackathons, and teaching artefacts

Every product page tells one story · the human problem, the named promise, how it works, and proof that it really exists.

## Live deployment

The catalogue is live at:

- **[dmj.one/catalogue/](https://dmj.one/catalogue/)** · the deployed catalogue (the link to share)
- **[dmj.one](https://dmj.one)** · the umbrella platform · the parent organisation that holds every product listed in this catalogue (think Alphabet to Google)

The catalogue is a single static site (HTML + CSS + a few lines of progressive-enhancement JS). To rehost a fork, drop the directory on Cloudflare Pages, GitHub Pages, Vercel, Netlify, S3, or any static host. No build step.

To preview locally:

```bash
git clone https://github.com/dmjone/catalogue.git
cd catalogue
python3 -m http.server 8000
# open http://localhost:8000
```

No build step. No bundler. No node_modules. The catalogue is plain HTML, CSS and a few lines of progressive-enhancement JavaScript · so it loads in under three seconds on a 2G connection.

## Featured products with live deployments

| Product | Lives at | What it does |
|---|---|---|
| [KisanMind](https://kisanmind.dmj.one) | kisanmind.dmj.one | Satellite-to-voice agricultural intelligence for 150 million Indian farmers |
| [Bharat eVote](https://bharat-evote.dmj.one) | bharat-evote.dmj.one | Remote, auditable, accessible voting system for Indian elections |
| [SevaSetu](https://sevasetu.dmj.one) | sevasetu.dmj.one | ONDC-connected local services marketplace for Bharat |
| [SentinelCloud](https://sentinelcloud.dmj.one) | sentinelcloud.dmj.one | Autonomous five-agent DevOps engineer with deterministic policy gates |
| [BioVault](https://biovault.dmj.one) | biovault.dmj.one | Multi-modal biometric trust score · face + voice + keystroke + WebAuthn |
| [JalSeva](https://jalseva.dmj.one) | jalseva.dmj.one | Voice-first water tanker delivery platform for the 163M Indians without clean water |
| [GharSetu](https://gharsetu.dmj.one) | gharsetu.dmj.one | ONDC-connected PG and room rental for university students |
| [GreenScale](https://greenscale.dmj.one) | greenscale.dmj.one | Carbon-aware multi-region serverless routing plane |
| [LocalPulse](https://localpulse.dmj.one) | localpulse.dmj.one | AI crisis management dashboard for small Indian communities |
| [Pratidhwani](https://pratidhwani.dmj.one) | pratidhwani.dmj.one | Predictive carbon-aware serverless gateway |
| [VerifiedTutor](https://verifiedtutor.dmj.one) | verifiedtutor.dmj.one | Faithfulness-verified Class 12 CS tutor with NLI claim-checking |
| [ResumeAI](https://astha-capstone.dmj.one) | astha-capstone.dmj.one | Three-in-one offline-first PWA · Saathi conversational builder + 9-agent screening + Bridge trust layer |
| [ShadowNotes](https://shadownotes.dmj.one) | shadownotes.dmj.one | Offline-first encrypted field intelligence app · zero data leaves device |
| [DreamBreeze](https://dreambreeze.dmj.one) | dreambreeze.dmj.one | Your phone becomes the AI sleep agent · zero hardware |
| [NFPC Mule Detection](https://nfpc.dmj.one) | nfpc.dmj.one | LightGBM × XGBoost mule account detection at 0.985 AUC-ROC |
| [Mrs Vaidya · Poetry](https://mrsvaidya.dmj.one) | mrsvaidya.dmj.one | Auto-synced Facebook poetry to a beautifully designed blog |
| [Enterprise SSO](https://sso-system-demo.dmj.one) | sso-system-demo.dmj.one | Military-grade SSO · ML-KEM-768 PQ KEM, FROST threshold, OPAQUE, FIDO2 |

[See all 59 products in the catalogue ›](#the-catalogue)

## The catalogue

### I · Bharat-First (20 products)

Voice-first. Twenty-two Indian languages. Works on a ₹6,000 phone over patchy 2G. Offline-capable. WCAG 2.2 AAA from line one. Includes capstones mentored to production.

`KisanMind` · `Janani Suraksha` · `JalSeva` · `Setu (Voice-to-ONDC)` · `GharSetu` · `Udaan` · `MindGuard` · `LocalPulse` · `JalNetra` · `BioVault` · `Pariksha Suraksha` · `Vaidya-Niti` · `HaqSetu` · `Digital Safety Labs` · `NFPC Mule Detection` · `SevaSetu` · `Bharat eVote` · `VerifiedTutor` · `RecoveryPilot` · `ResumeAI / Saathi`

### II · AI · Agents (12 products)

Multi-agent swarms, autonomous pipelines, edge-AI assistants · all production-deployed, explainable, with budgets and audit trails.

`APAC GenAI Academy` · `Claude Kanban` · `Agent Trust SDK` · `SmartEvaluator-Omni` · `NLU Bot Trainer` · `DreamBreeze` · `ShadowNotes` · `CityGuard Response Hub` · `Resha` · `RealtyAssistant` · `Scry` · `SentinelCloud`

### III · Enterprise · Security (8 products)

Post-quantum primitives, zero-trust architectures, military-grade SSO, hardened MySQL, signed PDFs.

`Enterprise SSO System` · `VSBS (Vehicle Service Booking)` · `Zero-Trust MySQL` · `Zero-Trust API Broker` · `dmj.one PDF Authenticator` · `SDN IDS Testbed` · `Compliant VM` · `Facial Surveillance`

### IV · Cloud · Infrastructure (8 products)

Carbon-aware routing, on-demand spot orchestration, ONDC-grade gateways, async workflows that survive partial failures.

`GreenScale` · `Pratidhwani` · `Async Document Workflow` · `Private Beckn Network` · `On-Demand Deployment` · `WSL Enterprise Manager` · `DevOps · DevSecOps Toolkit` · `DevOps Shell Scripts`

### V · Tools (5 products)

Sharp little things that save the day.

`DevStash` · `Facebook → Blog` · `Phone IP Finder` · `Universal Bootstrap` · `dmjone PyPI`

### VI · Research · Education (6 products)

Research builds, hackathon engineering, teaching artefacts · each shipped as a usable thing, not a slide deck.

`ECO-LENS` · `Anna-Verse 2.0` · `AWS CLF-C02 Practice` · `DIP Practical Handbook` · `dmj.one (the umbrella)` · `Personal Finance Tracker`

## Built for Bharat

Every product in this catalogue follows the same defaults:

- **Slow-phone first** · ₹6,000 phone on patchy 2G is the design target, not the edge case
- **Offline-capable** · core flows work without connectivity, sync when reachable
- **Twenty-two-language ready** · voice-first, screen-reader friendly, RTL-aware
- **WCAG 2.2 AAA** · 7:1 contrast, full keyboard nav, ARIA landmarks, reduced-motion support
- **DPDP-compliant** · India data stays in India, explicit consent, real deletion
- **Quantum-secure where it matters** · ML-KEM, ML-DSA, hybrid post-quantum primitives in the security stack
- **Production-grade only** · every page links to real source, real metrics, real deployments

## Tech across the catalogue

The 59 products span (in rough order of presence): TypeScript, Python, Rust, Bash, PowerShell, HTML, JavaScript, Java, C, C++, Jupyter; Next.js, FastAPI, Express, Hono, LangGraph, Streamlit, React 19, Vite, Tailwind; Gemini 2.5/3 Flash, Gemma 3 27b, Qwen 2.5, Whisper, Piper, ONNX Runtime, Transformers.js, SBERT, NLI Deberta-v3, Ollama; Google Cloud Run, AlloyDB, Earth Engine, Maps Platform, AlloyDB, Bhashini, Sarvam, Krutrim, Twilio, Cloudflare Workers + D1, Firebase, AMD XDNA NPU; ONDC, Beckn, FHIR R4, AgMarkNet, NASA SMAP, Sentinel-1/2, MODIS Terra; ML-KEM-768, FROST, OPAQUE, FIDO2/WebAuthn, AES-256-GCM, Argon2.

## Accessibility

The catalogue itself targets **WCAG 2.2 AAA** end-to-end:

- Skip-to-content link on every page
- Semantic HTML5 landmarks · `header`, `nav`, `main`, `section`, `article`, `footer`
- Visible focus indicators (3 px solid)
- 7:1 colour contrast minimum across the whole UI
- ARIA labels and live regions where appropriate
- Reduced-motion support · `prefers-reduced-motion: reduce` collapses every animation to 0.001ms
- Keyboard-driven filter chips with `aria-pressed` state
- No autoplay, no auto-scroll, no surprise modal interactions
- Print stylesheet for offline reading
- 44 px minimum touch targets
- Atkinson Hyperlegible body font (designed for low-vision readers)

## Performance

Every page is a single self-contained HTML file (24-46 KB) that links to one shared 8 KB CSS file. No bundlers. No runtime frameworks. No node_modules. The whole catalogue is roughly 2 MB on disk and loads in under three seconds on a 2G connection on a five-year-old phone.

## Repository layout

```
.
├── README.md            · this file
├── LICENSE              · AGPL v3
├── index.html           · the central catalogue with all 59 product cards
├── assets/
│   └── core.css         · shared design tokens, type scale, accessibility primitives
└── products/            · one self-contained HTML page per product (59 files)
    ├── kisanmind.html
    ├── janani-suraksha.html
    ├── ...
    └── personal-finance-tracker.html
```

## Licence

The catalogue itself · the HTML, the CSS, the copy, the showcase · is **AGPL v3**, matching dmj.one's educational content. Anyone forking the catalogue must keep the next student's access just as free.

**Individual products listed inside the catalogue ship under their own licences.** Most are Apache 2.0 (with patent retaliation) but each repository is the source of truth · check each one before forking.

See [LICENSE](LICENSE) for the full AGPL v3 text.

## About dmj.one

[dmj.one](https://dmj.one) is the umbrella platform behind every product in this catalogue · a public welfare initiative for free, accessible computer science education and Bharat-scale software, sustained since August 2022. Think of it the way Alphabet holds Google · the parent organisation, the welfare commitment, the open-source licence, the deploy infrastructure, the credit line for student capstones, the public face.

- Live · [https://dmj.one](https://dmj.one)
- Mission · [Aatmanirbhar Bharat by 2047](https://dmj.one)
- Founder · [Divya Mohan](https://github.com/divyamohan1993)

## Contact

- **Email** · contact@dmj.one
- **Site** · [dmj.one](https://dmj.one)
- **GitHub** · [@divyamohan1993](https://github.com/divyamohan1993) · [@dmjone](https://github.com/dmjone)
- **Based** · Solan, Himachal Pradesh, India

## Looking for a partner who ships?

Build partner, capstone mentor, founding engineer · the catalogue is the proof. If your problem is on this list, the work has already begun. If it isn't, that is exactly the kind worth starting.

→ Open an issue, or write to **contact@dmj.one**.

---

<sub>**Keywords** · dmj.one · Divya Mohan · Bharat first software · India product portfolio · ONDC products · post-quantum security · multi-agent AI · agentic AI · Aatmanirbhar Bharat · WCAG 2.2 AAA · Apache 2.0 catalogue · AGPL educational content · Shoolini University capstone · accessibility-first · voice-first AI · twenty-two Indian languages · slow-phone-first · offline-first PWA · DPDP compliant · Cloudflare Workers · Cloud Run · Gemini 3 · Gemma 3 · Bhashini · Sarvam · Krutrim · KisanMind · JalSeva · Bharat eVote · SentinelCloud · BioVault · ResumeAI</sub>
