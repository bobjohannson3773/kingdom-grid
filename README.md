# Market Index or Kingdom Grid? — Replication Steps

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
