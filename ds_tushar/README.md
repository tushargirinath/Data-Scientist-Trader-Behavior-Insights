# 📊 Trader Behavior vs Market Sentiment (Fear & Greed)

This project explores the relationship between **crypto trader performance** and the **Bitcoin Fear & Greed Index**.  
The analysis combines **trader-level execution data** with **market sentiment** to uncover behavioral patterns that can drive smarter Web3 trading strategies.  

By aligning sentiment-driven indicators with actual trading outcomes, the project highlights how **fear and greed cycles** directly influence:  
- Trade frequency and timing  
- Leverage and position sizing  
- Long vs short performance  
- Profitability under different sentiment regimes  

Unlike traditional backtesting focused only on **historical price movements**, this project incorporates **psychological market factors** to better understand trader decision-making.  
The findings can serve as a foundation for:  
- Building **adaptive trading models**  
- Improving **risk management frameworks**  
- Developing **next-generation Web3 trading intelligence systems**  


---

## 📂 Project Structure
    ds_tushar/
    ├── notebook_1.ipynb  # Main notebook with full analysis
    ├── csv_files/  # Raw & processed data
    ├── outputs/  # Visualizations, reports
    ├── ds_report.pdf # Exported final report     
    └── README.md

---

## 🚀 Workflow
1. **Data Preprocessing** – standardization, cleaning, merging trader & sentiment datasets.  
2. **Exploratory Data Analysis (EDA)** – trade volume, profitability, leverage, sentiment correlation.  
3. **Statistical Testing** – t-test, Mann–Whitney, ANOVA for hypothesis validation.  
4. **Risk Behavior Analysis** – long vs short win rates, trade size, volume concentration.  
5. **Symbol-Level Insights** – asset-specific trading behavior patterns.  
6. **Auto-Generated Reports** – Markdown → HTML → PDF summary.  

---

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, NumPy, SciPy)  
- **Visualization:** Matplotlib, Seaborn, Plotly  
- **Statistical Analysis:** SciPy, StatsModels  
- **Reporting:** Pandas Profiling, nbconvert, LaTeX/PDF export  

---

## 📊 Key Insights
- **Sentiment drives behavior** more than pure profitability.  
- **Greed →** higher leverage, more trades, stronger long performance.  
- **Fear →** lower leverage, fewer trades, shorts outperform.  
- Strategy should dynamically adapt to **market sentiment cycles**.  


## ⚡ How to Run
Clone the repo and install dependencies:
```bash
git clone https://github.com/your-username/junior-data-scientist-trader-insights.git
cd junior-data-scientist-trader-insights
pip install -r requirements.txt
Google colab / jupyter notebook notebook_1.ipynb
🔮 Future Work

Incorporate real-time sentiment APIs for live analysis.

Extend analysis to multi-chain crypto assets.

Build a predictive model for trader behavior using sentiment scores.

🧑‍💻 Author

Tushar DC
📧 tushargirinath26@gmail.com
🌐 GitHub | LinkedIn - tushar_girinath
