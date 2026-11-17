# Diabetes_Progression_ANN-_
# Diabetes Progression Prediction using Artificial Neural Network (ANN)

## Project Overview
This project focuses on predicting diabetes progression using an Artificial Neural Network (ANN). The model uses the Diabetes dataset available in the Scikit-learn library to understand the relationship between different health-related features and diabetes progression.

## Objective
To develop and evaluate an ANN model that predicts diabetes progression based on available independent variables.

## Dataset
- **Source:** Scikit-learn built-in Diabetes dataset
- **Total Records:** 442
- **Number of Features:** 10
- **Target Variable:** Progression

## Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow

1. Loading the Diabetes dataset.
2. Checking missing and duplicate values.
3. Data preprocessing and feature normalization.
4. Exploratory Data Analysis (EDA).
5. Data visualization using histograms, scatter plots, and correlation heatmaps.
6. Building an Artificial Neural Network.
7. Training the model using the Adam optimizer.
8. Evaluating the model using Mean Squared Error (MSE) and R² Score.
9. Experimenting with different ANN architectures to improve performance.
10. Comparing actual and predicted values.

## ANN Model Architecture

The original ANN model contains:
- Input layer: 10 features
- Hidden layer 1: 64 neurons with ReLU activation
- Hidden layer 2: 32 neurons with ReLU activation
- Output layer: 1 neuron with Linear activation

**Optimizer:** Adam  
**Loss Function:** Mean Squared Error  
**Epochs:** 100

## Model Performance

The following results were obtained from the test dataset:

| Model | MSE | R² Score |
|---|---:|---:|
| Original ANN | 2824.00 | 0.4670 |
| Improved ANN | 2895.51 | 0.4535 |
| Optimized ANN | 2992.67 | 0.4351 |

The original ANN model achieved the best performance among the three tested architectures.

## Conclusion

The project successfully demonstrates the application of Artificial Neural Networks for predicting diabetes progression. Different ANN architectures were tested and evaluated. The original ANN model achieved the best results, with an MSE of 2824.00 and an R² score of 0.4670.

This project provided practical experience in data preprocessing, exploratory data analysis, neural network development, model training, and performance evaluation.

## Project File

`Diabetes_Progression_ANN.ipynb`

## Note
This project is developed for educational purposes and is not intended for clinical diagnosis or medical decision-making.
