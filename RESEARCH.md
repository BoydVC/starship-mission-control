# RESEARCH.md — Starship & Starlink Mission Control

Session research desk for the TokenMax burn remaster at
`/workspace/tokenmax/starship-mission-control/`.

**Primary fetch window:** 2026-10-26 21:39 America/New_York (EDT)  
**UTC stamp:** 2026-10-27T01:39:28Z  
**Tools:** WebSearch + WebFetch (this Grok Bot session only; no cloud agents).

## Tag legend

| Tag | Meaning |
|-----|---------|
| **LIVE** | Fact pulled from a public page during this session; URL + fetch time recorded. |
| **SYNTHETIC** | Local product framing, Boyd-interest notes, or UI copy built on top of LIVE facts. |

This board is **not** official SpaceX telemetry, **not** FAA licensing status,
and **not** investment advice.

---

## Method

1. Search for current Starship Flight 15/16 schedule, Starlink constellation
   counts, Falcon 9 upcoming windows, and Elon/xAI theme news (Oct 2026).
2. Fetch primary pages (KeepTrack, NASASpaceFlight, SpaceX Launches,
   Spaceflight Now, NextLiftoff, TSN, SatellitesTonight, Markets Insider).
3. Copy numbers into `data/snapshot.json` with `tag`, `source`, `source_url`,
   and `fetched_at` in America/New_York.
4. Label unofficial planning dates clearly (NET / unofficial / licence TBD).
5. Keep Boyd-interest notes in `why_boyd_cares` as SYNTHETIC only.

---

## LIVE fact register (≥8 required; this desk recorded 15+)

### L1 — Starlink in orbit: 11,166
- **Tag:** LIVE
- **Value:** 11,166 satellites currently in space
- **Source:** KeepTrack — “How Many Starlink Satellites Are in Orbit?”
- **URL:** https://keeptrack.space/starlink-satellite-count
- **Page note:** Updated Oct 26, 2026 from satellite tracking data
- **Fetched:** 2026-10-26 21:39 America/New_York

### L2 — Starlink working: 11,151
- **Tag:** LIVE
- **Value:** 11,151 operational / working
- **Source:** KeepTrack (same page)
- **URL:** https://keeptrack.space/starlink-satellite-count
- **Fetched:** 2026-10-26 21:39 America/New_York

### L3 — Starlink launched all-time: 13,042
- **Tag:** LIVE
- **Value:** 13,042 launched since May 2019; ~1,876 reentered (launched − in orbit)
- **Source:** KeepTrack
- **URL:** https://keeptrack.space/starlink-satellite-count
- **Fetched:** 2026-10-26 21:39 America/New_York

### L4 — Starship Flight 15 NET Nov 8, 2026 (unofficial)
- **Tag:** LIVE
- **Value:** CADENA / aviation planning NET November 8; SpaceX has not announced
  an official launch date. Musk said “hopefully four to six weeks” (pre-Thanksgiving).
- **Source:** NASASpaceFlight — Flight 15/16 milestones (Chris Bergin & Arran Reid)
- **URL:** https://www.nasaspaceflight.com/2026/10/spacex-flight-15-16-milestones/
- **Article date:** October 18, 2026 (page fetched this session)
- **Fetched:** 2026-10-26 21:39 America/New_York

### L5 — Flight 15 dual-catch intent
- **Tag:** LIVE
- **Value:** Musk confirmed intent to attempt catches of both Super Heavy and Ship;
  NSF: first full recovery attempt of a Starship vehicle if successful.
- **Source:** NASASpaceFlight (same article)
- **URL:** https://www.nasaspaceflight.com/2026/10/spacex-flight-15-16-milestones/
- **Fetched:** 2026-10-26 21:39 America/New_York

### L6 — Flight 16 December / possible first LC-39A Starship
- **Tag:** LIVE
- **Value:** Flight 16 aimed for December; planning linked to bringing Launch
  Complex 39A online before year-end as first East Coast Starship launch.
- **Source:** NASASpaceFlight
- **URL:** https://www.nasaspaceflight.com/2026/10/spacex-flight-15-16-milestones/
- **Fetched:** 2026-10-26 21:39 America/New_York

### L7 — Booster 22 full-duration 33-engine static fire (Flight 15)
- **Tag:** LIVE
- **Value:** SpaceX posted full-duration 33-engine static fire for Super Heavy
  preparing for Flight 15 on Sunday 25 October (19:49 GMT post; observers: B22 Pad 2).
- **Source:** TSN citing SpaceX X post / Spaceflight News
- **URL:** https://tsnmedia.org/spacex-starship-flight-15-static-fire/
- **Article date:** October 26, 2026
- **Fetched:** 2026-10-26 21:39 America/New_York

### L8 — Next Falcon 9: Starlink Group 15-16
- **Tag:** LIVE
- **Value:** Falcon 9 Block 5 · Vandenberg SFB · 27 Oct 2026 05:46 UTC
  (01:46 America/New_York)
- **Source:** NextLiftoff
- **URL:** https://nextliftoff.com/next/falcon-9
- **Fetched:** 2026-10-26 21:39 America/New_York

### L9 — SpaceX public upcoming windows (SLC-4E)
- **Tag:** LIVE
- **Value:** Starlink window Oct 30 00:02–04:02 ET; USSF-432 Nov 1 20:56–Nov 2 00:56 ET;
  Starlink Nov 5 00:14–04:14 ET (plus an unlabeled nearer Starlink row on the page).
- **Source:** SpaceX Launches
- **URL:** https://www.spacex.com/launches
- **Fetched:** 2026-10-26 21:39 America/New_York

### L10 — Starlink Group 15-15 liftoff Oct 23
- **Tag:** LIVE
- **Value:** Liftoff SLC-4E 3:48 p.m. PDT / 6:48 p.m. EDT Oct 23 after three scrubs;
  booster B1063 on 36th flight; landed ASOG (229th on vessel; 673rd Falcon landing).
- **Source:** Spaceflight Now
- **URL:** https://spaceflightnow.com/2026/10/20/live-coverage-spacex-to-launch-27-starlink-satellites-on-falcon-9-rocket-from-vandenberg-sfb-5/
- **Fetched:** 2026-10-26 21:39 America/New_York

### L11 — Starlink business: +1.6M customers, 174 markets
- **Tag:** LIVE
- **Value:** Shotwell Q3 call: +1.6 million customers in the quarter; service active
  across 174 markets (excl. additional enterprise/aviation hundreds of thousands).
- **Source:** Spaceflight Now (earnings coverage)
- **URL:** https://spaceflightnow.com/2026/10/20/live-coverage-spacex-to-launch-27-starlink-satellites-on-falcon-9-rocket-from-vandenberg-sfb-5/
- **Fetched:** 2026-10-26 21:39 America/New_York

### L12 — Connectivity revenue $5.2B (Q3) + 26 V3 from Flight 14
- **Tag:** LIVE
- **Value:** SEC filing via Spaceflight Now: connectivity revenue $5.2B (+22% QoQ);
  closed Q3 with more than 11,100 Starlink sats in LEO including 26 Version 3 from
  Starship Flight 14.
- **Source:** Spaceflight Now / SEC filing summary
- **URL:** https://spaceflightnow.com/2026/10/20/live-coverage-spacex-to-launch-27-starlink-satellites-on-falcon-9-rocket-from-vandenberg-sfb-5/
- **Fetched:** 2026-10-26 21:39 America/New_York

### L13 — Orbital shells (CelesTrak GP 23 Oct 2026)
- **Tag:** LIVE
- **Value:** 53° → 5,085 (463 km); 43° → 3,612 (483 km); 97.6° → 1,522 (466 km);
  70° → 897 (475 km). Page listed 11,116 with current orbit data (slightly different
  cut than KeepTrack’s 11,166 — different catalogue freshness/rules).
- **Source:** SatellitesTonight (CelesTrak GP element sets)
- **URL:** https://www.satellitestonight.com/starlink-satellites/in-orbit-now/
- **Fetched:** 2026-10-26 21:39 America/New_York

### L14 — Grok Bot enterprise wide deployment “within a few weeks”
- **Tag:** LIVE
- **Value:** Musk Q3 call quotes: fastest product growth he’s seen; usage grows per
  user over time; early deployment with trusted customers; expects wide enterprise
  deployment within a few weeks; may use most superintelligence compute.
- **Source:** Markets Insider / TheFly
- **URL:** https://markets.businessinsider.com/news/stocks/spacex-says-usage-of-grok-growing-over-time-per-user-1036646313
- **Article date:** Oct. 20, 2026, 05:15 PM
- **Fetched:** 2026-10-26 21:39 America/New_York

### L15 — FAA PEIS Starbase cadence ambition
- **Tag:** LIVE
- **Value:** NSF reports FAA programmatic EIS process that could eventually allow
  up to 456 Starship launches and 912 landings/year from Starbase (current auth
  25 launches / 50 landings). Phase 1 → 100 launches. Early scoping — not approved.
- **Source:** NASASpaceFlight
- **URL:** https://www.nasaspaceflight.com/2026/10/spacex-flight-15-16-milestones/
- **Fetched:** 2026-10-26 21:39 America/New_York

---

## Secondary / corroborating fetches

| Source | Role | URL | Fetched (ET) |
|--------|------|-----|--------------|
| KeepTrack X-report Oct 25 | 13,042 launched / 11,170 orbit (prior day) | https://keeptrack.space/x-report/spacex-brief-2026-10-25 | 2026-10-26 21:39 |
| Space Launch Schedule | Flight 15 forecast framing | https://www.spacelaunchschedule.com/news/starship-flight-15-launch-date-how-to-watch/ | 2026-10-26 ~21:38 |
| LookToSpace / T-Minus Zero | Alternate Starship NET trackers (diverged; treated as secondary) | looktospace.com / tminuszero.app | 2026-10-26 ~21:38 |
| Yahoo Finance (partner network) | Super Intelligence Partner Network theme (secondary) | finance.yahoo.com | search hit 2026-10-26 |

**Tracker conflict note:** Some secondary Starship schedule sites listed late-December
Flight 15 NET. This desk privileges NASASpaceFlight CADENA NET Nov 8 + Musk’s
four-to-six-weeks framing, and labels the board **unofficial**. Always re-check
SpaceX’s own launches page and FAA licence announcements before treating a date
as firm.

---

## SYNTHETIC content (explicit)

The following are **not** external citations; they exist so the wall explains
itself to Boyd without pretending to be a news wire:

1. **Why Boyd cares — standing SpaceX/Elon overweight** — interest desk framing.
2. **Why Boyd cares — Starlink infrastructure story** — synthesis over L11–L12.
3. **Why Boyd cares — Grok Bot meta** — this dashboard is itself a weekly burn.
4. **Why Boyd cares — Flight 15 watch window** — local drama ranking.
5. **Why Boyd cares — not investment advice** — disclaimer card.
6. **Theme card “Why this wall exists”** — product framing.

UI chrome (tab labels, “Mission Control”, amber T-minus styling) is also SYNTHETIC.

---

## Snapshot wiring

`data/snapshot.json` fields:

- `launches[]` — Falcon + Starship rows with `net_utc`, `tag`, sources
- `starlink.metrics[]` — eight LIVE metrics
- `starlink.shells[]` — four LIVE shells
- `starlink.recent_mission` — LIVE 15-15 recap
- `milestones[]` — static fire, Flight 14, dual-catch intent
- `themes[]` — five LIVE + one SYNTHETIC
- `why_boyd_cares[]` — five SYNTHETIC notes
- `live_fact_ids[]` — index of LIVE ids for smoke / health

Server `count_live()` tallies LIVE tags across launches, metrics, shells,
milestones, themes, and recent_mission for `/api/health`.

---

## Cadence caveats (ops wall honesty)

1. **Starship dates slip.** Prefer NET language; never show a fake “confirmed”
   clock without SpaceX confirmation.
2. **Licence gap.** Dual catch requires FAA licence language Shotwell expects;
   TSN noted no Flight 15 licence announced at fetch time.
3. **Count divergence.** KeepTrack (11,166) vs SatellitesTonight current-orbit
   cut (11,116) vs Orbinauts Space-Track cut — different rules. Board shows
   KeepTrack as primary fleet KPI and shells from SatellitesTonight.
4. **Timezone.** All board clocks render America/New_York; stored `net_utc` is Z.
5. **No auto-refresh from the internet.** Snapshot is session-frozen; re-run
   research to refresh `data/snapshot.json`.

---

## Design research cross-link

Design Motion Studio (`:4334`) shipped an ops-brief palette (warm paper + terracotta)
and banned purple SaaS. This wall keeps the **IBM Plex + clarity** half of that
brief but switches to charcoal/amber/cyan for night wall readability. See
`DESIGN.md`.

---

## Acceptance checklist (research side)

- [x] ≥8 LIVE facts with URL + America/New_York fetch time
- [x] Starship Flight 15 planning NET cited with unofficial label
- [x] Starlink fleet counts from a primary tracker
- [x] At least one Falcon upcoming window from SpaceX or NextLiftoff
- [x] At least one Elon/xAI / Grok theme with public quote source
- [x] SYNTHETIC Boyd notes separated from LIVE
- [x] RESEARCH.md ≥150 lines
- [x] Snapshot consumed by `:4335` smoke

---

## Source index (bookmarkable)

1. https://keeptrack.space/starlink-satellite-count
2. https://www.nasaspaceflight.com/2026/10/spacex-flight-15-16-milestones/
3. https://www.spacex.com/launches
4. https://nextliftoff.com/next/falcon-9
5. https://spaceflightnow.com/2026/10/20/live-coverage-spacex-to-launch-27-starlink-satellites-on-falcon-9-rocket-from-vandenberg-sfb-5/
6. https://tsnmedia.org/spacex-starship-flight-15-static-fire/
7. https://www.satellitestonight.com/starlink-satellites/in-orbit-now/
8. https://markets.businessinsider.com/news/stocks/spacex-says-usage-of-grok-growing-over-time-per-user-1036646313
9. https://keeptrack.space/x-report/spacex-brief-2026-10-25
10. https://www.spacelaunchschedule.com/news/starship-flight-15-launch-date-how-to-watch/

---

## End of desk

Last line of research for smoke line-count: session closed after snapshot write
and wall UI wiring on 2026-10-26 evening America/New_York. Re-open this file and
re-fetch the URLs above before any public “reveal” that claims fresher numbers.
