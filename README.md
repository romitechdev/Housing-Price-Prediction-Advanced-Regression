# Housing Price Prediction – Advanced Regression

Advanced regression models for housing price prediction, with feature engineering and model comparison. Ships with a small web app and pre-trained artifacts.

## Features

- Multiple regression models for price estimation
- Feature engineering and model comparison
- Pre-trained model (`final_model.pkl`) and fitted scaler (`scaler.pkl`)
- Lightweight web app (`app.py`) for running predictions

## Tech Stack

- Python
- scikit-learn
- pandas
- Flask or Streamlit (serving `app.py`)

## Project Structure

```
.
├── app.py
├── final_model.pkl
├── scaler.pkl
└── requirements.txt
```

## Getting Started

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `python app.py`
