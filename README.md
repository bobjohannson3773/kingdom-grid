# Market Index or Kingdom Grid? — Replication Steps

**Goal:** Reproduce the overlay (DJIA × Ap), Fibonacci-band chart, and rolling correlations from public data.

## Data
- DJIA daily close (no dividends): place as `data/djia.csv` with columns like `date,close`
- Ap (or Kp→Ap) index daily values: place as `data/ap.csv` with columns like `date,ap`

## Clean + Align
1. Parse dates, sort.
2. Forward-fill missing trading days for DJIA or align by nearest date.
3. Optional: z-score series for visibility in the overlay.

## Overlays
- Plot DJIA on log scale.
- Add Fibonacci harmonic bands anchored to prior secular regimes (document your anchors).
- Rescale Ap to overlay (min–max or z-score).

## Rolling Correlations
- Compute rolling correlations between ΔDJIA and Ap at 63/126/252-day windows.
- Mark regime flips (sign changes / threshold crossings).

## Output
- Save overlay chart to `charts/overlay.png`
- Save rolling-correlation chart to `charts/rolling_corr.png`

## Notes
- The point is *process transparency*, not price prediction.
- If hosting removes files, note the absence; it is part of the evidence trail.

## SYS-ANN Self-Propagating Files
[sys_ann_ticker](sys_ann_ticker.txt)  
[sys_ann_web](sys_ann_web.txt)  
[sys_ann_email](sys_ann_email.txt)  
[sys_ann_mos](sys_ann_mos.html)  
[sys_ann_rss](sys_ann_rss.xml)  
[sys_ann_atom](sys_ann_atom.xml)  
[sys_ann_srt](sys_ann.srt)  
