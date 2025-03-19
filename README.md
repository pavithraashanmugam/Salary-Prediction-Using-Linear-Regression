# Linear Regression Model for Salary Prediction

This repository implements a **Linear Regression** model to predict **Salary** based on **Years of Experience** using custom Python code. The model is trained using **Gradient Descent** for optimization and the loss function is minimized to achieve the best model parameters (weight and bias). The dataset is split into training and test sets to evaluate the model's performance.

## Overview

- **Linear Regression Formula**: Y = wX + b  
  - **Y** -> Dependent variable (Salary)
  - **X** -> Independent variable (Years of Experience)
  - **w** -> Weight (Model parameter)
  - **b** -> Bias (Model parameter)

- **Gradient Descent**: Optimization algorithm to minimize the loss function, adjusting the weight (`w`) and bias (`b`) iteratively. 

- **Hyper-parameters**: Learning Rate and Number of Iterations control the training process.

## Features

- Custom **Linear Regression** class with gradient descent optimization.
- **Prediction of Salary** based on Years of Experience.
- Visualization of **Predicted vs Actual Salary** using **matplotlib**.
- Data processing using **pandas** for loading and preparing the dataset.
- Model training and evaluation using **train-test split**.

## Requirements

- **Python 3.x**
- **numpy** (for mathematical operations)
- **pandas** (for data handling)
- **matplotlib** (for visualization)
- **scikit-learn** (for train-test split)

## How to Use

1. Clone the repository.
2. Install the required libraries:
   ```
   pip install numpy pandas matplotlib scikit-learn
   ```
3. Prepare the **salary_data.csv** dataset with two columns: `YearsExperience` and `Salary`.
4. Run the Python script to train the model and visualize predictions.

## Training Process

1. Set **Learning Rate** and **Number of Iterations**.
2. Initialize the **Weight** and **Bias**.
3. Perform **Gradient Descent** to minimize the loss function and update the parameters.
4. Evaluate the model on the **test data** and visualize the results.

## Results

- The model learns the relationship between Years of Experience and Salary.
- Predicted Salary values can be compared with actual values for evaluation.
- **Visualization** of predicted vs. actual salary values shows how the model has fit the data.
- The **loss function** has been minimized through the iterative process of gradient descent, indicating that the model has reached the **global minimum**. The line in the plot represents the best-fit line, where the error between predicted and actual values is as small as possible.

Here’s the plot comparing the **Predicted vs Actual Salary** values:
![image](https://github.com/user-attachments/assets/ad0c8a0f-90d7-42f1-945a-0020262a1d8f)

