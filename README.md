# Physicochemical Analysis for Wine Quality Prediction 🍷

**Author:** Shorya Gupta  
**Roll No:** 2K24CSUN01252  
**Algorithm Focus:** k-Nearest Neighbors (KNN) Classification  

## 📖 Project Overview
This repository contains my individual contribution to our group machine learning project. The goal is to digitize the sensory evaluation of Vinho Verde red wine by predicting its quality based on objective chemical markers. 

This project aligns with **SDG 9 (Industry, Innovation, and Infrastructure)** by applying data-driven AI solutions to upgrade quality control in the beverage industry.

## ⚙️ Methodology & Data Cleaning
While the group shared the same dataset, my specific focus was optimizing a distance-based **KNN Classifier**. Key preprocessing steps included:
* **Target Binarization:** Grouping quality scores into distinct "High Quality" (≥7) and "Low Quality" (<7) classes.
* **Feature Scaling:** Applying `StandardScaler` to ensure features with large ranges (e.g., Sulfur Dioxide) do not mathematically dominate smaller features (e.g., Chlorides) during Euclidean distance calculations.
* **Hyperparameter Tuning:** Utilizing the **Elbow Method** to iteratively test $k$ values (1-40) to find the model with the lowest error rate.

## 🚀 How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have the following libraries installed: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
3. Open `wine_quality_knn.ipynb` in Jupyter Notebook or Google Colab.
4. Ensure the `winequality-red.csv` dataset is in the same directory before running the cells.

## 📊 Key Results
* **Optimal K-Value:** 29
* **Model Accuracy:** 90.94%
* *Please see the final cell of the notebook for the full Confusion Matrix and Classification Report.*
