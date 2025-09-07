# Bayesian Financial Forecasting

This repository contains the code and installation for the MSc dissertation:

**"Uncertainty Quantification in Bayesian Deep Learning for Financial Time Series Forecasting: Calibration, Interpretability, and Comparison of Methods"**  
by Miranda-Belle Onyekwere, Imperial College London, 2025.

---

## **Overview**

This project investigates Bayesian deep learning approaches for financial time series forecasting, including:

- **Baseline LSTM**
- **Monte Carlo Dropout**
- **Deep Ensembles**
- **Bayes by Backprop**

It focuses on both **predictive accuracy** and **uncertainty quantification**, with feature-level interpretability via Gradient-based Uncertainty Attribution (GUA).

---

## **Repository Structure**

- bayesian-financial-forecasting.ipynb -> Jupyter notebook
- requirements.txt -> Python dependencies
- LICENSE -> CC-BY-4.0 License
- README.md -> Project overview and instructions

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/mirandabelle/bayesian-financial-forecasting.git
cd bayesian-financial-forecasting
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

4. Launch the Jupyter notebook:

```bash
jupyter notebook bayesian-financial-forecasting.ipynb
```

---

## **Data Sources**

- Stock prices and trading volume: Yahoo Finance
- Macroeconomic indicators: FRED

---

## **License**

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

**Attribution is required.**

Examiners and future researchers are encouraged to use, extend, and build upon this work.

---

## **Contact**

For questions or issues regarding this repository, please contact Miranda-Belle Onyekwere:

Email: miranda-belle.onyekwere23@imperial.ac.uk
