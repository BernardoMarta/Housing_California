# California Housing Price Prediction with Neural Networks

## About the Project

This project implements a neural network model to predict housing prices in California using the California Housing dataset. The model is built using Keras and scikit-learn, demonstrating the application of deep learning techniques to real estate price prediction.

## How It Works

1. **Data Loading**: The California Housing dataset is loaded using scikit-learn's `fetch_california_housing` function.
2. **Data Preprocessing**: 
   - The dataset is split into training and testing sets.
   - Features are standardized using StandardScaler.
3. **Model Building**: A sequential neural network is constructed using Keras with two hidden layers.
4. **Model Training**: The model is trained on the preprocessed data for 50 epochs.
5. **Evaluation**: The model's performance is evaluated using Mean Absolute Error (MAE).
6. **Prediction**: Sample predictions are made and compared to actual values.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries: numpy, keras, scikit-learn

Install the necessary libraries with:

pip install numpy keras scikit-learn


### Usage

Open and run the Jupyter Notebook in Google Colab:

1. Click on the "Open in Colab" button at the top of the notebook.
2. Run all cells in the notebook.

The notebook will:
1. Load and preprocess the California Housing dataset.
2. Build and train a neural network model.
3. Evaluate the model's performance.
4. Make sample predictions.

## Features

- Uses the California Housing dataset, containing 20,640 samples and 8 features.
- Implements a neural network using Keras for regression.
- Demonstrates data preprocessing techniques like feature scaling.
- Provides model evaluation using Mean Absolute Error.
- Includes sample predictions to showcase model performance.

## Contributing

Feel free to fork this repository and submit pull requests to improve the model or extend its functionality.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to scikit-learn for providing the California Housing dataset.
- Thanks to Keras and TensorFlow for the deep learning framework.
