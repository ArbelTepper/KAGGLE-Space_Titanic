# Spaceship Titanic: Predicting Passenger Survival

**Objective:**  
Develope a machine learning model to predict passenger survival on the Space Titanic using features such as age, cryosleep status, home planet, and room service usage. The model aims to classify passengers into two categories: survived and did not survive, leveraging a combination of feature engineering, data preprocessing, and model optimization.

## Project Overview

The ["Spaceship Titanic" Kaggle competition](https://www.kaggle.com/c/spaceship-titanic) challenges participants to predict whether passengers survived the crash. The dataset contains various passenger details, such as age, cryosleep status, home planet, room service usage, and more. The goal is to use these features to train a classification model.

## Key Features:

- **Age**: Age of the passenger.
- **Cryosleep**: Whether the passenger was in cryosleep during the journey.
- **Home Planet**: The home planet of the passenger.
- **Room Service**: Whether the passenger used room service.

## Approach:

1. **Data Preprocessing:**
   - Cleaned and encoded categorical features.
   - Handled missing values through imputation.
   - Applied feature scaling where necessary.

2. **Modeling:**
   - Initially explored various classification algorithms.
   - Applied hyperparameter tuning and cross-validation to optimize model performance.
   - Implemented feature selection to identify the most relevant features for prediction.

3. **Model Evaluation:**
   - Employed solely the accuracy evaluation metric this time, while keeping the strength and weaknesses of it in mind.

4. **Final Model:**
   - Developed a final model based on the best-performing algorithm with optimized hyperparameters.
