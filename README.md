# Options Pricing using Random Forest and LSTM

This Jupyter Notebook demonstrates two approaches for pricing options: 
- A **Random Forest Regressor**
- A **Long Short-Term Memory (LSTM)** neural network.

The notebook trains both models on a dataset of options and compares their performance in predicting option prices.

## Features

1. **Data Preprocessing**: 
   - Loading and preprocessing options data for model training and evaluation.
  
2. **Random Forest Regressor**:
   - A machine learning approach to predict option prices based on historical data.
   
3. **LSTM Model**:
   - A deep learning approach that captures the temporal dependencies in the data.

4. **Performance Evaluation**:
   - The models are evaluated based on metrics such as **Mean Squared Error (MSE)** and **accuracy**.

## Requirements

To run this notebook, you need the following dependencies:

- Python 3.x
- TensorFlow
- scikit-learn
- Pandas
- NumPy
- Matplotlib

### Install dependencies:

```bash
pip install tensorflow scikit-learn pandas numpy matplotlib
