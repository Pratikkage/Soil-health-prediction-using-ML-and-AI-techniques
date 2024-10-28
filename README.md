# 🌱 Soil Property Prediction Using Machine Learning

## 📖 Overview
India's agricultural sector, crucial to its economy and food security, relies heavily on soil quality. However, the overuse of chemical fertilizers has led to soil degradation, impacting crop yield and sustainability. This project uses machine learning to predict key soil properties—**Calcium**, **Phosphorus**, **pH**, **Soil Organic Carbon**, and **Sand**—from spectroscopy data. Accurate soil property predictions help farmers make informed decisions about fertilizer application, supporting sustainable agriculture and resource use.

## 🎯 Purpose
This project aims to:
- 🧪 Use machine learning to predict soil properties affecting soil health.
- ⚠️ Provide early warnings about potential soil issues.
- 🌾 Help farmers and stakeholders make informed, sustainable choices to maintain soil quality and improve crop yield.

## 📊 Dataset
The project leverages the **Africa Soil Property Prediction** dataset, which includes spectroscopy data specific to soil properties essential for farming decisions. The data is split into training and testing sets to ensure model accuracy and robustness.

## 💻 Machine Learning Models
The following models are evaluated to find the best fit for soil property prediction:
- **Ridge Regression**
- **Lasso Regression**
- **Random Forest Regression**


Based on preliminary results, **Gradient Boosting** showed the highest accuracy for most properties, making it the top choice.

## 🔄 Methodology

### 1. 🗂️ Dataset Preparation
   - **Data Collection**: The Africa Soil Property Prediction dataset is used.
   - **Data Splitting**: The data is divided into training (80%) and testing (20%) sets.

### 2. 🔧 Pipeline for Preprocessing
   - **Feature Extraction**: Key features related to soil properties are extracted.
   - **Label Encoding**: Converts categorical variables to numerical format, if necessary.
   - **Standard Scaling**: Normalizes feature distributions for model input.
   - **Outlier Removal**: Removes outliers to improve data quality.
   - **Data Cleaning**: Final data preprocessing produces a clean dataset.

### 3. 🤖 Model Training
   - **Regression Models**: Ridge Regression, Lasso Regression, and Random Forest models are trained.
   - **Hyperparameter Tuning**: Grid search is used to optimize each model.

### 4. 📈 Model Evaluation and Selection
   - **Testing on Test Data**: Models are tested, with R² as the key metric.
   - **Best Model Selection**: Gradient Boosting, achieving high accuracy, is selected.

### 5. 🚀 Model Deployment
   - **Deployment**: The best-performing model is deployed to predict soil properties in real-time, aiding farmers in soil and fertilizer management.

## ⚙️ Installation

### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`


