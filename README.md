# 🏨 Hotel Booking Analysis: Reducing Cancellations & Growing Revenue

> End-to-end data analysis case study on 119,390 real hotel bookings (City Hotel & Resort Hotel, 2015–2017).

![Python](https://img.shields.io/badge/Python-3.10+-blue) ![Status](https://img.shields.io/badge/status-in%20progress-orange)

## 1. Business Problem
_To be completed after analysis._ Hotels lose revenue when booked rooms are cancelled. This project finds **who cancels, when, and why**, and recommends how to cut cancellations and lift revenue.

## 2. Dataset
| Item | Detail |
|---|---|
| Source | Hotel Booking Demand dataset (Antonio, Almeida & Nunes, 2019) |
| Rows / Columns | 119,390 / 32 |
| Hotels | City Hotel, Resort Hotel |
| Period | July 2015 – August 2017 |

## 3. Project Structure
```
hotel-booking-analysis/
├── data/
│   ├── raw/             # original, untouched CSV
│   └── processed/       # cleaned dataset (output of src/01_clean_data.py)
├── notebooks/           # main analysis notebook
├── src/                 # reusable scripts
├── visuals/             # all charts exported as PNG
├── reports/             # final summary / insights
├── requirements.txt
└── README.md
```

## 4. How to Run
```bash
pip install -r requirements.txt
cd src && python 01_clean_data.py
jupyter notebook notebooks/
```

## 5. Data Cleaning Summary
_Filled in after Step 1 results._

## 6. Key Insights
_To be completed._

## 7. Hypothesis Tests
_To be completed._

## 8. Recommendations
_To be completed._

## 9. Tech Stack
Python · pandas · NumPy · Matplotlib · Seaborn · SciPy · statsmodels
