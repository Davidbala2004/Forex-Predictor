# Forex Market Predictor

**Predicting forex market trends in real-time using RapidAPI and deep learning (ARIMA model).**

## Features
- Real-time forex data acquisition via [RapidAPI](https://rapidapi.com/).
- Data preprocessing and visualization for trend analysis.
- Forex trend prediction using the ARIMA model.
- User-friendly CLI/Notebook interface for testing predictions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/forex-market-predictor.git
   cd forex-market-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Get your API key from [RapidAPI](https://rapidapi.com/) for forex data.

2. Add the API key to a `.env` file:
   ```plaintext
   RAPIDAPI_KEY=your_api_key
   ```

3. Run the predictor script:
   ```bash
   python forex_predictor.py
   ```

## Technologies Used
- **RapidAPI**: Real-time forex data API.
- **Python**: Programming language for implementation.
- **ARIMA Model**: Predictive modeling for time-series data.

## Results
The model demonstrates predictive trends based on historical forex data, helping traders make informed decisions.



