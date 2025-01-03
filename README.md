# Solubility Prediction Using Delaney Dataset

This project leverages the Delaney solubility dataset to build machine learning models for predicting aqueous solubility (logS) of chemical compounds. We use two regression models—Linear Regression and Random Forest—and evaluate their performance on this task.

## What is Delaney Solubility?

Aqueous solubility, represented as logS, is a fundamental property in chemistry and biochemistry. It determines how well a compound dissolves in water, influencing its behavior in biological systems and industrial applications. The Delaney dataset provides experimental solubility values alongside molecular descriptors, making it an excellent resource for building predictive models.

## Workflow

1. **Data Preparation**
   - The dataset is loaded, and the target variable (`logS`) is separated from input features.
   - The data is split into training (80%) and testing (20%) subsets.

2. **Model Training**
   - Linear Regression and Random Forest models are trained using the training data.

3. **Model Evaluation**
   - Performance is evaluated using metrics:
     - Mean Squared Error (MSE)
     - R-squared (R²)
   - Models are compared to determine which performs better on this dataset.

4. **Visualization**
   - Scatter plots and trend lines are created to visually assess model predictions.

## Dataset

The dataset, sourced from [Data Professor's repository](https://github.com/dataprofessor/data), includes:
- `logS`: Experimental solubility values (target variable).
- Molecular descriptors: Input features for prediction.

## Results

The performance of the models is summarized in a comparison table, showcasing their MSE and R² values for both training and testing data.

## Prerequisites

To run this project, ensure you have Python installed along with the following libraries:
- pandas
- scikit-learn
- matplotlib
- numpy

## How to Run

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the script to train models and visualize results.
