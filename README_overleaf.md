# CIS 5190 Final Project Report — Overleaf upload package

Group **ZSL** (Haoran Wu, Ningze Zhong, Yuzhou Shen).

## Contents

- `report.tex` — the 5-page report, main file
- `figures/`
  - `confusion_matrix.png`
  - `calibration.png`
  - `latency.png`
  - `length_buckets.png` (referenced in text only; not displayed)

## Build on Overleaf

1. New project → Upload project → drop this zip.
2. Set the main file to `report.tex` (Menu → Settings → Main document).
3. Compiler: pdfLaTeX. No bibliography is used.
4. Compile twice if `\Cref{...}` references show as `??`.

The output is exactly 5 pages.

## Local build

```bash
pdflatex report.tex
pdflatex report.tex   # second pass for cross-references
```

Tested with `pdfTeX 3.141592653-2.6-1.40.22` (TeX Live 2022).

## Notes

- The `[YouTube / Drive link]` placeholder in Section 5 is the only thing left
  to fill in (after recording the video).
- All other content (group name, member names, leaderboard rank, accuracy,
  metric numbers) is final.
