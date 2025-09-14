This is a simple ensemble based AdaBoost technique that avoids complicated overfitting, ranked 13 out of 4400 competitors. In this case less was more.
# Binary Rainfall Prediction – Kaggle Playground Competition

This repository contains my code and experiments for a Kaggle Playground competition on **binary rainfall prediction**.  
The goal of the competition is to build a model that predicts whether rainfall occurs (1) or not (0) based on meteorological features.  

## Approach  

All of the work is implemented in a Jupyter Notebook (`Rainfall_Prediction.ipynb`).  
The workflow follows these steps:  

1. **Exploratory Data Analysis (EDA)**  
   - Basic exploration of feature distributions  
   - Handling missing values and preprocessing  

2. **Model Exploration**  
   - Initial trials with ensemble methods (Random Forest, Gradient Boosting, etc.)  
   - Performance comparison of different classifiers  

3. **Final Model**  
   - Selected **AdaBoost Classifier** as the primary model for predictions  
   - Tuned hyperparameters to improve performance  
   - Evaluated using competition metrics (accuracy / log-loss depending on setup)  

## Repository Structure  

```
.
├── Rainfall_Prediction.ipynb # Main notebook with code and experiments
└── README.md # Documentation

```

## Requirements  

- Python 3.8+  
- Jupyter Notebook  
- scikit-learn  
- pandas, numpy, matplotlib, seaborn  

How to Run

Clone this repository:
```bash
#!/bin/bash
git clone https://github.com/sauravdas101/rainfall-prediction.git
cd rainfall-prediction
```
Open the Jupyter Notebook:

```bash
#!/bin/bash
jupyter notebook Rainfall_Prediction.ipynb
```
