# Forex Market Predictor

## Overview

This project is a **Forex Market Predictor** designed to predict currency pair movements using machine learning techniques. It leverages historical Forex data, technical indicators, and advanced modeling to provide predictions for better decision-making in trading.

---

## Features

- **Data Preprocessing**: Cleans and prepares raw Forex data.
- **Feature Engineering**: Computes technical indicators (e.g., RSI, MACD, Bollinger Bands).
- **Model Training**: Uses machine learning models such as Random Forest, XGBoost, or LSTM.
- **Evaluation**: Evaluates model accuracy using metrics like RMSE, MAE, and classification reports.
- **Visualization**: Displays trends, predictions, and trading signals.

---

## Project Structure

```plaintext
Forex-Market-Predictor/
├── data/
│   ├── raw/                # Raw Forex data
│   ├── processed/          # Processed data
├── notebooks/              # Jupyter notebooks for experiments
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── evaluation.py
│   ├── visualization.py
├── models/                 # Trained models
├── requirements.txt        # Python dependencies
├── README.md               # Project README file
└── config.yaml             # Configuration file
```

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook (optional for experimentation)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/forex-market-predictor.git
   cd forex-market-predictor
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download historical Forex data and place it in the `data/raw/` folder.

---

## Usage

1. **Data Preprocessing**:
   ```bash
   python src/data_preprocessing.py
   ```

2. **Feature Engineering**:
   ```bash
   python src/feature_engineering.py
   ```

3. **Model Training**:
   ```bash
   python src/model_training.py
   ```

4. **Evaluation**:
   ```bash
   python src/evaluation.py
   ```

5. **Visualization**:
   ```bash
   python src/visualization.py
   ```

---

## Configuration

Modify the `config.yaml` file to:

- Specify currency pairs (e.g., EUR/USD, GBP/USD)
- Set timeframes (e.g., daily, hourly)
- Choose machine learning models
- Define evaluation metrics

---

## Technical Indicators Used

- **Relative Strength Index (RSI)**
- **Moving Average Convergence Divergence (MACD)**
- **Bollinger Bands**
- **Exponential Moving Averages (EMA)**
- **Stochastic Oscillator**

---

## Machine Learning Models

- **Random Forest**
- **Gradient Boosting (XGBoost)**
- **Long Short-Term Memory (LSTM)**
- **Support Vector Machines (SVM)**

---

## Results

- Example: Achieved an accuracy of **75%** on EUR/USD predictions over a 6-month period.
- Visualization of predicted vs actual prices included.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the project.
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a pull request.

---



