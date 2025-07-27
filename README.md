# 📊 Trader Behavior vs Market Sentiment Analysis

**Submitted by:** Prathyusha  
**Role:** Data Science Intern Applicant  
**Organization:** Web3 Trading Team  
**Assignment Objective:** Analyze trader behavior in relation to market sentiment (Fear vs. Greed)

---

## 🧠 Project Overview

This project explores how trader behavior (volume, profit, trade size) correlates with market sentiment, using:

- 📈 Historical trader activity data (Hyperliquid)
- 📊 Fear & Greed index (Bitcoin sentiment data)

The goal is to uncover patterns and trends that may inform smarter trading strategies.

---

## 📁 Datasets

1. **Historical Trader Data**  
   - Columns: `Timestamp`, `Closed PnL`, `Size USD`, `Account`, etc.

2. **Fear & Greed Index (Bitcoin Market Sentiment)**  
   - Columns: `timestamp`, `classification` (Fear/Greed), `value`

---

## 📊 Key Steps

### 🔹 Data Cleaning
- Converted timestamps  
- Removed missing values  
- Reduced to relevant columns for memory efficiency  

### 🔹 Efficient Merging
- Used `merge_asof()` for scalable time-aligned merging of large datasets  

### 🔹 EDA & Visualization
- Trade distribution by sentiment  
- Profitability patterns (`Closed PnL`)  
- Trade size patterns (USD)  
- Log-scaled charts to handle outliers  

### 🔹 Summary Table
- Aggregated metrics: average PnL, total PnL, average size, unique traders  

---

## 📌 Insights

- **Greed phases** show higher trading volume, larger trades, and better profitability.  
- **Fear phases** reflect lower activity and more conservative trade sizes.  
- Sentiment is a significant driver of trader behavior, which can be leveraged in predictive trading models.

---

## 🛠️ How to Run

1. Open `notebook_1.ipynb` in [Google Colab](https://colab.research.google.com/)  
2. Upload the two provided datasets  
3. Run all cells step-by-step  
4. Outputs and CSVs will be saved automatically to `/outputs/` and `/csv_files/`

---

## 📎 Submission Notes

- All code shared via Google Colab (viewable link)  
- Folder structure strictly follows the assignment format  
- Report attached as `ds_report.pdf`  
- GitHub Repo Link: [Insert your repository URL here]

---

## 📬 Contact

Feel free to reach out for any clarifications or improvements.
