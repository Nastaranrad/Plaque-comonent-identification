
# Plaque Component Identification with Deep Neural Networks

## Objective
This project focuses on the automatic classification of arterial plaque components from medical imaging data. The goal is to support early diagnosis of cardiovascular disease by applying deep learning methods to detect and categorize different tissue types within plaques.

## Dataset & Preprocessing
- Input data: labeled plaque component samples (images).
- The dataset is split into training and validation sets.
- Preprocessing includes normalization to ensure stable training.

## Model Architecture
- Implemented a **Deep Neural Network (DNN)** using TensorFlow/Keras.
- The model includes multiple dense layers with **ReLU activations** and **dropout layers** to reduce overfitting.

## Training & Evaluation
- Loss function: categorical cross-entropy.
- Optimizer: Adam.
- Regularization: dropout + early stopping.
- Metrics: accuracy on both training and validation sets.

## Results
- Confusion matrix and classification report demonstrate good performance across plaque categories.
- Shows the potential of deep learning to assist clinicians in cardiovascular imaging analysis.

## Key Contributions
- Implementation, training, and evaluation of deep learning models in **Python (TensorFlow/Keras)**.
- Application of machine learning to a **real-world healthcare problem**.
- Clear, reproducible code with visualizations for model evaluation.

## How to Run
1. Open the [Colab Notebook](https://colab.research.google.com/github/Nastaranrad/Plaque-comonent-identification/blob/main/DNN_Plaque.ipynb).
2. Run all cells step by step.
3. The notebook will train the model and display results, including accuracy and confusion matrix.
