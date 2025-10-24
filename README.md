# Data Science Report: Market Sentiment & PnL Analysis
## Github Link: https://github.com/Nasar-creator/ds_NasarBasha.git 
## 📘 Overview
This project analyzes trading performance based on historical data and the Fear & Greed Index.  
The goal is to explore whether market sentiment affects trading outcomes (PnL).

## 📂 Files
- **historical_data.csv** — Trading history dataset (executions, PnL, fees, etc.)  
- **fear_greed_index.csv** — Daily sentiment data (Fear, Greed, etc.)  
- **ds_report.docx** — Full analysis report with visuals and insights  
- **README.md** — Project documentation  

## ⚙️ Setup Instructions
1. Open **Google Colab**.
2. Mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
### Adjust file paths if needed (example):
histData = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/ds_NasarBasha/csv_files/historical_data.csv')
FGData = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/ds_NasarBasha/csv_files/fear_greed_index.csv')
Run all cells in order for complete analysis.
## 📈 Key Steps in Analysis

Data cleaning and preprocessing

Timestamp conversion and daily aggregation

Merging trader and sentiment datasets

Profitability and sentiment correlation

Outlier clipping (99th percentile)

Visualization (Boxplots, histograms, correlation heatmaps)

## 🧾 Author

Name: Nasar Basha
Role: Data Science Applicant – Web3 Trading Team
Tools Used: Python, Pandas, NumPy, Seaborn, Matplotlib, Google Colab
