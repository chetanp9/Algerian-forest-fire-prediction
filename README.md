# Algerian Forest Fire Prediction

This project focuses on predicting the occurrence and severity of forest fires in Algeria using machine learning techniques. The project utilizes a dataset that contains various environmental and meteorological factors to build a predictive model.

## Overview
The primary goal of this project is to predict forest fires in the Algerian region based on key environmental variables such as temperature, humidity, wind speed, and rainfall. By leveraging machine learning algorithms, this project aims to help in early detection and prevention of forest fires.

## Dataset
The dataset contains environmental features, including:
- **Temperature**: The average temperature in the region.
- **Humidity**: The moisture content in the air.
- **Wind Speed**: Wind velocity, which can influence fire spread.
- **Rainfall**: Precipitation levels, which reduce the likelihood of fires.
- **Fire Occurrence**: Labels indicating if and when a fire occurred.

The dataset is split into training and testing sets for model validation.

## Project Workflow
1. **Data Preprocessing**: 
   - Handling missing values.
   - Scaling numerical features.
   - Encoding categorical variables if necessary.

2. **Exploratory Data Analysis (EDA)**: 
   - Analyzing the relationship between features and fire occurrences.
   - Visualizing trends and correlations between environmental factors.

3. **Model Building**:
   - Applied machine learning models logistic regression.
   - Trained models to predict fire occurrences and severity based on the environmental data.

4. **Model Evaluation**: 
   - Used accuracy, precision, recall, and F1-score to evaluate model performance.
   - Optimized the models using cross-validation and hyperparameter tuning.

## Results
- The models were able to predict the occurrence of forest fires with high accuracy.
- The Random Forest model was particularly effective in identifying key factors that contribute to fire risk.
