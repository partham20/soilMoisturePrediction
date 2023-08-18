# Soil Moisture Prediction using Neural Networks

## Overview

Soil moisture is a crucial factor influencing agricultural productivity, water management, and climate modeling. Accurate prediction and understanding of soil moisture can lead to more efficient irrigation practices and sustainable land management. This project aims to develop a Sequential Neural Network model to predict the volumetric soil moisture content based on given features, using TensorFlow and Keras.

## Features

1. **Data Preprocessing:** Includes normalization, data splitting, and shuffling to prepare the data for training.
2. **Neural Network Model:** A three-layer Sequential Neural Network implemented using Keras, with Leaky ReLU activation functions.
3. **Training and Evaluation:** The model is trained on a subset of the data and evaluated using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
4. **Visualization:** Provides plots for training metrics and comparison between original and predicted soil moisture.
5. **Correlation Analysis:** Calculates the Pearson correlation coefficient to understand the relationship between the original and predicted values.

## Dependencies

- TensorFlow
- Keras
- SciPy
- NumPy
- pandas
- Matplotlib
- scikit-learn

## Usage

Clone the repository, ensure that the required dependencies are installed, and run the Jupyter notebook or Python script to train and evaluate the model.

## Data

The dataset consists of various features related to soil properties and the target variable 'volumetric soil moisture content.' The dataset must be placed in the specified path for the code to run.

## Ethical Considerations

It is vital to handle the data and modeling responsibly, keeping in mind local environmental norms and potential ecological impacts. This model aims to contribute positively to agriculture and environmental science.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#) or submit pull requests.

## License

This project is [MIT licensed](#).
