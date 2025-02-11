# Time Series Forecasting with XGBoost

This repository contains a comprehensive pipeline for time series forecasting hourly energy usage using the **XGBoost** machine learning model. The workflow covers data preprocessing, feature engineering, model training, and evaluation, making it suitable for predictive analytics.

## Contents

- **Data Splitting**: Train/Test split for model validation.
- **Feature Engineering**: Creation and transformation of features for time series prediction.
- **Visualizations**: Analysis of feature and target relationships.
- **XGBoost Modeling**: Building and training an XGBoost model for forecasting.
- **Feature Importance**: Insights into the most impactful features.
- **Forecasting**: Predictions on test data.
- **Evaluation**: Error metrics to assess model performance.
- **Prediction Analysis**: Examination of the best and worst predicted days.

## Repository Structure

- `archive/PJME_hourly.csv`: Folder for raw and processed datasets.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/time-series-forecasting.git
   cd time-series-forecasting
   ```

2. Install dependencies using `pip` or `conda`:
   ```bash
   pip install -r requirements.txt
   ```

   If using a virtual environment, activate it first:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows, use `venv\Scripts\activate`
   ```

3. Install Jupyter Notebook (if not already installed):
   ```bash
   pip install notebook
   ```

## Usage

1. Open the notebook:
   ```bash
   jupyter notebook time series.ipynb https://github.com/Emmanuel-Chukwuma/time_series_prediction_for_energy_usage/blob/main/time%20series.ipynb
   ```

2. Follow the workflow outlined in the notebook, which includes:
   - Splitting data into training and testing sets.
   - Engineering features for time series data.
   - Training the XGBoost model.
   - Evaluating and visualizing predictions.

## Evaluation Metrics

The model is evaluated using metrics such as:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
