# 🌱 Soil Fertility Classification using Machine Learning

This project focuses on analyzing soil properties and predicting **soil fertility levels** using various machine learning algorithms. The data is preprocessed, sampled, and classified using several popular models to evaluate performance and understand soil characteristics.

## 📌 Features

- 📊 **Stratified Sampling** to maintain fertility class distribution
- 🤖 **Machine Learning Models**:
  - Decision Tree
  - Random Forest
  - Naive Bayes
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- 📈 **Model Evaluation** using:
  - Accuracy
  - Classification Report (Precision, Recall, F1-score)
- 📉 Visualization of data distributions and model performance

## 🧪 Dataset

The dataset includes soil features such as:
- pH
- Electrical Conductivity
- Organic Carbon
- Nitrogen, Phosphorus, Potassium levels
- Fertility label (target variable)

> The original CSV file is uploaded during runtime and sampled to 500 entries for faster training.

🧠 Model Training & Evaluation
Each ML algorithm is trained on the sampled soil dataset. The notebook compares their performance to help identify the best model for predicting soil fertility.
## 📄 Research Paper

This repository is backed by a research paper (currently unpublished) which describes the methodology and findings in greater detail.

👉 [Download the paper](soil_analysis_paper.docx)
