# Flow-of-the-Nile-Time-Series-Analysis

This repository contains a comprehensive time series analysis of the annual flow of the Nile River at Aswan, Egypt. The dataset spans 100 years (1871–1970), and we analyze its statistical properties, apply ARIMA modeling, and conduct spectral analysis for periodicity detection. We also explore deep learning-based forecasting using LSTM for comparison.

---

## 📁 Files

- `Nile.csv`: Annual Nile River flow data.
- `MACT4232_Project.pdf`: Full report with code and outputs.
- `README.Rmd`: This documentation file.
- `project.R`: R code 

---

## 📌 Dataset Description

- **Source**: [Kaggle: Flow of the River Nile](https://www.kaggle.com/datasets/lsind18/flow-of-the-river-nile)
- **Measurements**: Annual flow in \(10^8\) cubic meters
- **Time Span**: 1871–1970
- **Observations**: 100 annual values

---

## 🧪 Libraries Used

```r
library(tseries)
library(urca)
library(forecast)
library(readr)
