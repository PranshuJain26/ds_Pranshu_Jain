# Data Science Assignment: Trader Sentiment Analysis

This repository contains the submission for the Web3 Trading Team data science assignment.

**Candidate:** `ds_Pranshu_Jain`

---

### Google Colab Notebook Link

As required by the instructions, here is the link to the live Google Colab notebook used for this analysis.

**[https://colab.research.google.com/drive/1CjiIYEM2qhRuHLML0g3-r41vtjcaD6C5?usp=sharing]**


*(Access is set to "Anyone with the link can view".)*

---

### Project Structure

This repository follows the structure specified in the assignment instructions.

**Note on `csv_files`:** The `historical_data.csv` file (80MB+) is **intentionally not included** in the `csv_files` folder because it exceeds GitHub's 25MB file size limit.

As a professional workaround, the `Notebook_1.ipynb` script is coded to download the large dataset *directly* from the Google Drive link provided in the assignment. The smaller `fear_greed_index.csv` file *is* included in the `csv_files` folder to demonstrate compliance with the required structure.

ds_Pranshu_Jain/ ├── Notebook_1.ipynb ├── csv_files/ │ └── fear_greed_index.csv ├── outputs/ │ ├── pnl_by_sentiment.png │ ├── volume_by_sentiment.png │ └── side_by_sentiment.png ├── ds_report.pdf └── README.md

---

### Key Finding: Data Incompatibility

A critical part of this analysis was data validation. The provided datasets were found to be incompatible, which prevents the core analysis from being completed.

1.  **Date Mismatch:** The trader data (`historical_data.csv`) is from **2024-2025**, while the sentiment data (`fear_greed_index.csv`) is from **2018**. There are no overlapping dates, making a merge impossible.

2.  **Missing Data:** The 'leverage' column, required for risk analysis, is missing from the trader dataset.

Please see the `ds_report.pdf` for a full summary of these findings.
