# Wine Quality Prediction

## Overview
This project predicts the quality of red wine based on physicochemical properties using data science and machine learning techniques.

## Dataset
The dataset (`winequality-red.csv`) contains 1599 observations of red wine quality metrics with 11 features, including various physicochemical tests and a quality score ranging from 0 to 10. You can download the dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv).

## Project Structure
- **Data Loading and Initial Exploration**: Load the dataset and perform an initial exploration.
- **Exploratory Data Analysis (EDA)**: Visualize data distributions and correlations.
- **Model Building and Evaluation**: Build regression models (Linear Regression, Decision Tree Regression, and Random Forest Regression) to predict wine quality. Evaluate model performance using Mean Squared Error (MSE) and R-squared (R2) score metrics.

## Requirements
Ensure you have the following Python libraries installed:

```
pandas==1.3.5
numpy==1.21.5
matplotlib==3.5.1
seaborn==0.11.2
scikit-learn==1.0.2
```

Install the required libraries using `pip install -r requirements.txt`.

## Usage
1. Clone the repository:
```
git clone <repository-url>
cd <repository-name>
```
2. Download the dataset (`winequality-red.csv`) and place it in the project directory.
3. Run the Jupyter Notebook (`Wine_Quality_Prediction.ipynb`) to execute the project steps and view results.

## Conclusion
This project demonstrates the application of Python for data preprocessing, exploratory data analysis, and machine learning model building in predicting wine quality. Feel free to explore and modify the code to enhance your understanding and skills in data science.