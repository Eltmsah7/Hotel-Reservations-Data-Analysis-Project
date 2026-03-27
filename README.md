# 🏨 Hotel Reservations Data Analysis & Optimization

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Data_Cleaning](https://img.shields.io/badge/Data-Cleaning-orange?style=for-the-badge)

## 📌 Project Overview
This project involves a deep-dive analysis of over **36,000 hotel reservation records**. The goal was to uncover patterns behind booking cancellations, analyze customer segments, and provide data-driven recommendations to maximize hotel occupancy and revenue.

## 🛠️ Tech Stack
* **Language:** Python 🐍
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn.
* **Environment:** Jupyter Notebook.

## ⚙️ Data Challenges & Solutions (The "Problem-Solving" Phase)
During the data preparation, several technical hurdles were addressed to ensure the integrity of the insights:

* **📅 The "Leap Year" Bug:** Found invalid dates (e.g., Feb 29th on non-leap years) which caused errors in time-series conversion. 
    * *Solution:* Implemented a custom Python function to programmatically correct these dates to Feb 28th, allowing seamless `datetime` parsing.
* **🔄 Feature Engineering:** Transformed binary columns (0/1) like `repeated_guest` and `parking_space` into categorical text (Yes/No).
    * *Result:* This significantly improved the readability of visualizations and final reports.
* **🧹 Data Consistency:** Handled inconsistent naming conventions and standardized columns for efficient SQL-like querying within Pandas.

## 📊 Key Insights & Business Impact
* **🚫 Cancellation Patterns:** The **Online Segment** generates the most revenue but suffers from a **36.5% cancellation rate**.
* **💡 The "Special Request" Effect:** A critical discovery: guests with **3 or more special requests** have a **0% cancellation rate**. Engagement equals commitment!
* **⏳ Lead Time Risk:** Cancelled bookings have an average lead time of **139 days**, nearly triple the lead time of confirmed stays (59 days).
* **💰 Revenue Peaks:** October is the most profitable month, while July faces the highest cancellation risks.

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have `pandas` and `seaborn` installed.
3. Open `Hotel_Reservations_Analysis.ipynb` and run all cells.

---
*Developed by a Data Analyst focused on turning complex datasets into business growth.*
