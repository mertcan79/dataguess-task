# Machine Learning Engineer Assignment

## Overview

- This project contains a stock price prediction model using an LSTM model. The model loads historical stock data, creates and extracts features, and predicts future prices. 
- A jupyter notebook in the notebooks folder contains EDA and modeling steps. 
- In src folder, main.py can be executed to run the model and output results based on the config.yaml file. Model parameters and basic things such as stock selection and time period can be set there.
- The logs, visuals and the model file can be found in their folders. 
- The presentation file shows the steps taken and the modeling approach.

## Installation

Clone the repository
```bash
git clone https://github.com/mertcan79/stock_predictor.git
cd stock_predictor
```
Create and activate a virtual environment
```bash
python -m venv env
source env/bin/activate
```

Install dependencies
```bash
pip install -r requirements.txt
```

## Configuration 

Modify config.yaml to adjust parameters for data loading, feature engineering, and model training.

## To run

```bash
python src/main.py
```

Or use Docker
```bash
docker build -t stock_predictor .

docker run --rm dataguess-task
```
