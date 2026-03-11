# Netflix Stock Price Prediction 📈

An end-to-end machine learning project that predicts **Netflix (NFLX) stock prices** using **LSTM neural networks** and provides an interactive **Streamlit dashboard** for forecasting and visualization.

The project demonstrates a full ML workflow including data preprocessing, model training, evaluation, and deployment through a simple web interface.

---

## Features

• LSTM-based deep learning model for time series forecasting
• Interactive Streamlit dashboard for visualization
• Multi-step forecasting (up to 30 days ahead)
• Historical stock data integration using Yahoo Finance
• Visual comparison of predicted vs actual prices

---

## Tech Stack

Python
TensorFlow / Keras
Pandas & NumPy
Streamlit
Plotly
Yahoo Finance API

---

## Project Structure

```
netflix-stock-prediction-system
│
├── data
│   ├── raw                # Original dataset
│   └── processed          # Cleaned datasets
│
├── notebooks
│   ├── data_preparation.ipynb
│   └── model_training.ipynb
│
├── models                 # Saved trained models
│
├── app
│   ├── app.py             # Streamlit application
│   └── utils.py           # Helper functions
│
└── requirements.txt
```

---

## Installation

Clone the repository

```
git clone https://github.com/yourusername/netflix-stock-prediction-system.git
cd netflix-stock-prediction-system
```

Create a virtual environment

```
python -m venv venv
```

Activate the environment

Windows

```
venv\Scripts\activate
```

Linux / Mac

```
source venv/bin/activate
```

Install dependencies

```
pip install -r requirements.txt
```

---

## Running the Application

Start the Streamlit app

```
streamlit run app/app.py
```

The dashboard will open at:

```
http://localhost:8501
```

---

## Model Details

Architecture
2-layer LSTM network with dropout regularization

Training Data
Netflix stock data from 2010–2023

Evaluation Metric
Mean Squared Error (MSE)

---

## Future Improvements

• Experiment with Transformer-based time series models
• Incorporate additional financial indicators
• Improve forecasting horizon and uncertainty estimation
• Deploy the application on cloud infrastructure

---

## License

MIT

## Dashboard Preview

![Dashboard](assets/dashboard.png)
