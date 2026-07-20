# CoreOS FY27 OKRs — Compared (Merged)

**Merged view:** CoreOS FY27 OKR set aligned to the live RoB tracker structure — 4 pillars, 6 objectives, 15 KRs — with **owners (DRIs)** and **Aug 2026 status** per KR. Targets still marked `*` = **TBV** pending baseline verification.

- **Reference tracker:** [Windows OS Platform · FY27 RoB](https://didactic-journey-wn5j121.pages.github.io/#/fy27-okrs)
- **Strategy doc:** [CoreOS Windows OS Platform FY27 Strategy.docx](https://microsoft.sharepoint-df.com/teams/AEPWindowsPlanning/_layouts/15/Doc.aspx?sourcedoc=%7B5DA62D23-4A29-403A-BA02-756454093318%7D&file=CoreOS%20Windows%20OS%20Platform%20FY27%20Strategy.docx)
- **Merged:** 2026-07-19

## Merged from live tracker
- Added **SFI/MSRCs (due to AI)** as its own KR under O1 · fixed **SRV → SFI**.
- Promoted **Neo compete** to its own objective under Win vs Mac (Memory Mgmt + MPTF as its 2 KRs).
- Reframed **Cross-Device** KR to tracker scope: "Apple AWDL, Intel-Based Windows, EOY 2026."
- Added **Owner (DRI)** column and **Status** chip from the Aug 2026 tracker view.

## Roll-up

| Pillars | Objectives | KRs | On Track | At Risk | Awaiting |
|---|---|---|---|---|---|
| 4 | 6 | 15 | 10 | 3 | 2 |

---

## Pillar 1 — Fundamentals & Craft (6 KRs)

### O1. Deliver the most reliable and secure Windows OS platform.

| # | Key Result | Target | Owner (DRI) | Status |
|---|---|---|---|---|
| KR1.1 | **SFI/MSRCs (due to AI)** | FY27 `*` | TBD | Awaiting |
| KR1.2 | **DQI:** Migrate new 3P kernel drivers to user mode / class drivers. | 52% by EOY CY27 `*` | Aacer Dakan | On Track |
| KR1.3 | **DQI:** Move client security drivers out of kernel — WESP adoption by Defender AV, CrowdStrike, and ≥5 vendors. | By end of CY27 `*` | Tom Lavoy | On Track |
| KR1.4 | **DQI:** Establish DQM as ecosystem-wide quality baseline. | By 27H2 `*` | Krishna Srinivasa Raghavan | On Track |

### O2. Lead in OS fundamentals.

| # | Key Result | Target | Owner (DRI) | Status |
|---|---|---|---|---|
| KR2.1 | **IO Perf:** ReFS + Storage Spaces boot (opt-in): 80% faster copies, up to 20% disk savings. | FY27 `*` | Shelby Unger | On Track |
| KR2.2 | **Power/Battery:** Successful instant resume on Windows 11 devices. | ≥90% by end FY27 `*` | Ellen McGee | On Track |

---

## Pillar 2 — Win vs Mac (6 KRs)

### O3. Windows OS platform powers diverse silicon, devices, and peripherals to win back PC market leadership.

| # | Key Result | Target | Owner (DRI) | Status |
|---|---|---|---|---|
| KR3.1 | **UMA / Intelligent Carveout:** memory sharing between CPU and GPU for AI. | Phase 1 static: 2026.8D; Phase 2 dynamic: 2027.2D `*` | Marc Sweetgall | On Track |
| KR3.2 | **Silicon:** OS Platform for new silicon (Intel, AMD, QC, NV). | Holiday '27 + early '28 `*` | Sandip Hiray, Sydney Hsing-I Dowdell, Marc Sweetgall | Awaiting |
| KR3.3 | **Cross-Device:** File sharing for Apple devices (AWDL, Intel-Based Windows only). | EOY 2026 `*` | Dhanya Nair | **At Risk** |
| KR3.4 | **Trusted Gaming Platform:** TGVM at GDC '27 with ≥1 ISV; MVP for NVIDIA RTX 50 dGPU on Intel & AMD. | GDC '27; 27H2 MVP `*` | Chanpreet Dhanjal | **At Risk** |

### O4. Neo compete: fast and responsive on low memory, power and cost devices.

| # | Key Result | Target | Owner (DRI) | Status |
|---|---|---|---|---|
| KR4.1 | **Memory Management:** OS memory-footprint reduction for 8GB RAM configuration. | October 2026 GA `*` | Emily Wilson | On Track |
| KR4.2 | **MPTF:** standardized power + thermal framework, targeting QC Triberg. | 27H2 `*` | Michelle Liu | On Track |

---

## Pillar 3 — Transition to Cloud (1 KR)

### O5. Windows OS platform enables seamless cloud-connected experiences.

| # | Key Result | Target | Owner (DRI) | Status |
|---|---|---|---|---|
| KR5.1 | **Cloud PC:** OS Platform for **Tiete**. | Fall 2026 preview; April 2027 GA `*` | Jeffrey Song | **At Risk** |

---

## Pillar 4 — Land AI Value (2 KRs)

### O6. Windows OS platform enables AI experience from device to developer experiences.

| # | Key Result | Target | Owner (DRI) | Status |
|---|---|---|---|---|
| KR6.1 | **Windows Devices for AI:** DGX Station / GB300 Windows devices with Dell, HP, ASUS. | Fall 2026 shipping `*` | Marc Sweetgall | On Track |
| KR6.2 | **WSL:** USB pass-through, Networking, Containers. | End of CY26 `*` | Ugan Sivagnanenthirarajah | On Track |

---

*Legend: `*` = **TBV** (to be verified) — target from strategy doc; baseline not yet vetted against telemetry/data.*
