# F1 Telemetry Analysis

Performance analyses of Formula 1 races using FastF1 telemetry data.
Portfolio project focused on lap comparison, delta decomposition, and driving style identification.

## Analyses

### Monaco Q3 2024 — Leclerc vs Sainz

Decomposition of Leclerc's 0.248s advantage over Sainz in Q3 qualifying.

**Key findings:**
- The spectacular delta spike at T6 is misleading — both drivers' styles compensate each other in this slow corner sequence
- The actual gap is built in two medium-speed corners: T3 (0.15s) and T18 (0.10s)
- In medium-speed corners, Leclerc's late-braking style generates a net gain that Sainz cannot recover on exit; in slow corners, the same style is neutralized

![Speed and Delta Comparison](outputs/speed_delta_comparison.png)

📓 [Full notebook](notebooks/monaco_q3_2024_LEC_vs_SAI.ipynb)

## Tech Stack

- **Python 3.10+**
- **FastF1** — F1 telemetry data extraction
- **pandas** — data processing
- **matplotlib** — visualizations

## Reproduce locally

```bash
git clone https://github.com/YOUR-USERNAME/f1-telemetry-analysis.git
cd f1-telemetry-analysis
pip install -r requirements.txt
jupyter notebook
```

## About

Engineering student building a portfolio of F1 performance analyses.
Currently applying for internships in F1 performance / vehicle dynamics engineering.

📧 Contact: [your email or LinkedIn]
