# Profit Prediction with Machine Learning

This repository contains a machine learning project for predicting profits of startups based on various features like R&D spend, administration costs, and marketing spend.

## Dataset
The dataset used for this project is provided in the file `Startups.csv`. It contains information about 50 startups, including their R&D spend, administration costs, marketing spend, and profit.

## Model Training and Evaluation
We trained several machine learning models to predict profits based on the given features. The models used are:

- Linear Regression
- Random Forest Regression

### Linear Regression
- R²-Wert des Modells: 0.900065308303732
- Dieses Modell erklärt etwa 90% der Variationen in den Profiten durch die unabhängigen Variablen.

### Random Forest Regression
- R²-Wert des Modells: 0.9103164738430438
- Dieses Modell erklärt etwa 91% der Variationen in den Profiten durch die unabhängigen Variablen.

## Conclusion
Both linear regression and random forest regression models provide good predictions for profit. While the random forest model slightly outperforms linear regression, both models explain a significant portion of the profit variation. Depending on other considerations like model complexity and interpretability, either model could be chosen for making profit predictions.

Feel free to explore the Jupyter Notebook for detailed code and analysis.
