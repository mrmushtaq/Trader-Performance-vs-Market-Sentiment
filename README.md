# Trader Performance vs Market Sentiment

## Project Overview
This project analyzes how **Bitcoin market sentiment** (Fear/Greed Index) relates to trader behavior and performance on **Hyperliquid**, a decentralized perpetuals exchange. The goal is to uncover actionable patterns that can inform smarter trading strategies.

---

## Key Questions Explored
- Do traders perform better during **Fear** or **Greed** market conditions?
- How does sentiment affect **win rate** across different risk segments?
- What is the relationship between sentiment and **average PnL**?

---

## Project Structure
```
Trader Performance vs Market Sentiment/
│
├── Data/
│   ├── fear_greed_index.csv        # Bitcoin Fear/Greed Index data
│   └── historical_data.csv         # Hyperliquid historical trade data
│
├── outputs/
│   ├── charts/
│   │   ├── avg_pnl_by_sentiment.png
│   │   └── win_rate_by_risk_segment.png
│   └── tables/
│       ├── daily_metrics.csv
│       └── win_rate_by_risk_segment.csv
│
├── Analysis.ipynb                  # Main analysis notebook
├── AnalysisOfProject.ipynb         # Detailed project analysis
├── Project.ipynb                   # Project summary notebook
└── README.md
```

---

## Datasets

### 1. Bitcoin Market Sentiment (Fear/Greed Index)
- **Columns:** Date, Classification (Fear / Greed / Extreme Fear / Extreme Greed)
- **Source:** [Google Drive](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

### 2. Historical Trader Data (Hyperliquid)
- **Columns:** Account, Symbol, Execution Price, Trade Size, Side, Timestamps, Closed PnL, Trade ID, etc.
- **Source:** [Google Drive](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

---

## Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/mrmushtaq/Trader-Performance-vs-Market-Sentiment.git
cd Trader-Performance-vs-Market-Sentiment
```

2. **Install dependencies:**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. **Run the notebooks:**
```bash
jupyter notebook
```
Open `Analysis.ipynb` or `Project.ipynb` to explore the analysis.

---

## Key Findings
- **Win rate** and **average PnL** vary significantly across Fear vs Greed market conditions.
- Risk segmentation reveals distinct trader behavior patterns depending on sentiment.
- Sentiment-aware strategies may offer an edge over sentiment-agnostic approaches.

---

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Source:** Hyperliquid DEX + Alternative.me Fear & Greed Index

---

## Author
**Mushtaque Alee**  
[GitHub](https://github.com/mrmushtaq)
