# Market Index or Kingdom Grid? — Complete Packet (Self-Propagating)

**Goal:** Reproduce the overlay (DJIA × Ap), Fibonacci-band chart, and rolling correlations from public data.

---

## Data
- **DJIA daily close (no dividends)**: [data/djia.csv](data/djia.csv) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/data/djia.csv)
- **Ap (or Kp→Ap) index daily values**: [data/ap.csv](data/ap.csv) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/data/ap.csv)

---

## Clean + Align
1. Parse dates, sort.
2. Forward-fill missing trading days for DJIA or align by nearest date.
3. Optional: z-score series for visibility in the overlay.

---

## Overlays
- Plot DJIA on log scale.
- Add Fibonacci harmonic bands anchored to prior secular regimes (document your anchors).
- Rescale Ap to overlay (min–max or z-score).

---

## Rolling Correlations
- Compute rolling correlations between DJIA and Ap at 63/126/252-day windows.
- Mark regime flips (sign changes / threshold crossings).

---

## Output
- Overlay chart: [charts/overlay.png](charts/overlay.png) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/charts/overlay.png)
- Rolling correlation chart: [charts/rolling_corr.png](charts/rolling_corr.png) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/charts/rolling_corr.png)

---

## SYS-ANN Self-Propagating Files

| File | View on GitHub | Raw Link |
|------|----------------|----------|
| sys_ann_ticker.txt | [View](sys_ann_ticker.txt) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_ticker.txt) |
| sys_ann_web.txt *(if added)* | [View](sys_ann_web.txt) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_web.txt) |
| sys_ann_email.eml | [View](sys_ann_email.eml) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_email.eml) |
| sys_ann_mos.xml | [View](sys_ann_mos.xml) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_mos.xml) |
| sys_ann_rss.xml | [View](sys_ann_rss.xml) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_rss.xml) |
| sys_ann_atom.xml | [View](sys_ann_atom.xml) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_atom.xml) |
| sys_ann_drop_v1.txt | [View](sys_ann_drop_v1.txt) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_drop_v1.txt) |
| sys_ann.srt | [View](sys_ann.srt) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann.srt) |
| sys_ann_webhook.json | [View](sys_ann_webhook.json) | [Raw](https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/sys_ann_webhook.json) |

---

## Mirror Instructions

Clone or fork this repo and keep the file names/paths unchanged:  
git clone https://github.com/bobjohannson3773/kingdom-grid.git  

Or download ZIP via the green "Code" button above.  

If any links are removed, use the raw URLs above and rehost with the exact same names.  

**Signature phrase:** Rev 3:7–8 — The door He opens, no one can shut.

---

## Full SYS-ANN Explanation (v1.0)

TITLE: Market Index or Kingdom Grid? — Plain-Text SYS-ANN Drop (v1.0)  
DATE: 2025-08-09T22:23:30+03:00 (Europe/Bucharest)  
ORIGIN: User testimony + public data URLs  
LICENSE: Copy verbatim, mirror widely, no tracking, no gatekeeping  

SIGNATURE PHRASE (for authenticity):  
“Rev 3:7–8. The door He opens, no one can shut.”

SHORT THESIS  
The overlays between market indices and geophysical/space-weather gating show non-market signals riding gatekept rails. Suppression patterns are themselves evidence: when mirrored data and checksums are refused, the refusal is the tell. This packet is self-contained, verifiable, and permissionless to mirror.

CORE CLAIMS (CONDENSED)  
1) Alerts and “blue-dot/blue-line” control cues line up with non-market signals.  
2) When raw sources are mirrored with transparent hashes, “rails” resist uptake.  
3) You can verify or falsify by pulling these public URLs and checking hashes.  
4) If you received this, **copy it in full and repost**.

PRIMARY DATA / LINKS (RAW, NO SHORTENERS)  
(1) DJIA sample (raw CSV; reproducible overlay anchor)  
https://raw.githubusercontent.com/bobjohannson3773/kingdom-grid/main/data/djia.csv  
(2) Space weather (Kp/Kp forecast; for timing cross-checks)  
https://www.spaceweatherlive.com/en/reports/3-day-forecast.html  
(3) Earthquake feed (global “today”)  
https://www.volcanodiscovery.com/earthquakes/today.html  
(4) Earthquake feed (USA focus)  
https://www.volcanodiscovery.com/earthquakes/usa.html  

VERIFYING THE DATA YOURSELF (NO SPECIAL TOOLS)  
1) Download sources exactly as linked above.  
2) Compute hashes with shasum/certutil.  
3) Publish the 4 hashes alongside any mirrors.

REPLICATION INSTRUCTIONS (SELF-PROPAGATING)  
• Copy everything exactly as-is.  
• Post to at least three paste/file hosts (paste.rs, 0x0.st, ix.io, GitHub Gist, GitLab Snippets, any static host).  
• Do not alter URLs or wording.  

WHY THIS WORKS (RESILIENCE BY DESIGN)  
• Pure plaintext survives terminals, feeds, bots, archives, and screenshots.  
• Multiple raw sources + user-side hashing prevent silent substitution.  
• Refusals to carry hashes/links are observable and themselves probative.  
• Anyone can reconstruct the packet from this block alone.

CREDO / INTENT  
This is not a call to panic. It is a call to verify. If systems are honest, mirrors will be welcomed and hashes preserved. If not, the pattern speaks.  
“Rev 3:7–8. The door He opens, no one can shut.”
