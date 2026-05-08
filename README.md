# Polymarket Insider Trading: A Quantitative Investigation

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MarkArenSangha/Polymarket-Project/blob/main/Polymarket_Insider_Trading.ipynb)

Statistical and visual evidence of structured information advantages operating across two markets: decentralised political prediction markets (Polymarket) and U.S. congressional equity trading. All data is synthetic but calibrated to documented empirical patterns.

---

## Contents

**Part I -- Pre-Announcement Volume Anomalies in Political Prediction Markets**

| Section | Title |
|---------|-------|
| 1.1 | Anatomy of a Pre-Announcement Surge |
| 1.2 | 3-D Volume Surface: Time x Contract x Intensity |
| 1.3 | Statistical Distribution of Pre-Announcement Returns |
| 1.4 | Order-Flow Imbalance Polar Clock |
| 1.5 | Hexbin Density: Contract Price vs. Volume |
| 1.6 | Wallet Clustering: Network of Correlated Accounts |
| 1.7 | Event Study: Cumulative Abnormal Returns |

**Part II -- Systematic Information Advantages in Congressional Trading**

| Section | Title |
|---------|-------|
| 2.1 | Congressional Trade Timeline Around Key Votes |
| 2.2 | Cumulative Portfolio Return: Congress vs. Benchmarks |
| 2.3 | Committee x Sector Trade Concentration Heatmap |
| 2.4 | Trade Volume Streamgraph by Political Party |
| 2.5 | STOCK Act Disclosure Delay Distribution |
| 2.6 | Pre-Legislation Trade Network |
| 2.7 | Alpha Generation by Committee Membership |

---

## Key Findings

| Finding | Metric |
|---------|--------|
| Pre-announcement volume spike | 3-5x baseline in final 24 hours |
| Informed wallet excess return | +12-28% per event |
| Congress vs. S&P 500 alpha | +8.4 pp/year average |
| Committee chair alpha | +18.7 pp/year |
| Median STOCK Act delay | 41 days (near statutory limit) |
| Late disclosures | ~18% of all reported trades |

---

## Methodology

- **Data:** Synthetic, calibrated to published academic literature on political prediction markets and congressional trading.
- **Event windows:** Defined relative to announcement or legislative vote date (T = 0).
- **Benchmarks:** S&P 500 total return used as passive baseline throughout Part II.
- **Network analysis:** Barabasi-Albert (Part I) and Watts-Strogatz (Part II) random graph models used to simulate wallet correlation structures.

## Dependencies

```
numpy pandas matplotlib scipy networkx seaborn
```

Install via: `pip install numpy pandas matplotlib scipy networkx seaborn`

---

**Disclaimer:** All data in this notebook is synthetically generated. No individual is identified or accused of any offence. This analysis is produced for educational and research purposes only.
