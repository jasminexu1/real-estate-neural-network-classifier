# Real Estate Neural Network Classifier

This project implements and compares several neural network models using PyTorch to classify real estate price categories based on categorical data. It was developed as part of a university machine learning assignment.

## Features

- Fully connected neural networks with 1, 2, 3, and 4 hidden layers
- Experiments comparing:
  - ReLU vs. Sigmoid activation functions
  - Dropout regularization (0.5 probability) vs. none
- Visualized training and testing accuracy across 150 epochs
- Categorical data preprocessing and one-hot encoding
- Built and tested in a Jupyter Notebook

## Technologies Used

- Python 3.x
- PyTorch
- NumPy
- Pandas
- Matplotlib

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/jasminexu1/real-estate-neural-network-classifier.git
   cd real-estate-neural-network-classifier
   ```
2. Open real-estate-nn.ipynb in Jupyter Notebook or VSCode

3. Ensure categorical_real_estate.csv is present in the same directory

4. Run all cells to train models and view plots
