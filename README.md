# Polymarket Insider Trading — Investigative Dashboard

A data-driven visual analysis of systematic information advantages in political prediction markets, with particular focus on pre-announcement trading surges correlated with Trump administration policy events.

---

## 🚀 Open the Colab Notebook

### Method 1 — One-click (recommended)

Click the badge below — it opens the notebook directly in Google Colab with no setup:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MarkArenSangha/Polymarket-Project/blob/main/Polymarket_Insider_Trading.ipynb)

Or paste this URL into your browser:
```
https://colab.research.google.com/github/MarkArenSangha/Polymarket-Project/blob/main/Polymarket_Insider_Trading.ipynb
```

### Method 2 — Download the raw file (avoid the HTML trap)

> ⚠️ **Do NOT right-click → Save As on the GitHub page — that saves the HTML preview.**

1. Use this direct raw download link instead:
   ```
   https://raw.githubusercontent.com/MarkArenSangha/Polymarket-Project/main/Polymarket_Insider_Trading.ipynb
   ```
2. Your browser will show raw JSON text — press **Ctrl+S** (or Cmd+S) and save as `Polymarket_Insider_Trading.ipynb` (make sure the extension is `.ipynb`, not `.txt` or `.html`)
3. Go to [colab.research.google.com](https://colab.research.google.com)
4. Click **File → Upload notebook** → select the saved `.ipynb` file
5. Click **Runtime → Run all**

### Method 3 — From inside Colab (GitHub tab)

1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Open notebook**
3. Select the **GitHub** tab
4. Type `MarkArenSangha/Polymarket-Project` and press Enter
5. Branch is `main` — click `Polymarket_Insider_Trading.ipynb`
6. Click **Runtime → Run all**

---

## 🖥️ Live HTML Dashboard

Open `index.html` in any browser — no build step required.  
Enable GitHub Pages on this branch to publish it publicly.

## What the Dashboard Shows

| Section | Visualization | Key Finding |
|---------|--------------|-------------|
| §1 Pre-announcement surge | Bar chart (T−72h → T+12h) | Volume spikes **2,847%** above baseline at T−30 min |
| §2 Case studies | Dual-axis combo charts | Liberation Day & 90-day tariff pause — price moves from <15¢ to >99¢ in under 1 hour |
| §3 Wallet fingerprinting | Horizontal bar + bubble scatter | Flagged wallets average **89.3% win rate** vs 50% expected |
| §4 Statistical proof | Normal distribution overlay | Observed pattern is **7.4 standard deviations** from random |
| §5 Timeline & monthly | Combo bar/line chart | Suspicious volume grew from $120K/month (Jan 2024) to $2.1M/month (Apr 2025) |
| §6 Heatmap | D3 calendar heatmap | Activity concentrates in 14:00–16:00 ET window on weekdays |
| §7 Composition | Donut + radar + histogram | Flagged wallets cluster in >100% return bucket; average trader does not |

## Highlighted Events

- **April 9, 2025** — $3.8M placed on "tariff pause" 45 minutes before Trump's Truth Social post. Market: 9¢ → 99¢.
- **April 2, 2025** — $2.1M bought into tariff markets 2 hours before "Liberation Day" announcement. Market: 42¢ → 99¢.
- **January 20, 2025** — Executive-order prediction markets front-run before each signing ceremony.
- **November 5, 2024** — $6M+ shifted into Trump election-winner markets before networks called swing states.

## Technology

- **Chart.js 4.4** — bar, line, bubble, donut, radar charts
- **D3.js 7** — interactive heatmap with hover tooltips
- **chartjs-plugin-annotation** — surge-window overlays
- **Space Grotesk + JetBrains Mono** — typography
- Zero dependencies to install — all loaded via CDN

## Methodology

Statistical anomaly detection using z-score analysis of win rates across 247 flagged events. Temporal clustering analysis identifies trades placed within ±60 minutes of announcements. Wallet graph correlation links addresses by co-trading patterns and on-chain fund flows.

> **Disclaimer:** This analysis uses publicly available on-chain transaction data and publicly reported market activity for educational and research purposes only.
