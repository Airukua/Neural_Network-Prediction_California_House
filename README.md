# Linear Regression on California Housing Dataset

This notebook demonstrates the implementation of a linear regression model on the California Housing dataset. The model is built and trained in Python using PyTorch, with Google Colab as the runtime environment. The notebook includes data preprocessing, model training, and evaluation steps to predict housing prices.

## Requirements

- Python 3.x
- Google Colab
- PyTorch
- Additional Python libraries: `numpy`, `pandas`, `sklearn`, `tqdm`

## Features

1. **Data Loading**: The California Housing dataset is loaded and split into training and testing sets.
2. **Data Normalization**: Data normalization is applied to ensure that input values are scaled to a specific range.
3. **Model Architecture**: A simple linear regression model is defined using PyTorch.
4. **Training**: The model is trained on the training set, minimizing the loss function (Mean Squared Error).
5. **Validation**: After each epoch, validation is performed to monitor the model's performance.
6. **Denormalization**: Predictions and targets are denormalized for error calculation in the original price scale.
7. **Error Calculation**: Mean Absolute Error (MAE) is calculated on the denormalized predictions to evaluate model accuracy.

## Usage

1. Run all cells in the notebook to load data, train the model, and evaluate its performance.
2. Monitor the loss values and denormalized errors printed at the end of each epoch.

## Results

- The notebook provides training and validation loss values per epoch.
- Final validation loss and Mean Absolute Error (MAE) are displayed after training.

## Acknowledgments

This notebook is based on the California Housing dataset and leverages PyTorch for machine learning model development and training.
