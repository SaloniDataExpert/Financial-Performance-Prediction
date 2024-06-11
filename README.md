# Financial Performance Prediction

## Overview
This project aims to predict the latest financial indicators for publicly traded companies based on their historical performance. The dataset comprises financial data points for 2030 companies sourced from financial reports submitted to the SEC authority EDGAR database. It spans 11 consecutive quarters from Q3-2023 (latest quarter indicated by Q0 prefix) to Q1-2021 (furthest quarter indicated by Q10 prefix). Each quarter (except for Q0) contains 17 indicators, and there are 9 targets representing the latest financial data points for each company. The primary objective is to train predictive models that can accurately map the historical financial performance of companies to their latest financial indicators.

## Objectives
1. **Data Preprocessing**: Clean and format the dataset to ensure accuracy and consistency.
2. **Exploratory Data Analysis (EDA)**: Identify trends, correlations, and insights in the data to inform model development.
3. **Model Training**: Utilize machine learning algorithms to develop predictive models capable of forecasting the latest financial indicators.
4. **Model Evaluation**: Assess the performance of the trained models using appropriate evaluation metrics and techniques.
5. **Presentation and Discussion**: Communicate findings, insights, and model recommendations to stakeholders through presentations and discussions.
6. **Validation and Implementation**: Validate assumptions and ensure successful implementation of proposed solutions.

## Dataset Details
- **Companies**: 2030 publicly traded companies
- **Quarters**: 11 consecutive quarters from Q3-2023 to Q1-2021
- **Indicators**: 17 indicators per quarter (excluding Q0)
- **Targets**: 9 targets representing the latest financial data points for each company

## Files
- `train.csv`: Training set containing historical financial data points.
- `test.csv`: Test set for evaluating model performance.
- `sample_submission.csv`: Sample submission file in the correct format.
- `data_dictionary.txt`: Detailed description of data points and columns.

## Tools and Technologies
- **Tools**: Python (Jupyter Notebook)
- **Techniques**: Machine Learning, Advanced Statistics
