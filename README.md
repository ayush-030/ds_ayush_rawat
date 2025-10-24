# 📊 Bitcoin Market Sentiment Analysis

## 🧠 Project Overview
This project explores the relationship between **trader behavior** and the **Bitcoin Fear & Greed Index** to identify patterns that can inform smarter trading strategies.  
The analysis focuses on market sentiment trends, trading profitability, risk, and volume to understand how emotional factors influence market decisions.

---

## 📂 Datasets

- **Fear & Greed Index**
  - File: `csv_files/fear_greed_index.csv`
  - Can be downloaded from: [Google Drive link](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)
  - Columns: `timestamp`, `value`, `classification`, `date`

- **Historical Trader Data**
  - File: `csv_files/historical_data.csv` (≈45 MB)
  - ⚠️ Not included in the repo due to size constraints
  - Can be downloaded from: [Google Drive link](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)
  - Columns: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp IST`, `Start Position`, `Direction`, `Closed PnL`, `Transaction Hash`, `Order ID`, `Crossed`, `Fee`, `Trade ID`, `Timestamp`, `trade_date`  

---

## 🧪 Objectives

- Visualize daily market sentiment using the Fear & Greed Index 📈  
- Analyze patterns in trader behavior (profitability, volume, leverage) 💹  
- Identify correlations between sentiment and trading outcomes 🔍  
- Generate insights for smarter Web3 trading strategies 💡  

---

## 🛠 Tech Stack

- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, gdown
- **Environment:** Google Colab / Jupyter Notebook  

---

## 📓 Notebooks

All analysis and visualizations were performed in Google Colab. You can view the notebooks using the links below:

- **Trader Behavior Analysis Notebook:** [View in Colab](https://colab.research.google.com/drive/1f0urEkrd9Rr7I3nxGZKXKwSArjZgMzg8?usp=sharing)  

> ⚠️ **Note:** The notebooks are view-only. To run them, open the link in Google Colab.

---

## 📈 Visual Outputs

- **average_pnl_vs_sentiment.png** — Shows the relationship between average trader profit/loss and market sentiment (Fear vs Greed)
- **buy_sell_ratio_vs_sentiment.png** — Visualizes the ratio of buy vs sell trades under different sentiment conditions  
- **trading_volume_vs_sentiment.png** — Displays how trading volume varies according to market sentiment  

> These plots are also included in the **DS_Report_Ayush_Rawat.pdf** with detailed explanations.

---

## 🚀 How to Run

1. Open the notebook: `notebooks/notebook_1.ipynb` in Google Colab  
2. Ensure the datasets are in `csv_files/`  
3. Run all cells sequentially to reproduce analysis and generate plots in `outputs/`

---

## 📝 Notes

- The notebook is modular and well-commented for clarity  
- Outputs folder contains all generated visualizations  
- Historical trader data is large; a sample or full dataset can be downloaded manually

---

## 👤 Author

**Ayush Rawat**  
📧 [rawat.ayush.work@gmail.com](mailto:rawat.ayush.work@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ayushrawat20)

---

## 📌 Submission

This repository is structured as per **Primetrade.ai Data Science Internship** requirements, including:

- Structured directories (`csv_files/`, `notebooks/`, `outputs/`)  
- Professional report in PDF  
- Visual EDA outputs in PNG format  
- Colab notebook with all analysis steps
