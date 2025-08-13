# Data Science Assignment Web3 Trading Team  
**Candidate Name:** Aastik Sonkar  
**Project Title:** Market Sentiment vs Trader Behavior Analysis  

---

## **1. Overview**  
This project analyzes the relationship between trader behavior (profitability, risk, volume, leverage) and overall market sentiment (Fear vs Greed) using two datasets:  
- **Bitcoin Market Sentiment Dataset** (Fear & Greed Index)  
- **Historical Trader Data from Hyperliquid**  

The goal is to identify patterns, correlations, and potential trading signals that can guide smarter decision-making in Web3 markets.  

---

## **2. Repository Structure**  

---

## **3. Data Sources**  
1. **Historical Trader Data:** [Google Drive Link](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)  
2. **Fear & Greed Index:** [Google Drive Link](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_mnrYv_nhSf/view?usp=sharing)  

---

## **4. Analysis Workflow**  
1. **Data Cleaning & Preprocessing:** Handled missing values, converted data types, and merged datasets on `Date`.  
2. **Exploratory Data Analysis (EDA):** Plotted sentiment trends, PnL distributions, and leverage patterns.  
3. **Visualizations:** Created bar charts, heatmaps, and time-series plots to illustrate trends.  
4. **Insights Extraction:** Identified key behaviors of traders in different sentiment phases.  

---

## **5. Key Insights**  
- **Leverage Trends:** Average leverage increases steadily from Extreme Fear to Extreme Greed, showing higher risk appetite in bullish markets.  
- **PnL Patterns:** Profitable trades cluster in Greed phases, while losses are more common during Fear phases.  
- **Risk Implications:** Extreme optimism correlates with higher volatility and potential for sharp reversals.  

---

## **6. How to View**  
- **Colab Notebooks:**  
  - [Notebook 1 Data Preprocessing & EDA] https://colab.research.google.com/drive/11hClkeCBC1bIKMWMSQiDX-HvpMX0XYg5?usp=sharing
  - [Notebook 2 Analysis & Insights] https://colab.research.google.com/drive/1Zyb0-OmNvxvsESXv8dwcOb6EqYjlr7Dg?usp=sharing
  - csv_files
- Open **`ds_report.pdf`** for final summarized insights.  
- View PNGs in the **`outputs/`** folder for visual analysis.  

---

## **7. Tools & Libraries Used**  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Plotly  
- **Google Colab** for coding and execution  
- **GitHub** for version control and submission  

---

## **8. Author**  
**Aastik Sonkar** B.Tech Computer Science, Gautam Buddha University  
# Market Sentiment vs Trader Behavior Analysis  
**Candidate:** Aastik Sonkar  

---

## **Overview**  
This project explores how trader behavior (profitability, leverage, volume) aligns with Bitcoin market sentiment
 (Fear vs Greed). Using historical trader data from Hyperliquid and the Fear & Greed Index, the analysis uncovers patterns 
 that can inform smarter trading strategies.  

---

## **Repository Structure**  

---

## **Key Insights**  
- Average leverage rises from Extreme Fear to Extreme Greed, showing higher risk appetite in bullish sentiment.  
- Profitable trades cluster in Greed phases; losses are more frequent during Fear phases.  
- Extreme optimism drives both higher profits and sharper volatility.  

---

## **View Project**  
ds_aastik_sonkar/
  notebook_1.ipynb # Data cleaning & preprocessing
notebook_2.ipynb # Analysis, visualizations, insights
    csv_files/ # Raw & processed datasets
    outputs/ # Charts & heatmaps
    ds_report.pdf # Final summarized report
    README.md # Project documentation

---

## **Tools Used**  
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly), Google Colab, GitHub  

---

