# How Do You Compare? — Real Fitness & Biometric Data

**How does your body actually compare to 13,393 real people?**

🔗 **Try it live:** https://thanuhith.github.io/real-body-data-compare/

## What this is

Drag your own numbers into six real physical and biometric measurements, and instantly see where you land against a dataset of **13,393 real people** — not averages someone made up, actual recorded data.

## The data

- **Source:** Korea Sports Promotion Foundation fitness assessments
- **Size:** 13,393 people (8,467 men, 4,926 women)
- **Publicly released and fully anonymized** — no personal identifying information

## Metrics compared

| Metric | Type |
|---|---|
| Body fat % | 🧬 Biotech |
| Systolic blood pressure | 🧬 Biotech |
| Grip strength | 💪 Fitness |
| Sit-ups (1 min) | 💪 Fitness |
| Broad jump | 💪 Fitness |
| Sit & reach flexibility | 💪 Fitness |

Each slider shows a live histogram of the real population split by gender, with your value plotted against it in real time, and your estimated percentile.

## Accuracy note

Percentiles are calculated from **binned histogram data** (22 bins per metric), not the raw 13,393 rows individually — so results are close estimates (±2–3%), not exact lab-grade percentiles.

## Tech

Single self-contained HTML file — no dependencies, no backend, no build step. Data is pre-processed from the public dataset and embedded directly in the page.

## Disclaimer

This is an educational comparison tool, not a medical assessment or diagnostic tool. For health concerns, talk to a professional.

## License

Free and open source — fork it, remix it, use it however you like.
