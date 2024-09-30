# Bike Share Count Prediction Project

This project is based on the **Bike Sharing Demand** competition on Kaggle. The goal is to predict bike rental counts using various features such as time, weather, and other factors.

**Kaggle Competition Overview**: [Bike Sharing Demand](https://www.kaggle.com/c/bike-sharing-demand/overview)

## Project Structure

- `your_notebook.ipynb`: The Jupyter notebook containing the entire data exploration, feature engineering, model training, and evaluation.
- `data/submissions.csv`: The output file containing predictions for the test data, formatted for submission.
- `data/test.csv`: The test data used for predictions.
- `README.md`: This file, providing an overview of the project and instructions.

## Key Features

- **Feature Engineering**: Time-based features such as hour of the day, day of the week, and cyclical encoding are used to capture the cyclical nature of bike rentals.
- **Random Forest Model**: A Random Forest Regressor is trained on the dataset to predict bike rental counts.
- **Cyclical Encoding**: Cyclical encoding is applied to time features like `hour` and `day_of_week` to better capture their periodic nature.
- **Hyperparameter Tuning**: Hyperparameters are fine-tuned to improve the model's performance.
- **RMSLE Evaluation**: Root Mean Squared Logarithmic Error (RMSLE) is used as the evaluation metric for model performance.

## Installation

### Requirements

To run the notebook and reproduce the results, you need to have the following installed:

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Required Python libraries (listed in `requirements.txt` or install via `pip` below)

### Install Dependencies

You can install the required libraries using `pip`:

```bash
pip install -r requirements.txt
