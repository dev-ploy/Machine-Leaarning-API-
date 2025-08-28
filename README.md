# House Price Prediction API

A FastAPI-powered REST API for predicting house prices using a trained machine learning model.

## Features

- Predict price for a single house (`/predict`)
- Predict prices for multiple houses (`/predict_batch`)
- Model training and evaluation in Jupyter notebook
- API testing notebook

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/House-Prediction-API.git
cd House-Prediction-API
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the API

```bash
uvicorn src.main:app --reload
```

### 4. Test the API

- Use `testing/test.ipynb` to send requests and view predictions.

## Repository Structure

```
House-Prediction-API/
│
├── notebooks/
│   ├── model.ipynb         # Jupyter notebook for model development
│   └── model.pkl           # Trained model file
│
├── src/
│   ├── main.py             # FastAPI application
│   └── __pycache__/        # Python cache files (can be ignored)
│
├── testing/
│   └── test.ipynb          # Notebook for API testing
│
├── README.md               # Project overview and instructions
├── requirements.txt        # Python dependencies
└── .gitignore              # Files/folders to ignore in git
```

## File Overview

- `notebooks/model.ipynb`: Model development and training.
- `notebooks/model.pkl`: Saved model for inference.
- `src/main.py`: FastAPI app serving prediction endpoints.
- `testing/test.ipynb`: Example requests to the API.
- `requirements.txt`: List of required Python packages.


## License

MIT
