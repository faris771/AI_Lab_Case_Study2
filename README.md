# Case Studies: Bike Sharing Dataset Analysis  

## Table of Contents  
1. [Overview](#overview)  
2. [Case Study #1: Data Cleaning and Feature Engineering](#case-study-1-data-cleaning-and-feature-engineering)  
3. [Case Study #2: Model Comparison for Bike Demand Prediction](#case-study-2-model-comparison-for-bike-demand-prediction)  
4. [Getting Started](#getting-started)  
5. [Requirements](#requirements)  
6. [License](#license)  

---

## Overview  
This repository contains case studies focused on analyzing the Bike Sharing Dataset, which provides historical data on bike rentals aggregated hourly, along with weather and seasonal information. The two case studies cover essential steps in data preprocessing and predictive modeling, providing a comprehensive workflow for preparing data and comparing machine learning models.  

---

## Case Study #1: Data Cleaning and Feature Engineering  

### Objective  
Prepare the dataset for machine learning tasks by applying essential preprocessing techniques such as data exploration, cleaning, feature engineering, and dimensionality reduction.  

### Steps  
1. **Dataset Download**  
   Download the modified Bike Sharing Dataset from the following link:  
   [Bike Sharing Dataset](https://github.com/mkjubran/ENCS5141Datasets/tree/main/ENCS5141_BikeSharingDataset_Modified)  

2. **Data Exploration**  
   - Summarize the dataset’s structure, statistics, and insights.  
   - Identify missing values and outliers.  

3. **Data Cleaning**  
   - Handle missing data using imputation or row/column removal.  
   - Remove or correct outliers.  

4. **Feature Engineering**  
   - Analyze feature relevance using feature selection techniques.  
   - Encode categorical variables into numerical formats.  

5. **Dataset Splitting**  
   - Split the dataset into training and testing subsets.  

6. **Scaling and Normalization**  
   - Apply scaling or normalization to ensure consistency across numerical features.  

7. **Dimensionality Reduction**  
   - Use dimensionality reduction techniques to simplify the dataset while preserving essential information.  

8. **Validation**  
   - Train a Random Forest model on the preprocessed dataset.  
   - Compare performance with a model trained on the raw dataset.  

---

## Case Study #2: Model Comparison for Bike Demand Prediction  

### Objective  
Compare the performance of Random Forest (RF), Extreme Gradient Boosting (XGBoost), and Multilayer Perceptron (MLP) models for predicting categorized bike demand.  

### Steps  
1. **Categorize Bike Demand**  
   - Categorize bike demand as "extreme," "high," "medium," or "low" based on rental bike counts.  
   - Plot a histogram of the `cnt` column to understand the distribution.  

2. **Model Training and Evaluation**  
   - Train the following models on the dataset:  
     - Random Forest (RF)  
     - Extreme Gradient Boosting (XGBoost)  
     - Multilayer Perceptron (MLP)  
   - Evaluate the models’ performance and analyze their strengths and weaknesses.  

---

## Getting Started  

### Prerequisites  
- Python 3.x  
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  

### Installation  
Clone the repository:  
```bash  
git clone https://github.com/faris771/Bike-Sharing-Dataset-Analysis
cd BreadcrumbsBike-Sharing-Dataset-Analysis 
