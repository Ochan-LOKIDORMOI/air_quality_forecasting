# **Beijing Air Quality Forecasting**

## **Project Overview**

This project is part of the **Machine Learning Techniques I** course and focuses on forecasting PM2.5 air pollution levels in Beijing using Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) models.
 Accurate predictions of PM2.5 concentrations help policymakers and communities take timely action to mitigate air pollution effects.


## **Objectives**

- Preprocess sequential air quality and meteorological data.
- Design and train RNN/LSTM models to forecast PM2.5 levels.
- Fine-tune models by experimenting with different architectures and hyperparameters.
- Evaluate model performance and submit predictions.


# **Best Selected Model**

After conducting multiple experiments with different architectures, the selected model
demonstrated superior performance in terms of minimizing RMSE while ensuring generalization.

## **LSTM layers:**

- First LSTM layer with 128 units, ReLU activation, and L2 regularization.

- Dropout layer (20%) for regularization.

- Second LSTM layer with 64 units, ReLU activation, and L2 regularization.

- Dropout layer (20%) for regularization.

## **Dense layers:**

- Fully connected layer with 32 units, ReLU activation, and L2 regularization.

- Output layer with 1 unit for PM2.5 prediction.

- **Optimizer**: Adam with a learning rate of 0.01.

- **Loss function**: Mean Squared Error (MSE).

- **Evaluation metric**: Root Mean Squared Error (RMSE).
- **Performance metric**: 70.44

## **Training:**

- 20 epochs with a batch size of 32.

- Model was fine-tuned to improve performance.

# **Repository Structure**
├── data/                  # Dataset files
├── notebook/              # Jupyter Notebooks for data exploration
├── models_output/         # Evaluation metrics and model outputs
├── README.md              # Project documentation


# **Setup**
To run the code, follow this instructions. 

## Here's
- Clone this Reo in your machine and run the Jupyter Notebook 
- This will train the LSTM

## **Contributors**

- Ochan LOKIDORMOI (https://github.com/Ochan-LOKIDORMOI/)

- Open to collaboration! Feel free to fork and contribute.